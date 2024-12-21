# Redundant Visibility and Display Style Settings in HTML
This repository demonstrates a subtle HTML/CSS bug involving redundant style settings for element visibility.  The bug involves setting both `display: none` and `visibility: hidden` on the same element. While modern browsers might handle this without issues, this is bad practice and could lead to unexpected behavior in some cases.

## Bug Description
The bug is present in `bug.html`.  The script attempts to hide a div element by setting both `display: none` and `visibility: hidden` in JavaScript. This is redundant; only one is necessary.

## Solution
The corrected code is provided in `bugSolution.html`.  It uses only one method (`display: none`) to hide the element, which is cleaner and more consistent.