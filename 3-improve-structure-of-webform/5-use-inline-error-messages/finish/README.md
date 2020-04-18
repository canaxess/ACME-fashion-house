# 5. Use Inline Error Messages
When a form control is in error, a message is often displayed next to the control. However, unless the error message is coded correctly it won't be announced by a screen reader and the user won't know the error exists and will continue to try and submit the form.

## Activity
1. Make all inline error messages programmatically associated to the controls

## Solution
* The inline error message has been added within the label element
```html
<label for="first" class="correct">First Name (required) 
  <span class="inline-alert alert-primary">First Name is empty</span>
</label>
```
## Live Demo
Use Inline Error Messages
