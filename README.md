# 01-horiseon-code-refactor
Homework 01: Refactoring code to meet accessibility standards.

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

## Summary of Changes

* Updated website title
* Moved header out of body and to header/h1 tags
* Fix linking to Search Engine Optimization
* Simplified header HTML and CSS
* Add nav bar
* Updated to use aside for right-hand content and consolidated CSS
* Reduced use of div throughout HTML

To Do:
* Update to use main, section, articles
* Consolidate CSS where possible.
* When window resizes, how to get nav bar to not look awkward?, have it not move? set overflow?
