# Uncommon HTML Bug: Unexpected Element Hiding

This repository demonstrates an uncommon bug related to hiding HTML elements using inline styles within Javascript.  The issue arises from how the `style.display` property is handled.  This example will show the bug and provide the correct way to manage element styles for a more robust solution. 

## Bug Description

The main issue is that directly manipulating the `style` property in this manner can lead to unintended consequences, especially if the code is executed multiple times. The bug will happen when the Javascript part is run multiple times.

## Bug Solution

The solution uses `classList.add` and `classList.remove` for better management of CSS classes and a more elegant and robust method to handle element display states.
