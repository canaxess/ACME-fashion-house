# 3. Highlight Required Input
Giving the user advanced notice of what they are required to complete on a form makes it much easier for them and reduces errors. The common convention is adding a red asterisk to indicate mandatory controls is not ideal and there are better accessible alternatives.

## Activity
1. Mark all form controls as required, and newsletter signup, and shipping options as optional

## Solution
* All required form controls have the word Required in the label of the control

Deciding on simpler wording to highlight controls which have to be completed makes the form a little easier to understand. Additionally placing the wording within the `<label>` element ensures the text is announced by the screen reader when the control is in focus.

### Code
```html
<label for="first">First Name (required)</label>
```
## Live Demo
[Highlight Required Input](https://canaxess.github.io/ACME-fashion-house/3-improve-structure-of-webform/3-highlight-required-input/finish/)
