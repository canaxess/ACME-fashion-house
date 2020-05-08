# 2. Identify Data Formats
Providing a text description with a programmatically associated label will help all users understand what type of data is required. But if that data is required to be a specific format or in a specific sequence this also needs to be communicated.

## Activity
1.	Add constraint information to the _Last name_ label describing the maximum number of allowed characters the control accepts

## Solution
* The maximum character count constraint is added into the form controls label

Providing the maximum character constraint information in the label ensures when the control receives keyboard focus, the constraint information is announced as part of the label text.

### Code
```html
<label for="last">Last Name (20 character maximum)</label>
```

## Live Demo
[Identify Data Formats](https://canaxess.github.io/ACME-fashion-house/3-improve-structure-of-webform/2-identify-data-formats/finish/)
