# horiSEOn ADA Landing Page
Refactor an SEO landing page that is **accessible**, **legible**, and **optimized** for search engine optimization. Responsibilities include fixing HTML and CSS errors, refactoring code to reduce file size, maintain look&feel of site to provided high fidelity mocks.

- HTML REFACTORING — I replaced div tags with semantic html tags such as `<header>`, `<footer>`, `<nav>`, cleaned up redundant attributes, implemented WCAG 2.1 guidelines for accessibility such as `aria-labels` and tag ordering, implemented SEO-related attributes in the head for organic search.

- CSS REFACTORING - I consolidated repeated css attributes, reassigned classes to match semantic html, added comments, global styles and component styles for readability. To make this site work with mobile phones, I added a breakpoint and modified css attributes to match accordingly.

- MINOR IMPROVEMENTS - Brandname was originally "Horiseon", modified to "HoriSEOn" per client request.

## Installation
To use this landing page as a template, open `terminal` or `gitbash` and move to Desktop
 
    cd desktop

Create a new directory

    mkdir ada-landing-page

Clone this repo

    git clone https://github.com/mrjeoffrey/horiseon-ada.git

Open folder in VisualStudioCode and modify `index.html`

## Usage
Initial Lighthouse Report of HoriSEOn
![Initial Lighthouse Report of HoriSEOn](/assets/screenshots/lighthouse-report-initial.png "Initial SEO/Accessibility Report of HoriSEOn") 

| Performance | Accessibility | Best Practices | SEO |
| :-------: | :-------: | :-------:  | :-------: |
| 49 | 71 | 100 | 70 |


Final Lighthouse Report of Landing Page
![Final Lighthouse Report of HoriSEOn](/assets/screenshots/lighthouse-report-final.png "Final SEO/Accessibility Report of HoriSEOn")

| Performance | Accessibility | Best Practices | SEO |
| :-------: | :-------: | :-------:  | :-------: |
| 100 | 100 | 100 | 90 |

<br>


## LIVE
| DEPLOYMENT | URL | STATUS |
| ---------- | --- | ------ |
| Repository  | [github.com/mrjeoffrey/horiseon-ada](https://github.com/mrjeoffrey/horiseon-ada) |  ACTIVE 🟢   |
| Published Page     | [mrjeoffrey.github.io/horiseon-ada](https://mrjeoffrey.github.io/horiseon-ada/) | ACTIVE 🟢  |
   
   <br>

## Credits
| RESOURCE | DESCRIPTION |
| -------- | ----------- |
| [SEO Starter Guide](https://developers.google.com/search/docs/beginner/seo-starter-guide) | Documentation on optimizing a site for organic search by Google  |
|[WCAG 2.1 Accessibility Guidelines](https://www.w3.org/TR/WCAG21/) | Complete documentation for Web Accessibility Standards V 2.1 from W3C |
| [Markdown Styleguide](https://www.markdownguide.org/basic-syntax/) | Quick style guide on markdown syntax for README.md |
| [Frequent Word Utility](https://www.online-utility.org/text/frequent_words.jsp) | Select all the text on a webpage and paste in this Frequent Word Utility to see which words are frequently used. Excellent tool to determine if SEO words are being used. |
| [iloveimg Image Compressor](https://www.iloveimg.com/) | Image compression tool to reduce image size |
| [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) | Checks contrast ratios of background / foreground colors. Use this tool to slightly modify colors to pass WCAG standard |

## MIT License

Copyright (c) 2022 Jeoffrey Batangan

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.