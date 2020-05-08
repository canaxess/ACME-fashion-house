# 5. Write Clear Link Text
Links are the core way to navigate between webpages, but creating link text which is understandable can be a challenge. Unless the link text is well written it can be very easy or very hard for a user navigating audibly to understand where the link takes them.

## Activity
1. Replace all instances of "Shop Now" with clear link text

## Solution
* All "Shop Now" links have been altered to have the link destination on the front of the link, followed by "...Shop Now"

Link text is sorted alphabetically within the screen reader elements/links list. Placing the unique part of the link text at the beginning of the link allows a screen reader user to understand the link destination easier. The sorting is based on the unique part of the link text not the repeated 'Shop Now...'.

A screen reader user can understand the destination of the link without having to listen to several audible 'Shop Now...' before hearing the important destination text.

### Code
```html
<a class="btn btn-link stretched-link text-reset correct" href="#">
  Bags Collection Shop Now <i class="fe fe-arrow-right ml-2"></i>
</a>
```

## Live Demo
[Write Clear Link Text](https://canaxess.github.io/ACME-fashion-house/2-add-pagelevel-content/5-write-clear-link-text/finish/)
