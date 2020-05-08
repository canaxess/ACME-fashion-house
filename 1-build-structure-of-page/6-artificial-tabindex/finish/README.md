# 6. Avoid An Artificial Tabindex
Every interactive element on a webpage receives keyboard focus when the user presses the tab key. That is unless the attribute `tabindex` is added to elements. When the value of `tabindex` is artificially altered and used incorrectly it causes many headaches.

## Activity
1. Remove the artificial `tabindex` attribute on all the footer elements and observe the before and after effects<p>
_Hint: use the keyboard to tab through the content to find which elements receive focus in an order which is different to how they are displayed_

## Solution
* All footer links have the `tabindex` attribute removed

Removing the `tabindex` attribute and value `-1` from all footer links reset the focus order for these links. The footer links will receive focus in the order they are displayed and will become the last focusable links on the page.

## Live Demo
[Avoid An Artificial Tabindex](https://canaxess.github.io/ACME-fashion-house/1-build-structure-of-page/6-artificial-tabindex/finish/)
