# 5. Use Inline Error Messages
When a form control is in error, a message is often displayed next to the control. However, unless the error message is coded correctly it won't be announced by a screen reader and the user won't know the error exists and will continue to try and submit the form.

## Activity
1. Make all inline error messages programmatically associated to the controls

## Solution
* The inline error message has been added within the label element

Placing the inline error message (the span element) within the `<label>` element uses the established programmatic association with the control. When the control receives focus, the label is announced followed by the error message.

The error message can be injected into the `<label>` element or a style toggled to only show the message on error.

### Code
```html
<label for="first">First Name (required) 
  <span class="inline-alert alert-primary">First Name is empty</span>
</label>
```
## Live Demo
[Use Inline Error Messages](https://canaxess.github.io/ACME-fashion-house/3-improve-structure-of-webform/5-use-inline-error-messages/finish/)
