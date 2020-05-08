# 6. Use A Validation Summary
A validation summary acts as a convenient grouping mechanism where all errors are located in one region without forcing the user to tab through each control individually to see if it has an error.

## Activity
1. Add a validation summary for the whole form

## Solution
* The validation summary has been added above the form
* `<ul>` elements are used for each error within the validation summary

The `<ul>` element groups related items together and allows the screen reader to announce the number of items in the list. An `<ol>` element could also be applied, but there isn't necessarily a strong requirement to provide the position of each item in the list as well as the item.

The validation summary also has a `<h2>` element to provide a hierarchy and is positioned directly above the form all to assist in locating the summary.

### Code
```html
<div class="alert alert-danger">
<h2 class="alert-heading">Errors have occurred</h2>
<hr>

  <ul>
    <li>Title is blank</li>
    <li>First Name is blank</li>
    <li>Last Name is blank</li>
    <li>Email Address is blank</li>
  </ul>

</div>
```

## Live Demo
[Use A Validation Summary](https://canaxess.github.io/ACME-fashion-house/3-improve-structure-of-webform/6-use-validation-summary/finish/)
