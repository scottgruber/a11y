
# Web Accessibility Workshop Notes

![Illustration of users with variety of disablities](https://github.com/scottgruber/a11y/blob/master/web-accessibility-notes-medium.jpg)

Building in accessibility from the beginning of the design and development process improves usability for everyone.

Here are some resources and tools that helped me learn more about Web Accessibility and the fantastic community of writers, designers and developers working on this topic. I prepared these notes for a workshop I led at UCLA. I hope it helps you explore this important field of study.

## Resources

### Books
- [Design for Real Life](https://abookapart.com/products/design-for-real-life) by Eric Meyer and Sara Wachter-Boettcher
- [Accessibility for Everyone](https://abookapart.com/products/accessibility-for-everyone) by Laura Kalbag
- [Inclusive Design Patterns](https://shop.smashingmagazine.com/products/inclusive-design-patterns) by Heydon Pickering
- [A Web for Everyone: Designing Accessible User Experiences](https://rosenfeldmedia.com/books/a-web-for-everyone/) by Sarah Horton and Whitney Quesenbery
	- [Illustrations on Flickr](https://www.flickr.com/photos/rosenfeldmedia/sets/72157638911360206/)
- [Color Accessibility Workflows](https://abookapart.com/products/color-accessibility-workflows) by Geri Coady

### Articles
- [How to do an Accessibility Review](https://developers.google.com/web/fundamentals/accessibility/how-to-review)
- [Practical Hands-On Accessibility Testing](https://incl.ca/speaker/practical-hands-accessibility-testing-preparation/) by Nicolas Steenhout
- [Web Accessibility Checklist](https://a11yproject.com/checklist.html)
- [Introducing the Accessibility Inspector in the Firefox Developer Tools](https://www.marcozehe.de/2018/04/11/introducing-the-accessibility-inspector-in-the-firefox-developer-tools/)
- [Using VoiceOver to Evaluate Web Accessibility](https://webaim.org/articles/voiceover/) This article is designed to help users who are new to VoiceOver learn the basic controls for testing 
- [How to enable VoiceOver on Mac](https://www.imore.com/how-enable-voiceover-mac)
- [imore.com Accessibility page](https://www.imore.com/accessibility/home)
- [smashingmagazine.com category: accessibility](https://www.smashingmagazine.com/category/accessibility/)
- [alistapart.com topic: accessibility](https://alistapart.com/topic/accessibility)
- [Keyboard Accessibility](https://webaim.org/techniques/keyboard/)
- [Keyboard-Only Navigation for Improved Accessibility](https://www.nngroup.com/articles/keyboard-accessibility/)

### Websites
- [Inclusive design patterns](https://inclusive-components.design/) by Heydon Pickering
- [A11yproject.com](https://a11yproject.com/)
- [The Paciello Group resources](https://developer.paciellogroup.com/resources/)
- [Inclusive design principles](https://inclusivedesignprinciples.org/)
- [Apple’s Accessibility site for users](https://www.apple.com/accessibility/)
- [Apple’s Accessibility site for developers](https://developer.apple.com/accessibility/)
- [Microsoft Accessibility](https://www.microsoft.com/en-us/accessibility)
- [Google Accessibility](https://www.google.com/accessibility/)
- [IBM Accessibility Research](https://www-03.ibm.com/able/)
- [Adobe’s Accessibility page](https://www.adobe.com/accessibility.html)
- [Adobe’s Accessibility blog](http://blogs.adobe.com/accessibility/)
- [Gov.UK Government Digital Service Accessibility site](https://www.gov.uk/help/accessibility)
- [Section 508.gov](https://www.section508.gov/) provides Section 508 tools, resources, standards, and news.
- [US Health and Human Services accessibility page](https://www.hhs.gov/accessibility.html)
- [A11y.me](https://a11y.me/) A good start on web accessibility for you.

### Podcasts
- [A11y Rules podcast](https://a11yrules.com/) hosted by Nicolas Steenhout

### Newsletters
- [A11y Weekly](https://a11yweekly.com/) curated by David A. Kennedy

### Webinars
- [Creating Accessible PDFs](https://www.lynda.com/Acrobat-tutorials/Creating-Accessible-PDFs/669540-2.html?es_sh=b79e15e3a3caee6673ea262eb4659e22&es_ad=50312) on lynda.com

### Tools
- [Google lighthouse](https://developers.google.com/web/tools/lighthouse/)
- [aXe Developer Tools](https://addons.mozilla.org/en-US/firefox/addon/axe-devtools/?src=collection) by Deque Labs
	- Add accessibility auditing to the Firefox Developer Tools or Chrome
- [Contrast Ratio](http://contrast-ratio.com/) By Lea Verou
- [WAVE accessibility tools](http://wave.webaim.org/)
- [Color contrast checker](https://webaim.org/resources/contrastchecker/)
- [NVDA (Non-visual Desktop Access)](http://www.nvda-project.org/) is a free and open-source screen reader for the Microsoft Windows operating system

## WCAG Web content accessibility guidelines 

Content and interaction elements should be tested for accessibility in accordance to the WCAG 2.0 AA (the standard for UC) guidelines and success criteria. 
- [How to meet WCAG 2 (Quick reference)](https://www.w3.org/WAI/WCAG20/quickref/)
- [WCAG Web content accessibility guidelines](https://www.w3.org/TR/WCAG/)
- [W3C Evaluating Web Accessibility](https://www.w3.org/WAI/test-evaluate/)
- [WCAG Myths](https://www.w3.org/WAI/GL/wiki/WCAG_Myths)


## Color contrast
- [Color ratio on WCAG](https://www.w3.org/TR/WCAG/#visual-audio-contrast)
- [Contrast checker](https://webaim.org/resources/contrastchecker/)
- WCAG 2.0 level AA requires a contrast ratio of at least 4.5:1 for normal text and 3:1 for large text. 
- Level AAA requires a contrast ratio of at least 7:1 for normal text and 4.5:1 for large text.
	- Large text is defined as 14 point (typically 18.66px) and bold or larger, or 18 point (typically 24px) or larger.

**Is JavaScript required in WCAG?**
- WCAG 2 does not prevent you from using or relying on JavaScript.
	- [No statement](http://lists.w3.org/Archives/Public/w3c-wai-ig/2012OctDec/0223.html)
	- [But about 1.1% of users don’t have JavaScript](https://stackoverflow.com/questions/21235312/accessibility-and-using-javascript)

## Manual testing
When it is not feasible to test every single page of a website you may need to focus on just critical and representational pages: 
- site templates
- interactive forms
- dynamic content pages
- dialog modals and alerts
- Key entry and exit pages (including account login and recovery pages)
- Contact and help pages
- Pages that receive the most visits and traffic identified with analytics

This article was originally posted on [my website](https://scottgruber.me/articles/web-accessibility-workshop-notes) and is also cross-posted on [github](https://github.com/scottgruber/a11y/blob/master/workshop-notes.md) and [medium.com](https://medium.com/@scottgruber/web-accessibility-workshop-notes-5d832f63fd01).




 
