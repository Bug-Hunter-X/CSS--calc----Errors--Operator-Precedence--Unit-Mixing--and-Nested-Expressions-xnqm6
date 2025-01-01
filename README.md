# CSS `calc()` Errors and Solutions

This repository demonstrates common errors and solutions related to using the `calc()` function in CSS.  `calc()` offers powerful flexibility for dynamic calculations but requires careful attention to detail.  Incorrect usage can lead to unexpected layouts and visual inconsistencies across browsers.

The `bug.css` file showcases examples of erroneous `calc()` usage, such as unit mixing and incorrect operator precedence.  The `bugSolution.css` file provides the corrected versions with explanations.

Issues include:

* **Unit Mixing:** Combining percentages, pixels, ems, etc., without explicit multiplication often leads to errors.
* **Operator Precedence:**  Incorrect order of operations can produce wrong results.
* **Nested Expressions:**  Complex nested expressions may need extra parentheses to ensure correct evaluation.
* **Browser Compatibility:** Certain `calc()` usages may not be supported by older browsers.