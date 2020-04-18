# 4. Group Related Controls
Grouping related controls together can help a user understand relationships more clearly between components. Form controls may be grouped visually next to each other, but if the user is unable to identify the visual grouping any relationship between controls can be difficult to understand.

## Activity
1. Group the shipping options together

## Solution
* The shipping options are grouped within a `<fieldset>` element
* The `<legend>` element has the text '**Please indicate your shipping preferences by selecting the relevant option**'
```html
<fieldset class="correct">
<legend>Please indicate your shipping preferences by selecting the relevant option</legend>

~ shipping option controls ~

</fieldset>
```

## Live Demo
Group Related Controls
