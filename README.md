# CSS calc() with Unitless Zero

This repository demonstrates a subtle bug involving the `calc()` function in CSS when using a unitless zero.  Some browsers may misinterpret this, leading to unexpected rendering. The solution shows how to avoid this issue.

## Bug

The `bug.css` file contains CSS that uses `calc()` with a unitless zero.  This can lead to inconsistent results across browsers. 

## Solution

The `bugSolution.css` file provides a corrected version, ensuring consistent behavior by explicitly specifying units for the zero value. 