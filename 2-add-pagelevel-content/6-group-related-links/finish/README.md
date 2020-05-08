# 6. Group Related Links
Sometimes links on a page are related, they may be links in the header such as navigation or links in the footer. When a grouping mechanism is used for these links it can trigger the screen reader to announce extra information which can assist the user in understanding how the page is structured.

## Activity
1.	Use an unordered list element to group related footer links together

## Solution
* All footer links contained in `<ul>` list elements

Grouping related links together within `<ul>` elements can trigger the screen reader to announce the number of items within the list. This extra infromation can be thought of as meta data which helps a user understand how the page is structured.

### Code
```html
<ul>
  <li><a class="text-gray-300 " href="#">Contact Us</a></li>
  <li><a class="text-gray-300 " href="#">FAQs</a></li>
  <li><a class="text-gray-300 " href="#">Size Guide</a></li>
  <li><a class="text-gray-300 " href="#">Shipping &amp; Returns</a></li>
</ul>
```

## Live Demo
[Group Related Links](https://canaxess.github.io/ACME-fashion-house/2-add-pagelevel-content/6-group-related-links/finish/)
