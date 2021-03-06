# code-refactor

Refactoring the "Horiseon" home page.

Refactoring of the provided HTML and CSS code was done to meet these goals:

- Incorporate semantic HTML elements

- Organize the elements to follow a logical structure independent of styling and positioning

- Use accessible alt attributes for images

- Organize the CSS attributes in sequential order

- Use a concise, descriptive title in the title element


THe goals where reached by:

- Replacing 'div' tags in the original HTML code with semantic tags to provide better readibility and understanding of what the various elements and blocks of code represent.  A 'main' tag was placed around the key content.  Comments were added to make the code understandable.

- Organizing the HTML code to flow in manner consistent with the content as viewed in the browser.

- Providing each image with an alt attribute for accessibility.

- Reorganizing the CSS code to flow with the HTML code.  Redundant styling was removed by applying identical class names to elements with identical styling.  Comments were added to improve readability.

- Using the company name in the title so the tab will be more descriptive.

Notes:
- Browser-specific default styling was eliminated by including reset.css prior to the page-specific styling.  This provides a consistent appearance across all browsers.

- The height of the <aside class="benefits"> was matched to the "Content" section so that the tops and bottoms of these sections remain even as the page is zoomed in/out or the browser window is re-sized.  This was done by applying 'height' and 'overflow' attributes to the 'aside'.

- An id was added to line 40 of the HTML code to make the link on line 21 functional.

- A hover affect was added to the links in the header.

