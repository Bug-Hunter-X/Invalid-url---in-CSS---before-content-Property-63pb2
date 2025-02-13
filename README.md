# Invalid url() in CSS ::before content Property

This repository demonstrates an uncommon error in CSS involving the misuse of the `url()` function within the `content` property of a `::before` pseudo-element.  The example showcases the problem and its solution.

## Bug
The `bug.css` file contains the incorrect CSS rule.  It attempts to use `url()` to include an image directly in the `content` property, which is invalid. 

## Solution
The `solution.css` file provides the corrected CSS using background-image instead.