# CSS-G4G
Geeks 4 Geeks: CSS Tutorial, Brian Style

CSS Introduction
Last Updated : 21 Jan, 2026
CSS (Cascading Style Sheets) is a language designed to simplify the process of making web pages presentable.

It allows you to apply styles to HTML documents by prescribing colors, fonts, spacing, and positioning.
It separates content from styling and allows CSS to be reused across pages.
HTML uses tags, and CSS uses rule sets.
CSS styles are applied to the HTML element using selectors.

Understanding Cascading
Cascading in CSS defines how the browser resolves conflicts between multiple CSS rules using importance, specificity, and source order.

CSS follows a hierarchy-Inline, Internal, External styles.
Specificity decides which selector has more weight.
Later rules override earlier ones if they have equal priority.
CSS Selector
A CSS selector is a pattern used to target HTML elements and apply specific styles based on their type, class, ID, attributes, or state.

Selectors can target elements by tag, class, or ID.
Combinators allow selecting elements based on hierarchy or sibling relationships.
Attribute selectors target elements with specific attributes or values.
Pseudo-classes style elements in a particular state (e.g., :hover, :first-child).
Pseudo-elements style specific parts of an element (e.g., ::first-letter, ::after).
Advanced selectors like :not() or :nth-child() allow precise and complex selection.
Efficient use of selectors leads to clean, maintainable, and scalable CSS.
Working of CSS
CSS applies styles to HTML elements, helping the browser render a visually styled and well-structured web page

1. Load HTML

The browser fetches the HTML document from the server.

Browser requests the HTML file from the server.
Receives the HTML document as text.
2. Parse HTML

The browser analyzes HTML syntax and breaks it into meaningful tokens.

Browser reads and tokenizes HTML.
Converts tags into nodes for the DOM tree.
3. Build DOM (Document Object Model)

The browser creates a tree structure representing all HTML elements.

The parsed HTML elements form the DOM structure.
Represents all page elements and hierarchy.
4. Load CSS

The browser downloads CSS files referenced in the HTML.

When browser finds a <link> or <style>, it loads CSS files.
External CSS is render-blocking (page waits until loaded).
5. Parse CSS

The browser converts CSS into a structured CSS Object Model (CSSOM).

CSS text is parsed into the CSSOM (CSS Object Model).
Browser understands all CSS rules and selectors.
6. Compute Styles (Match + Cascade)

The browser determines the final styles for each element based on CSS rules.

Browser matches CSS rules to DOM elements.
Applies cascading rules and calculates final computed styles.
7. Build Render Tree

The browser combines DOM and CSSOM to prepare visible elements for rendering.

Combines DOM + CSSOM to create the Render Tree.
Includes only visible elements (e.g., skips display: none).
8. Layout (Reflow)

The browser calculates the size and position of each visible element.

Calculates exact position and size of each element.
Determines where elements appear on the page.
9. Paint

The browser draws visual parts like text, colors, and images onto the screen.

Converts render tree elements into actual pixels.
Draws colors, borders, text, images, etc.
10. Display (Compositing)

The browser merges all painted layers and displays the final page output.

Browser combines painted layers into the final image.
Final visual output is displayed on the screen.
Advantages of CSS
Here are some advantages of css:

Simplifies Design: Makes web design and maintenance easier.
Better Performance: Improves website performance and user experience.
Responsive Design: Supports responsive and adaptive designs for all devices.
Saves Time: Write CSS once and reuse it across multiple HTML pages.
Easy Maintenance: Change the style globally with a single modification.
Search Engine Friendly: Clean coding technique that improves readability for search engines.
Superior Styles: Offers a wider array of attributes compared to HTML.
Offline Browsing: CSS can store web applications locally using an offline cache, allowing offline viewing.
