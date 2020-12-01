# 01 HTML CSS Git: Code Refactor

## Review:

After reviewing the User Story and Acceptance Criteria of the Code Refactor task, I read through the HTML and CSS documents side by side to try and identify any areas that required changes or amendments that were inline with the provided User Stories and Acceptance Criteria.

## Areas of Identification:
---

*	There is no meta information:
    * Viewport 
    * Description 
    * Keywords 	
    * Author
*	The site title is not displaying the Company name.
*	Semantics are not being used. All HTML blocks are wrapped in 'div' elements. 
*	There are no comments within the CSS or HTML.
*	The CSS file contains a lot of repeated code.
*	Search Engine Optimization id missing for Nav link.
*	No ‘alt’ attribute for any of the 'img' elements.
---
## Changes Made:

### .html document:
---

*	ADDED meta tags with content to the head of the HTML document:
	*	Description
	*	Keywords
	*	Author	
	*	Viewport
*	ADDED a title that reflects the company name ‘Horiseon’ and a small description, this now 	displays in the webpage tab.
*	EDITED the first 'div' element of the header, and replaced the 'div' with the 'header' 	semantic element.
*	REMOVED the CSS .header class from the Header semantic element.
*	EDITED the 'div' element of the 'nav' contained within the 'header', and replaced the 'div' with the 	'nav' semantic element.	
*	EDITED the Hero Section 'div' and replaced it with the 'section' semantic.
* ADDED a 'main' semantic section and moved the content and sidebar into it.
*	EDITED the content 'div' and renamed it to 'section'.
*	EDITED the 'div' within the content section and renamed them to 'article'.
*	EDITED the benefits sidebar 'div' and renamed to 'aside'.
*	ADDED the alt attribute to the three 'aside' img elements.
*	EDITED the 'div' element of the footer, and replaced the 'div' with the 'footer' 	semantic element.
*	REMOVED the CSS .footer class from the Header semantic element.
* ADDED Search Engine Optimization id to the Search Engine Optimization section, to fix 	Nav link.
*	ADDED comments to identify each section.
---
### .css document:
---

*	EDITED the CSS .header class to target the 'header' semantic element.
*	EDITED the CSS .header nav classes and removed the .header class name.
*	EDITED the CSS .footer class to target the 'footer' semantic element.
*	MERGED CSS classes with duplicate code using the dry principle.
*	ADDED comments to the code to separate the sections to reflect the HTML doc.
*	MOVED CSS code around and placed into its respective commented section.
---
## Areas used for research:

* HTML5 Semantic Elements In Depth | HTML5 | [#assemblyJS](https://www.youtube.com/watch?v=17vYHaf1E-A)
* HTML5 Semantic Tags: What Are They and [How To Use Them!](https://www.semrush.com/blog/semantic-html5-guide/)
* SEO recommendations: [Mediacom](https://www.mediacom.com/)
* Meta Description & SEO: [MOZ](https://moz.com/learn/seo/meta-description)
