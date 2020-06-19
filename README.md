# Horiseon Home Page Code Refactor
The Horiseon Home Page was refactored to:
-meet accessibility standards
-incorporate HTML semantics
-simplify the CSS stylesheet
-improve page performance

Horiseon's revised home page can be accessed at the following link:
https://hilbug.github.io/01-horiseon-code-refactor/

The following image is a preview of the page:
![Screen Shot 2020-06-18 at 11 24 26 PM](https://user-images.githubusercontent.com/65197724/85094974-13a98200-b1be-11ea-8f10-c2d586cb5f0d.png)

The client's __User Story__ was:

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

The client's __Acceptance Criteria__ was: 

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

Here is a detailed __Summary of Changes__:

* Website title
* Fixed linking to Search Engine Optimization
* Simplified header HTML and added nav
* Updated to use html elements: main, aside, footer
* Consolidated CSS
* Reduced use of divs
* Incorporated ARIA labels for accessibility