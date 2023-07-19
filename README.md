# Code Refactor

This repo is for module one's challenge assignment.

## Description

The challenge is an On-the-job ticket/feature request Challenge (begin with starter code that you need to modify). The goal is to refactor existing code (in HTML and CSS) for a marketing agency that has hired me to make it more accessible. It is also the goal to exceed expectations and improve the codebase for long-term sustainability.

The motivation behind this project was to learn how to refactor since it is a common task for junior developers. I built this project in order to hone my own skills in HTML, CSS and Git to ensure that I begin to understand more about the developer mindset and process. The problem it solved is making the code more accessible for the marketing agency. After completing this project, I have learned a plethora in refactoring, HTML and CSS elements and the Git process.

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
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Accessing the Repo or Webpage:

- GitHub Repo URL: https://github.com/kevindimayuga/code-refactor-kd.git
- GitHub Pages WebPage Deployment URL: https://kevindimayuga.github.io/code-refactor-kd/

## Webpage Screenshot

![code refactor webpage screenshot](./assets/images/kevindimayuga.github.io_code-refactor-kd.png)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

The following steps were taken to complete the project:
- Review the purpose of the project, the user story and acceptance criteria
- Review the ins and outs of refactoring code
- Review semantic HTML elements and structure
- Review CSS
- Review code accessibility standards
- Refactor HTML and CSS
- Create Professional README file
- Add website image to README file
- Deploy website to GitHub Pages
- Submit screenshot of webpage and URLs to webpage and GitHub Repo

HTML Updates
```
<!--comments were made as needed in the HTML file-->

<title> was updated to "Horiseon Social Solution Services, Inc." </title>

the first <div> tag was updated to a <header> tag

removed <span> element in <h1>

next <div> tag was updated to a <nav> tag since it has nav links

moved "meetingimg" to header section

next <div> tag was updated to <main> tag for main content and changed "content" to "main content"

added alt attributes to specify alternate text for all images on webpage

updated "search-engine-optimization" class to id

removed "online-reputation-management" class, kept id

removed "social-media-marketing" class, kept id

next <div> tag was updated to <aside> tag

updated "benefit-lead", "benefit-brand" and "benefit-cost" classes to ids

last <div> tag was updated to a <footer> tag

made spaces between sections for clarity and cleanliness

added indents where necessary for clarity and cleanliness
```

CSS Updates
```
/*comments were made as needed in the CSS file*/

moved "a" and "p" styles to global section at top of css file

removed ".header h1 .seo" rule

updated ".header div", ".header div ul" and ".header div ul li" to ".header nav", ".header nav ul" and ".header nav ul li" 

updated .hero to .meetingimg

updated .content to .maincontent

updated "online-reputation-management" and "social-media-marketing" class (.) to id (#)

merged #search-engine-optimization, #online-reputation-management, #social-media-marketing into one

merged #search-engine-optimization img, #online-reputation-management img, #social-media-marketing img into one

merged #search-engine-optimization h2, #online-reputation-management h2, #social-media-marketing h2 into one

updated "benefit-lead", "benefit-brand" and "benefit-cost" class (.) to id (#)

merged #benefit-lead, #benefit-brand, #benefit-cost into one

merged #benefit-lead h3, #benefit-brand h3, #benefit-cost h3 into one

merged #benefit-lead img, #benefit-brand img, #benefit-cost img into one
```

Additional Updates
```
N/A
```

## Usage

N/A

## Credits

I used the following resources to help guide me to complete the refactoring project:

- [12 Refactoring Ruels of Thumb](https://betterprogramming.pub/refactoring-rules-of-thumb-for-beginners-to-become-experts-70161c3c4f20)
- [A Beginner's Guide to HTML Accessibility](https://blog.hubspot.com/website/html-accessibility)
- [HTML: A good basis for accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
- [HTML Comments: How to Use Them](https://blog.hubspot.com/website/comment-out-in-html#:~:text=To%20leave%20a%20comment%20in,with%20a%20team%20of%20developers.)
- [HTML <img> Tag](https://www.w3schools.com/tags/tag_nav.asp)
- [HTML Images Syntax](https://www.w3schools.com/html/html_images.asp)
- [HTML 'aside' Tag](https://www.w3schools.com/tags/tag_aside.asp)
- [div: The Content Division Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)
- [span: The Content Span element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span)
- [CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)
- [CSS and JavaScript accessibility best practices](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/CSS_and_JavaScript)

## License

N/A

## Badges

N/A

## Features

N/A

## How to Contribute

N/A

## Tests

N/A