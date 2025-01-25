# Uncommon HTML Bug: Incorrect innerHTML Assignment

This repository demonstrates a subtle but potentially problematic error in HTML involving the incorrect usage of `innerHTML`. The bug arises from a missing quotation mark around the new HTML string being assigned to the `innerHTML` property. This results in a runtime error because the JavaScript interpreter fails to correctly parse the code.

## Bug Description
The `bug.html` file contains a JavaScript script that attempts to update the `innerHTML` property of a div element. However, due to missing quotes around the new HTML string, the code fails to execute correctly.

## Solution
The `bugSolution.html` file shows the corrected version of the code.  The solution involves simply enclosing the new HTML string in quotation marks, which ensures the browser correctly interprets the code and updates the `innerHTML` property without error.

## How to Reproduce the Bug
1. Clone this repository.
2. Open `bug.html` in your web browser.
3. You should see a JavaScript error in your browser's console indicating a syntax error.

## How to Fix the Bug
1. Refer to `bugSolution.html` for the corrected version.
2. Notice the quotes around the new HTML string within the `innerHTML` assignment.