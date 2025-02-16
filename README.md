# Uncommon HTML/JavaScript Bug: Permanently Hidden Div

This repository demonstrates a subtle bug involving the permanent hiding of an HTML element due to missing code in the JavaScript function.  The `myDiv` element is hidden when the button is clicked but is never made visible again. This is an uncommon error because it's not a syntax error or a runtime error but a logic error that's easy to overlook.

## How to Reproduce
1. Open `bug.html` in a web browser.
2. Click the button. The div should disappear and remain hidden permanently.

## Solution
The solution is provided in `bugSolution.html`. It adds the necessary code to toggle the visibility of the div.