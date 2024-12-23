# Unexpected Behavior with calc() and Percentage Widths in CSS

This repository demonstrates an uncommon issue related to the `calc()` function in CSS. When using percentage values within `calc()` and the parent element's width isn't explicitly defined, unexpected results can occur.

## The Problem
The `calc()` function is powerful, but it's important to understand how it handles dependencies. The example demonstrates how this may not behave as expected when the parent width is indirectly calculated or not set.

## Solution
The solution involves ensuring the parent element has a clearly defined width, so the percentage values in the `calc()` function can resolve correctly. This can be done by setting the parent's width explicitly, or by ensuring its width is defined by its content or other CSS rules that provide a definite dimension.