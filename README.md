# CSS Vertical Centering Bug

This repository demonstrates a common error in CSS related to vertical centering. The `bug.css` file contains code that attempts to center a div both horizontally and vertically, but only achieves horizontal centering. The `solution.css` file provides the corrected code.

The problem arises from the way `margin: 0 auto;` works. It automatically centers the element only if its width is specified. In this particular case, it doesn't affect vertical centering because `margin: 0 auto;` doesn't deal with vertical properties and height.

Solutions to this vertical centering problem can be achieved using flexbox, grid, or absolute positioning combined with appropriate transform and top/left values, as demonstrated in `solution.css`.

Feel free to contribute or report any other issues.