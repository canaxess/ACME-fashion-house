# 2. Decorative And Descriptive Images
For vision impaired users every image needs to provide a text alternative, which is a way for the user to understand what the image is describing. But if the image is decorative, this description is not required, in both instances though the ALT attribute is required.

## Activity
1. Add `ALT` text to images you think require a description and null `ALT` text to images you think should be ignored

## Solution
* Images which assist a user understanding the page have descriptive `ALT` text whilst decorative images have blank `ALT` text

### Code
**Descriptive image**<br>
`ALT` text causes the screen reader to announce the text. The text must convey what the image is showing.
```html
<img class="card-img-top card-img-front correct" src="../../../assets/img/site/sandals.png" 
width="253" height="300" alt="open toe sandals">
```
**Decorative image**<br>
Null `ALT` text causes the screen reader to ignore the image, this is especially useful for decorative images which don't need to be conveyed.
```html
<img src="../../../assets/img/brands/gray-350/reebok.svg" class="img-fluid mb-7 mb-md-0 correct" alt="">
```

## Live Demo
[Decorative And Descriptive Images](https://canaxess.github.io/ACME-fashion-house/2-add-pagelevel-content/2-decorative-descriptive-images/finish/)
