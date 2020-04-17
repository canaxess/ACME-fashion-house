# 6. Group Related Links
Sometimes links on a page are related, they may be links in the header such as navigation or links in the footer. When a grouping mechanism is used for these links it can trigger the screen reader to announce extra information which can assist the user in understanding how the page is structured.

## Activity
1.	Use an unordered list element to group related footer links together

## Solution
* All footer links contained in `<ul>` list elements
```
<ul class="correct">
  <li><a class="text-gray-300 " href="#">Contact Us</a></li>
  <li><a class="text-gray-300 " href="#">FAQs</a></li>
  <li><a class="text-gray-300 " href="#">Size Guide</a></li>
  <li><a class="text-gray-300 " href="#">Shipping &amp; Returns</a></li>
</ul>
```

## Live Demo
Group Related Links