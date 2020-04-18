# 6. Use A Validation Summary
A validation summary acts as a convenient grouping mechanism where all errors are located in one region without forcing the user to tab through each control individually to see if it has an error.

## Activity
1. Add a validation summary for the whole form

## Solution
* The validation summary has been added above the form
* `<ul>` elements are used for each error within the validation summary
```html
<div class="alert alert-danger correct">
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
Use A Validation Summary
