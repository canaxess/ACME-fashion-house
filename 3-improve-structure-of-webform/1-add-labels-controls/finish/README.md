# 1. Add Labels To Controls
Nearly all form elements need a label. Without a label form controls that receive keyboard focus will only announce the type of control to the screen reader user not what type of data is required. When a label doesn’t provide enough information describing what to enter, more errors are likely.

## Activity
1.	Programmatically associate all labels to the form controls Title, First name, Last name, Email address

## Solution
* All form controls have a programmatically associated label using the `FOR` attribute of the label with the `ID` of the form control

Using the `FOR` and `ID` attributes creates a programmatic link between the label and control and ensures when the control receives focus the accompanying label is announced. An additional benefit is the increased control activation area where the label is used to focus the control.

### Code
```html
<label for="first" class="correct">First Name</label> 
<input type="text" id="first" class="form-control" autocomplete="off">
```

## Live Demo
Add Labels To Controls
