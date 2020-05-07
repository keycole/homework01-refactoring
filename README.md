Code changes made to index.html
Line 5 - Inserted standard meta info.

Line 7 - Added a clear, concise, relevant title to the page.

Line 11 - Changed div to header using semantic HTML.

Line 13 - Added aria-label and aria-hidden to instruct screen readers to read Horiseon as one word. Renamed span class to describe the sylistic effect.

Line 15 - Changed div to nav using semantic HTML.

Lines 19, 22, & 25 - Updated anchor links to make them functional.

Line 31 - Removed div and added image with alt text.

Line 32 & Line 82 - Added Main tag to identiy the main content on the page.

Line 34 - Changed div to section using semantic HTML and renamed class.

Line 35 - Changed div to article using semantic HTML and renamed class to consolidate the class name for all children of the section.

Line 36, 43, 50 - Added alt text for the image.

Line 37, 44, 41  - Added a name to enable anchor tag functionality.

Line 58 - Changed div to aside using semantic HTML and modified class name.

Line 59, 67, 74 - Change dive to article and modify class to consolidate the class name for all children of the aside.

Line 62, 69, 76 - Added empty alt tags to instruct screen readers to skip icons that do not add to the information on the page.

Line 84 - Changed div to footer using semantic HTML.


Code changes made to ./assets/css/style.css
Overall: 
- Reorganized the order so that style rules are listed in the order that they appear in the HTML file.
- Removed redundant style rules.

Line 12 - Changed .header style to target header selector.

Line 19 - Removed header selector and simply left h1. This is the only h1 on the page so its location does not need to be specified to the header.

Line 24 - Removed header and updated span class to mirror the change made in the HTML file. gray-text is more descriptive of the stylistic effect that is achieved via the span.

Line 28 - Simplified selector to nav.

Line 36 - Simplified selector to ul.

Line 40 - Simplified selector to li.

Line 51 - Moved image file into the HTML file.

Line 58 - Renamed class products to be reflective of the purpose of the section.

Line 64 - Consilidated all children of the products section into one class: product-definition. Deleted redundant styling rules.

Line 73 - Consilidated all children of the products section into one class: product-definition. Deleted redundant img styling rules.

Line 82 - Consolidated all h2 styling rules into one.

Line 98 - Changed class name to benefits to better describe the purpose of the aside.

Line 109 - Consolidated all h3 styling rules into one.

Line 114 - Consilidated all children of the benefits aside into one class: benefit-description. Deleted redundant img styling rules.

Line 120 - Consilidated all children of the benefits aside into one class: benefit-description. Deleted redundant styling rules.

Line 126 - Changed selector to footer.

Line 133 - Changed footer class to footer element.

# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
