# Inconsistent Floating Element Rendering Across Browsers

This repository demonstrates a CSS bug related to inconsistent rendering of floating elements across different browsers.  The issue occurs when the total width of floating elements exceeds the width of their parent container. Some browsers handle this gracefully, while others produce unexpected overlapping or positioning.

## Bug Description

The provided CSS code uses `float: left` to position `div` elements. When the combined width of these elements exceeds the container's width, the behavior varies across browsers.

## Solution

The solution avoids using floats and instead uses flexbox for more consistent and reliable layout across different browsers.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in different browsers (e.g., Chrome, Firefox, Safari).
3. Observe the differences in how the `div` elements are rendered.
4. Open `bugSolution.html` to see the corrected version using flexbox.