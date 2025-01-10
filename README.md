# CSS Pseudo-element Overlap Bug

This repository demonstrates a common yet subtle bug in CSS related to pseudo-elements (`::before`, `::after`) overlapping the main element's content.  The issue arises from improper handling of positioning within the CSS layout, specifically when the pseudo-element is absolutely positioned. 

The `bug.css` file contains the problematic code, showcasing the unexpected overlap. The `bugSolution.css` file demonstrates a corrected version with proper handling of the pseudo-element's position.