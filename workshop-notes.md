# Web Accessibility Workshop
Introduction to some resources and tools to help us learn more about the #a11y community.

Building in accessibility from the beginning of the design and development process improves usability for everyone. 

## Reading List

### Books
- [Design for Real Life](https://abookapart.com/products/design-for-real-life) by Eric Meyer and Sara Wachter-Boettcher
- [Accessibility for Everyone](https://abookapart.com/products/accessibility-for-everyone) by Laura Kalbag
- [Inclusive Design Patterns](https://shop.smashingmagazine.com/products/inclusive-design-patterns) by Heydon Pickering
- [A Web for Everyone: Designing Accessible User Experiences](https://rosenfeldmedia.com/books/a-web-for-everyone/) by Sarah Horton and Whitney Quesenbery
	- [Illustrations on Flickr](https://www.flickr.com/photos/rosenfeldmedia/sets/72157638911360206/)
- [Color Accessibility Workflows](https://abookapart.com/products/color-accessibility-workflows) by Geri Coady

### Websites and a podcast
- [How to do an Accessibility Review](https://developers.google.com/web/fundamentals/accessibility/how-to-review)
- [Practical Hands-On Accessibility Testing](https://incl.ca/speaker/practical-hands-accessibility-testing-preparation/)by Nicolas Steenhout
- [A11y Rules podcast](https://a11yrules.com/) hosted by Nicolas Steenhout
- [A11yproject.com](https://a11yproject.com/)
	- [Web Accessibility Checklist](https://a11yproject.com/checklist.html)
-[ Inclusive design patterns](https://inclusive-components.design/) by Heydon Pickering

### Webinars
- [Creating Accessible PDFs](https://www.lynda.com/Acrobat-tutorials/Creating-Accessible-PDFs/669540-2.html?es_sh=b79e15e3a3caee6673ea262eb4659e22&es_ad=50312) on lynda.com
### Tools
- [Google lighthouse](https://developers.google.com/web/tools/lighthouse/)
- [aXe Developer Tools](https://addons.mozilla.org/en-US/firefox/addon/axe-devtools/?src=collection) by Deque Labs
	- Add accessibility auditing to the Firefox Developer Tools or Chrome
- [Contrast Ratio](http://contrast-ratio.com/) By Lea Verou
- [WAVE accessibility tools](http://wave.webaim.org/)
- [Color contrast checker](https://webaim.org/resources/contrastchecker/)

## WCAG and Web standards

Content and interaction elements should be tested for accessibility in accordance to the WCAG 2.0 AA (the standard for UC) guidelines and success criteria. 
- [How to meet WCAG 2 (Quick reference)](https://www.w3.org/WAI/WCAG20/quickref/)
- [WCAG Web content accessibility guidelines](https://www.w3.org/TR/WCAG/)
- [W3C Evaluating Web Accessibility](https://www.w3.org/WAI/test-evaluate/)
- [WCAG Myths](https://www.w3.org/WAI/GL/wiki/WCAG_Myths)
- [Color ratio on WCAG](https://www.w3.org/TR/WCAG/#visual-audio-contrast)
- [Contrast checker](https://webaim.org/resources/contrastchecker/)

## Color contrast
- WCAG 2.0 level AA requires a contrast ratio of at least 4.5:1 for normal text and 3:1 for large text. 
- Level AAA requires a contrast ratio of at least 7:1 for normal text and 4.5:1 for large text.
	- Large text is defined as 14 point (typically 18.66px) and bold or larger, or 18 point (typically 24px) or larger.
	- some ucla health site colors urls can be shared
		- [\#363636](http://contrast-ratio.com/#%23363636-on-white)
		- [another color combo](http://contrast-ratio.com/#%23606060-on-rgba%28255%2C%20255%2C%20255%2C%200.70%29)
- Is JavaScript required in WCAG?
	- WCAG 2 does not prevent you from using or relying on JavaScript.
	-  [no statement](http://lists.w3.org/Archives/Public/w3c-wai-ig/2012OctDec/0223.html)
	- [But about 1.1% of users don’t have JavaScript](https://stackoverflow.com/questions/21235312/accessibility-and-using-javascript)

## Manual testing
When it is not feasible to test every single page of a website you may need to focus on just critical and representational pages. 
- site templates
- interactive forms
- dynamic content pages
- dialog modals and alerts
- Key entry and exit pages (including account login and recovery pages)
- Contact and help pages
- Pages that receive the most visits and traffic identified with analytics