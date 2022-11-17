# Challenge 01 - SEO Refactor

[Link to my project](https://ryan-young17.github.io/seo-refactor/)

## Table of Contents
- [Description](#description)
- [Visuals](#visuals)

## Description
In order to make this agency's website codebase follow accessibility standards, while also improving its search engine optimization, I changed each of the generic element tags in the HTML file to semantic element tags. For example: instead of using "div" and "span", I replaced them with more clear element tags such as, "header", "section", "article", "aside", "nav", "abbr" and "footer". I also added meta tags to include a description of the website content, keywords, and viewport so the website would be viewable on varying devices, such as a mobile device or a computer screen. The "Search Engine Optiimization" link in the navigation was broken, so I added an id to that article element in order to fix it.

To follow accessibility standards, I added a title of "Search Engine Optimization" in the Horiseon heading to show viewers what SEO stands for. I also added alt text for each of the images on the webpage.

The CSS file had redundant class styles, so I consolidated the benefits in the aside to become one class "benefit", instead of three separate ones (i.e. benefit-lead, benefit-brand, benefit-cost). I did the same consolidation with the Search Engine Optimization, Online Reputation Management, and Social Media Marketing article styling--making them one class article. I also changed div to nav to match the new nav tag in the HTML file.

## Visuals
![Screenshot of the Horiseon Website](assets/images/screenshot.png)
