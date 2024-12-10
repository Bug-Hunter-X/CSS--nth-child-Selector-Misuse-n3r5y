# CSS :nth-child Selector Bug

This repository demonstrates a common error involving the CSS `:nth-child` selector. The incorrect use of this selector can lead to unexpected and inconsistent styling.

The `bug.css` file contains the problematic code. The `bugSolution.css` file provides the corrected version.

## Problem

The incorrect use of `:nth-child` without specifying the element type leads to unexpected styling of all elements within the container, rather than just the desired element type.  This is a subtle but easily overlooked error that can be difficult to debug.

## Solution

The solution is to correctly specify the element type within the `:nth-child` selector to ensure only elements of the target type are affected.