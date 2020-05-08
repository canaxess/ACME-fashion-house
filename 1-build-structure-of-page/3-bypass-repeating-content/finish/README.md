# 3. Bypass Repeating Content
Page content which repeats across multiple pages is a challenge for keyboard and screen reader users if there is no way to avoid the content. If a user is forced to tab through the same set of links to reach new content every time a page has loaded in can quickly become a frustrating and fatiguing process.

## Activity
1. Add a skip link to bypass the repeating page navigation located in the header and navigate to the beginning of the "Best Picks 2020" section

## Solution
* A skiplink is added as the first link in the keyboard tab sequence
* The link is hidden using CSS until tabbed to
* The link destination is the **Best Picks 2020** heading which has an ID of `content`

Skip links are located at the top of page as the first links in the keyboard tab sequence. The CSS uses off-screen positioning to hide the link from display in its default state. When the link is focused from the keyboard its position is back onto the screen.

The skip link `href` value is `content` which is the id of the region **Best Picks 2020** focus is moved to. The skipped to region can be named anything however the `href` value of the skip link must match the `id` of the destination.

### Code
```css
#skiplink a 
{
  position:absolute;
  left:-10000px;
  top:auto;
  width:1px;
  height:1px;
  overflow:hidden;
}

#skiplink a:focus 
{
  position:static;
  width:auto;
  height:auto;
}
```

```html
<div id="skiplink">
  <a href="#content" class="correct">Skip to Main Content</a>
</div>

<div class="mb-4 h2BestPicks correct" id="content">Best Picks 2020</div>
```

## Live Demo
[Bypass Repeating Content](https://canaxess.github.io/ACME-fashion-house/1-build-structure-of-page/3-bypass-repeating-content/finish/)
