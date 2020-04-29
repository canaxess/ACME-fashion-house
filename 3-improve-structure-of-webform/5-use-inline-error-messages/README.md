# 5. Use Inline Error Messages
When a form control is in error, a message is often displayed next to the control. However, unless the error message is coded correctly it won't be announced by a screen reader and the user won't know the error exists and will continue to try and submit the form.

## Activity
1. Make all inline error messages programmatically associated to the controls

## Code
* Use the following inline error message fragment:
```html
<span class="inline-alert alert-primary">(control label text) is empty</span>
```

## Instructions
1. Alter the file `index.html` in the `/start/` directory
1. Compare your changes against the file `index.html` in the `/finish/` directory
1. Changes are described in the [README.md](finish/README.md)
