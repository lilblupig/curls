# Curls

## Development Life Cycle

This document is to provide an brief insight into how the approach to the code structure of the website was expected to work, what changed and why, and then to summarise how the creator would now approach replicating the project.

Changes to design are documented in the UX section of the [README](README.md) under wireframes.

# Index
1. [General Approach](#reflections-on-general-approach-to-build)
1. [Lessons Learned](#lessons-learned)
1. [Revised Development Process](#revised-development-process)

## Reflections on General Approach to Build
The preparation and build plan for the project was methodical and modular, with the intention of building one thing at a time and using previous code as a template for other similar parts of the website.  To a greater extent this was achieved, but a number of early build sections had to be re-written, some a number of times, as shown in the commit history.  Greater understanding of the concepts to be used would avoid this.  The preparation and user/owner research did provide a solid foundation to work from and an excellent focus for direction in resolving issues. This approach will be repeated, along with the use of a kanban board or GitHub projects area.

Overall commits are short, concise and descriptive.  Most commits are made in the style "Change in","Page name","Section number".  This became unclear at times, such as when first building sections on the "More" page: the commit was "Add more s1". Without context this is very ambiguous.  This degenerated further when coding tired and abbreviating Page names to their first letter "Amend spacing T S2."  On future projects a predefined structure will be chosen for commits and used at all times.

The development lifecycle for this project has been quite repetetive.  As a beginner developer, the creator gained better understanding of various concepts at middle and later stages of development, that learning was then applied to previous code before moving on to the next new section in order to maintain consistency of both code and page structure.

The final draft project is well structured, absolutely responsive, fulfils the user stories, clears the W3C validators and scores highly on Lighthouse in all areas.  The creator believes the project is of good quality and has real-world value.

## Lessons Learned
As the first proper personal project, many mistakes were made in its development and a number of inappropriate approaches were taken across the board.  These can largely be narrowed down to inexperience and relying primarily upon the content provided in the LMS by Code Institute rather than supplementing that learning with self guided learning in relation to both mini code projects and industry standards and best practices.

### Preparation
The UX design process was followed closely, and the stages relating to each plane were actually fairly comprehensive.  These provided a good foundation for the production of wireframes and preparation for the build proper.

Limited knowledge of Bootstrap and the grid system that makes it so useful meant that the wireframes were not always readily translated into code.  This made for a particularly frustrating experience coding the first few pages until proper understanding was gained and utilised going forwards.  It also meant that the first few pages had to be almost completely rebuilt.

Wireframes were built PC first, with section design based heavily on this medium.  This meant trying to build everything backwards in Bootstrap, with little insight as to how the responsive classes could be readily utilised.

Assets were not adequately prepared in advance.  Hero images were uploaded at full size and in rectangular format, with little disposable edge space.  This meant that a number of images had to be discarded and new ones found to replace them that would work better in a responsive design.  Diagrams were built as the page was being written, and not designed to fit the space they were to occupy.  It is apparent that knowing the approximate size and shape of the desired asset is valuable and makes incorporating them into the website much easier.

### Build
In hindsight, the creator would choose to build with Bootstrap 4 which as an established following and a vast array of resources and supports rather than Bootstrap 5 which is fairly new, and it is therefore more difficult to find assistance for bugs.

An enormous number of best practice points became apparent on first review with the project mentor, and then subsequently when validating code and seeking assistance in the Code Institute community.  Some of these relate to code, others to how it should be approached.
* Do not override Bootstrap classes, create additional classes for the same elements/attributes and style those.
* Be sure to understand CSS specificity, overriding Bootstrap styling is difficult and confusing.  It is likely that the use of parent-child relationships, multiple classes and possibly ID's where appropriate might be necessary to override the specificity within Bootstrap.  When one considers the class system used to make Bootstrap work, this is less surprising.
* Do not use !important unless it is absolutely unavoidable.  It can be difficult to understand the hierarchy of many attributes utilising !important.
* Comments in code should use only the standard comment indicators, and not larger dash numbers as indicated in some tutorials.  HTML comments should have only two dashes, and CSS comments should have none.
* Use Bootstrap classes for manipulation of space (padding/margin etc) rather than creating custom classes.
* Always start a "col" div with col-12, regardless.
* Text on mobile should be consistently left, center or justify, always.
* Footer styling should match nav styling.
* Contrast is important, Lighthouse should rate it as at least AA.
* Browser form field validation does not work in Bootstrap modals.
* When stuck, take a break, even if just for a few minutes.  It is far quicker in the long run than doggedly trying to resolve an issue.
* When tired, stop.  Start again the next day.  The quality of the commit messages on this project dipped considerably towards the end of a full day and night coding.  This is not useful to people viewing the project, assessors marking the project or yourself going back to view the revisions made to the project.

## Revised Development Process

Based on the experience of producing the website, the creator would now take the following approach.

### Preparation
Not much changed in terms of the 5 Planes of Design, or the use of wireframes, however, the creator would now invest more time in preparing assets in advance and planning for the behaviour of known technologies.
1. Use the 5 Planes of UX design to work out what is needed from the perspective of the owner and users.
1. Being mindful of the discoveries in the design process, decide what languages and frameworks might be necessary to achieve the minimum viable product.
1. Create wireframes to outline the expected skeleton and structure of the website, and how things link together.  It is important during this process to think about how aspects of design will translate across multiple platforms.
1. When drawing up wireframes, bear in mind the capabilities of the technologies to be used and plan accordingly.  For example, if working with Bootstrap, design the mobile view first, then tablet, then PC as this is how each piece of code will be implemented.
1. Collate every asset in advance, as far as is practicable.  Images should be cropped square for responsive design, with disposable content around the edges. PC views will crop the top and/or bottom of an image, while mobile and probably tablet will crop the left and/or right.
1. Resize images for optimal web viewing, this can be done simply using Paint in Windows.
1. If any assets need to be made, work out what dimensions will be required and make them accordingly.  Trying to tweak or work with diagrams which are not the shape and size of the destination on the page is difficult.

### Build
1. Get the right information in the head.  Decide what Bootstrap version to use, what Font Awesome etc and include it from the start.
1. Establish meta elements like favicon and description in the header.
1. Include any scripts to be used at the foot of the body, in a commented section.
1. If using Bootstrap, take the time to really understand the structure.  For example, rows and columns not in containers seem to work at first glance, but actually do really strange things like overspill just ever so slightly off the edge of the page, or only have one margin (gutter) on the left, but not on the right meaning sections are not centred within their parent.
1. Build the nav first, and get it right before moving on.  A nav was built as the first item in this project but required a lot of tweaking as a result of not understanding how Bootstrap would affect it.  These changes then had to be copied across all pages each time.
1. Build the footer second, and get it right before moving on.  The same as the nav, this section was given a basic structure and not polished before starting other components.  Any changes then had to be replicated across all pages.
1. Once the basic structure to be used on all pages is complete, set up dummy files for all pages and establish links.  There were no missed links on the pages built this way, but there were on pages which were written before the other files existed.
1. Once complete examine code using Lighthouse and W3C HTML and CSS validators.
1. Deal with any issues.
1. Copy basic clean structure into dummy pages and update any active classes.
1. Build the home page sections, one at a time, in line with the wireframe.
1. Once complete examine code using Lighthouse and W3C HTML and CSS validators.
1. Deal with any issues.
1. Use the structure established in the home sections to help build the body of the other pages, one at a time.

### Testing
1. Validate HTML.
1. Validate CSS.
1. Validate accessibility/performance/SEO with Lighthouse.
1. Manually check that Bootstrap grid classes have the correct structure throughout the website.
1. Manually check that all links work as they should.
1. Check that all external links open in a new tab.
1. Manually check that all interactive elements work as they should (hover/active/focus etc).
1. Test any forms, ensure prompts display for incorrect completion.
1. Test submission of correctly completed forms for positive feedback.
1. Test any responsive elements like navs collapsing to hamburger behave as expected when displayed on different devices.
1. Check that componenets such as accordions do not truncate text or have overspill and return correctly to start position when required.
1. Check that any modals display correctly on all device types and that they can easily be dismissed.
1. Generally use website on multiple devices to be sure of appropriate display of images and sections.
