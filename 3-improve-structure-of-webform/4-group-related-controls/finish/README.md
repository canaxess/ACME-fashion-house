# 4. Group Related Controls
Grouping related controls together can help a user understand relationships more clearly between components. Form controls may be grouped visually next to each other, but if the user is unable to identify the visual grouping any relationship between controls can be difficult to understand.

## Activity
1. Group the shipping options together

## Solution
* The shipping options are grouped within a `<fieldset>` element
* The `<legend>` element has the text '**Please indicate your shipping preferences by selecting the relevant option**'

The `<fieldset>` element can trigger the screen reader to announce the `<legend>` text when each control contained in the fieldset receives keyboard focus.

This grouping structure provides greater context to controls where the label text may be insufficient.

### Code
```html
<fieldset>
<legend>Please indicate your shipping preferences by selecting the relevant option</legend>

~ shipping option controls ~

</fieldset>
```

## Live Demo
[Group Related Controls](https://canaxess.github.io/ACME-fashion-house/3-improve-structure-of-webform/4-group-related-controls/finish/)
