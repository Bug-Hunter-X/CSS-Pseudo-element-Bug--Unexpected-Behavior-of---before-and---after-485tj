# CSS Pseudo-element Bug: Unexpected Behavior of ::before and ::after

This repository demonstrates an uncommon CSS bug related to the unexpected behavior of pseudo-elements (`::before` and `::after`) when used together in complex scenarios. This can lead to stacking order issues and specificity problems.

## Bug Description
The provided CSS code snippet uses `::before` and `::after` pseudo-elements to add content before and after an element. In certain contexts, this approach can result in unexpected behavior regarding element positioning and styling conflicts.  This is particularly likely when dealing with other selectors and complex layouts.

## Solution
The solution demonstrates alternative approaches to achieve the desired effect in a more robust and maintainable manner.  Instead of using two separate pseudo-elements, consider alternative techniques.