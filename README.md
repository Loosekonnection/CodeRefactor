# 01 HTML CSS Git: Code Refactor

## Summary:

<span style="color:yellow">Homework assignment 01</span>

After reviewing the README of the Code Refactor homework task, I read through the provided HTML and CSS documents side by side to try and identify any areas that required changes or amendments that were inline with the provided User Stories and Acceptance Criteria, from which I then began to list out as bullet points.

Following this I then began to work systematically down through the .html file and address each HTML block in turn, where applicable I used online resources to research additional detail on how to correct/change issues. If I identifed more issues as I worked through the documents I would add them to the Issues Identified list.

Upon editing each HTML block containing a corresponding CSS Selector I turned to the .css file to edited the selectors to reflect my amendments within the HTML.

I then added comments to both of the HTML and CSS files, and then reorganised the code in the .css file to reflect the .html structure, and comment order.

---
<br>

## Issues Identified:

*	There is no meta information:
    * Viewport - <span style="color:red">Although there is no users story or criteria for responsive design, this is an important accessibility feature that needs raising.</span>
    * Description 
    * Keywords 	
    * Author
*	The site title is not displaying the Company name.
*	Semantics are not being used. All HTML blocks are wrapped in ```<div>``` elements. 
*	There are no comments within the CSS or HTML documents.
*	The CSS file contains a lot of repeated code.
*	Search Engine Optimization id missing for Nav link.
*	No ```alt``` attribute for any of the ```<img>``` elements.
*   ```header``` & ```heading (h1/h3)``` should not be qualified.
---
<br>

## Changes Implemented:

<span style="color:yellow">.html document:</span> 
<br>

*	ADDED meta tags with content to the head of the HTML document:
	*	Description
	*	Keywords
	*	Author	
	*	Viewport
*	ADDED a title that reflects the company name ‘Horiseon’ and a small description, this now 	displays in the webpage tab.
*	EDITED the first ```<div>``` element of the header, and replaced the ```<div>``` with the ```<header>``` 	semantic element.
*	REMOVED the CSS ```.header``` class from the Header semantic element.
*	EDITED the ```<div>``` element of the ```<nav>``` contained within the ```<header>```, and replaced the ```<div>``` with the 	```<nav>``` semantic element.	
*	EDITED the Hero Section ```<div>``` and replaced it with the ```<section>``` semantic.
* ADDED a ```<main>``` semantic section and moved the content and sidebar into it.
*	EDITED the content ```<img>``` and renamed it to ```<section>```.
*	EDITED the ```<img>``` within the content section and renamed them to ```<article>```.
*	EDITED the benefits sidebar ```<div>``` and renamed to ```<aside>```.
*	ADDED the alt attribute to the three ```<aside>``` img elements.
*	EDITED the ```<img>``` element of the footer, and replaced the ```<img>``` with the 'footer' 	semantic element.
* ADDED the id of 'Search Engine Optimization' to the Search Engine Optimization section, to fix Nav link.
*	ADDED comments to identify each section.
*   ADDED ```header``` & ```heading (h1/h3)``` classes to their respective HTML elements.
<br>

<span style="color:yellow">.css document:</span>
<br>

*	EDITED the CSS ```.header``` class to target the ```<header>``` semantic element.
*	EDITED the CSS ```.header nav``` classes and removed the .header class name.
*	EDITED the CSS ```.footer``` class to target the ```<footer>``` semantic element.
*	MERGED the CSS classes containing duplicate code using the dry principle.
*	REORDERED the CSS code  and placed into its respective commented section.
*	ADDED comments to the code to separate the sections to reflect the HTML structure.
*   DECLARED ```header``` & ```heading (h1/h3)``` selectors as classes.
---
<br>


## Credit Sites used for research:
<br>

*   HTML5 Semantic Elements In Depth | HTML5 | [#assemblyJS](https://www.youtube.com/watch?v=17vYHaf1E-A)
*   HTML5 Semantic Tags: What Are They and [How To Use Them!](https://www.semrush.com/blog/semantic-html5-guide/)
*   SEO recommendations: [Mediacom](https://www.mediacom.com/)
*   Meta Description & SEO: [MOZ](https://moz.com/learn/seo/meta-description)
*   CSS Selectors and Best Practices [Stack Overflow](https://stackoverflow.com/)

---
<br>

![code-review](https://img.shields.io/badge/code--review-ready%20for%20critique-orange)

<br>

---
© 2020 Loosekonnection, Working towards being a Full Stack Dev.