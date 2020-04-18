# 1. Add Labels To Controls
Nearly all form elements need a label. Without a label form controls that receive keyboard focus will only announce the type of control to the screen reader user not what type of data is required. When a label doesn’t provide enough information describing what to enter, more errors are likely.

## Activity
1.	Programmatically associate all labels to the form controls Title, First name, Last name, Email address

## Solution
* All form controls have a programmatically associated label using the `FOR` attribute of the label with the `ID` of the form control

```html
<label for="first" class="correct">First Name</label> 
<input type="text" id="first" class="form-control" autocomplete="off">
```

## Instructions
1. Alter the file `index.html` in the `/start/` directory
1. Compare your changes against the file `index.html` in the `/finish/` directory
