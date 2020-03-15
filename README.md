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

1. WHEN I view the source code
THEN I find semantic HTML elements (V)
>Used <nav><section><aside><footer><div> for showing semantic HTML elements. 

2. WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
> Used <header><main><h1><h2><h3><ul><p> for showing a logical structure and css classes to be independent of styling and poistioning.  

3. WHEN I view the image elements
THEN I find accessible alt attributes (V)
> Added alt attributes with image explanation for finding accessbility.  

4. WHEN I view the heading attributes
THEN they fall in sequential order (V)
> HTML/CSS codes are sequentially ordered and described with remark for easy understanding.

5. WHEN I view the title element
THEN I find a concise, descriptive title (V)
> Simplified the duplicated codes on HTML/CSS for finding a concise and renamed classese as more descriptive titles.
```

## Review

You are required to submit the following for review:

* The URL of the deployed application. (V)

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project. (V)

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
