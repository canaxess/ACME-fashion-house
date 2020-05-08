# 4. Add Keyboard And Mouse Focus
The often-overlooked way of navigating a website is via the keyboard. All interactions may be accessible from the keyboard, but if users can’t see where the screen focus is when navigating, it makes it that much harder to know where they are on the page.

## Activity
1. Create a consistent mouse and keyboard focus effect for the navigation links _Hint: this involves editing the CSS file focus.css_

## Solution
* The file `focus.css` is editted to add a CSS focus effect which underlines all links in focus from the mouse and keyboard

The same focus effect applied on keyboard and mouse navigation confirms to the user the link has the same action regardless how it is interacted with.

A consistent keyboard and mouse focus effect help users identify the screen focus when navigating by keyboard or mouse. Relying on the default browser focus effect alone can't be the only way to identify in focus elements due to differences amongst browsers.

* `a:focus` pseudo class styles a link when focused from the keyboard
* `a:hover` pseudo class styles a link when focused from the mouse

### Code
```css
a:focus, a:hover, a:focus i, a:hover i
{
	text-decoration:underline !important;
}
```

## Live Demo
[Add Keyboard And Mouse Focus](https://canaxess.github.io/ACME-fashion-house/2-add-pagelevel-content/4-keyboard-mouse-effect/finish/)
