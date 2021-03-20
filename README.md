# **Curls**

## **Overview**

An easily accessible basic resource for people looking for information about haircare methods specific to curly hair. Changes in fashion and greater acceptance of individuality mean more people are able to wear naturally curly hair in a professional environment as well as in other situations in which it would have previously been considered inappropriate.

Decades of straightening, blow-drying and otherwise taming or conatining curls have meant that information about curly haircare is thin on the ground, and what there is is very spread out.  This website aims to pull together all of the basic information a curly converter might need to get started, and then provide them with links for further reading should they need or want it.

![Am I Responsive Image](assets/images/am-i-responsive.png)

# Index
1. [UX](#ux)
    * [User Stories](#user-stories)
    * [Strategy](#strategy)
    * [Scope](#scope)
    * [Structure](#structure)
    * [Skeleton](#skeleton)
    * [Surface](#surface)
1. [Features](#features)
    * [Existing Features](#existing-features)
      * [Home](#home)
      * [Science](#science)
      * [Types](#types)
      * [Actions](#actions)
      * [More Info](#more-info)
      * [Contact](#contact)
    * [Features for Future Implementation](#features-for-future-implementation)
1. [Testing](#testing)
1. [Technologies Used](#technologies-used)
1. [Deployment](#deployment)
    * [Via GitPod](#deployment-of-the-page)
    * [Cloning Locally](#how-to-run-the-code-locally)
1. [Credits](#credits)
    * [Website](#website-credits)
    * [README](#readme-credits)

## UX

Adopters of curly specific haircare do tend to be female and younger, however this is rapidly changing as male grooming becomes more mainstream, and personal freedoms become more acceptable for all generations.  The users of this website therefore could be anybody, regardless of age or gender and the design is approached accordingly.
*  Bright unisex colours are offset by classic, largely white sections and black/white text and details.
*  Soft scrolling fonts are contrasted with sharp, angled corners and straight lines.
*  Imagery is fairly inclusive, although it was not possible to find suitable pictures of older people with spectacular natural curly hair.

### **User Stories**
1. As a new user, I want to quickly determine if the website contains information I need, so that I know quickly whether to stay on the page.
1. As a new user, I want to easily determine and navigate to a point on the website which is appropriate for my existing knowledge, so that I do not waste time.
1. As a new user, I want to learn about basic techniques that I can use right away, so that I can start putting research into action.
1. As a returning user, I want to determine my hair type and porosity, so that I can tailor the techniques I learned before.
1. As a returning user, I want to be able to easily contact the site owners with questions, so that I can obtain tailored information or troubleshoot issues.
1. As a frequent user, I want to be able to navigate quickly and easily to the relevant part of the website which contains the information I need, so that I can quickly fulfil the reason for my visit.

### **Strategy**
This website is for individuals looking for information to help them decide whether curly haircare is for them, and if it is, identify the characteristics of their hair and what their first steps might be.

The Curls website satisfies these objectives by first presenting a summary of the information contained within the various sections of the website, before expanding on each summary with clear progression to a dedicated page. As the user works through the pages they will gain an understanding of their hair and how it is affected by products and practices before arriving at links to further learning.

Owner aims:
* Inspired/informed user
* Increase awareness of curly haircare
* Provide basic information on such
* Grow the curly haircare community
* Potential for commissions or sponsored links in the future

User aims:
* Get better curls
* Increase knowledge
* Easily progress through basic details to more in depth information as understanding improves
* Identify hair type and porosity
* Learn where to find information specific to indentified hair type

### **Scope**
The project is born of the designers own experience trying to find information on how to get defined, glossy curls.  There was lots and lots of information but all scattered about, and nothing aimed directly at a beginner.

The scope of the project therefore is to provide condensed, basic information which can give the user the tools they need to get started.

#### Feature Viability

#|Feature | Importance | Viability | Comment 
---|------------ | -------------|--------------|-----------|
1.| Identify curl type  | 5 | 5 | Y - Important for care routine
2.| Identify porosity | 5 | 5 | Y - Important for care routine
3.| Identify hair type | 2 | 4 | N - Advanced concept, research needed
4.| Table porosity/curl type do's and dont's | 4 | 2 | N - Too big to easily make responsive
5.| Hair type needs and routines | 5 | 3 | N - Bulky text heavy sections
6.| Links to further reading | 3 | 5 | Y - Assist with research beyond current scope of website
7.| Indicative starter products by type/porosity | 4 | 1 | N - Products change regularly, research needed
T.| Total score | 28 | 25 |

#### Feature Plan
First increment:
* Identify type & porosity
* Understand type & porosity
* Understand actions to take (creep risk)
* Links to further research

Second increment:
* Add type routines
* Add product information

Third increment:
* Add type/porosity table

### **Structure**
* See Information Grouping [mind map here](assets/documents/structure.pdf).

### **Skeleton**
In line with structure planning, a clear and concise homepage is designed in line with standard expectations, linking immediately to all parts of the site.  Each page also allows logical progression to effectively build knowledge.

Each page broken down into small sections for easy digest of information.

Very basic 404 redirect page with a link to home to prevent stuck users.

#### Wireframes

##### Original
1. [Mobile](assets/documents/curls-mobile.pdf) 375px
1. [Tablet](assets/documents/curls-tablet.pdf) 768px
1. [PC/Laptop](assets/documents/curls-pc.pdf) 1200px

##### Final
1.  [Mobile](assets/documents/) 375px
1.  [Tablet](assets/documents/) 768px
1.  [PC/Laptop](assets/documents/curls-pc.pdf) 1200px

##### Summary of Changes
The most notable change between the original wireframes and the final version is the footer.  The original design felt very disconnected to the flow of the page, and almost unfinished when viewed in its final environment.  Other top-level changes are the exchange of in-line text links for bolder, more obvious call to action buttons, the use of collapsed nav in hamburger button format on tablet and the elimination of underlines, horizontal and vertical rules.

*  The four panel structure of the footer was revised, in particular eliminating the contact section.  This had contained a telephone number and email address and a link to a contact form modal.  No address was included as it is not relevant to the content.  The phone number and email address were vulnerable to misuse, either by bots or malicious users and the Contact Us page was so readily accessible that the modal was deemed surplus to requirements.  It was also felt that the modal dod not fit well with the overall feel of the site.
*  The links to the next pages were somewhat lost in the volume of content on each page, particularly the homepage which has snippets of information about each following segment.  As such, these were changed to bolder, clearer buttons which focus the user per the intent of the designer, which is to move onto the next learning section.
*  The navigation bar link items proved to be too large for the tablet view when spacing between elements was optimised.  As such, the decision was made to collapse to a hamburger menu at tablet, rather than make the lements fit and appear squashed.
*  All pages have a lot of content, in line with the nature of the website.  The inclusion of decorative elements cluttered the pages and made for an uncomfortable viewing experience.
*  Source data links have been acknowledged in the README, the majority of content is knowledge held by the creator, verified by the external sources.  The links made the pages very bitty and unattractive.

###### Changes Specific to Home Page
*  Section 2 was very busy, so the background image was eliminated and the content condensed into a smaller number of sections.
*  Section 4 was very spaced out and clunky.  The arrangement made it appear dated.  This was tweaked slightly to make use of Bootstrap cards to present the information in a more contained manner.
*  Added a Get Started section, as user was otherwise left at the end of the page with a link only to the last section.

###### Changes Specific to Science Page
*  None.

###### Changes Specific to Types Page
*  Section 1 did not follow a logical reading order of left to right and then down, and was amended as such.

###### Changes Specfic to Actions Page
*  Section 2 contains a vast amount of content which was overwhelming, particularly on tablet and mobile.  A Bootstrap Accordion component was used to separate the text into digestible segments.  A video was embedded here to help further break up the textual content.

###### Changes Specific to More Page
*  None.

###### Changes Specific to Contact Page
*  Remove Fieldset and Legend from form, page appeared cluttered and bitty as the appearance was very different to the other sections thorugh out the webpage.

### **Surface**

#### Colours
Haircare and beauty in general can be perceived as a feminine area of interest, when in reality it is simple self-care.  A selection of bright colours across the spectrum were chosen to give an androgynous feel, a nod to LGBTQA users and complement a plain white background.  The very simplistic design is to allow the information to speak for itself as this is the main purpose of the website, and to keep the data easily digestible by the user.
![Colours option 1](assets/images/colors-opt-1.png)

Once put to use, it became apparent that the boldness of the chosen colours did not work well for large block sections on the web pages.  This slightly more muted palette was chosen to make using the site more comfortable but still keep a quirky, friendly feel.
![Colours option 2](assets/images/colors-actual.png)

#### Typography
Three fonts are chosen for the website, all via Google Fonts.
1. A fun and whimsical cursive font for the logo: "Sunshiney"
2. A similar but easier to read cursive font for headings through the page, and for navigation links: "Delius Swash Caps"
3. Finally, a simple sans-serif font for the body to facilitate easy reading.  Sans-serif fonts render well on lower resulution screens, and are generally considered more readable by those affected by dyslexia or similar reading difficulties: "Quicksand"

![Example fonts](assets/images/typography.png)

## Features

### **Existing Features**
Uniform design across all pages in line with conventional practice.  This incorporates:
* A sticky navigation bar which collapses to hamburger menu on mobile and tablet, with the Logo on the left and a stand-out Contact item on the right.  This allows quick and easy navigation of the website.
* A footer which provides a mission statement and design information, and social media links.  This provides a certain and familiar endpoint to every page.
* Consistent, defined design across information delivery sections of the website.  This allows intuitive use of the website through familiarity.
* Every page starts with a hero image, to elicit a positive emotional response.
* The website is designed to be bright and clean with the focus on the information itself.  This allows the user to fulfil their purpose of obtaining knowledge without distraction.
* Androgynous design is deliberately chosen as the content is traditionally seen as feminine.  This helps users who identify as other than female to feel comfortable using the site.
* Colours for each page are tied to the colour of the related navigation bar component to assist with centering.
* Every page has at least one internal link near the bottom of the page to avoid users becoming "trapped", and to encourage them on their journey through the website.
* The Contact Us part of the navigation bar is displayed proudly on the right of the page.  This allows the user to easily access help or tailored information from anywhere on the site.

#### Home
The page features a relevant full screen hero image to provide positive emotional response and visual validation that the user is in a location which meets their needs.

The page then contains very short snapshots of all of the information contained in following pages.  These sections are clearly structured to relate directly to the links in the navigation bar and coloured accordingly.  This serves multiple purposes:
1. It allows the user to quickly determine if the website contains the information they are looking for.
2. It allows the user to quickly identify which part of the website contains the information that they are looking for, and a means to navigate to it easily.

#### Science
The page also opens with a relevant hero image, though this is not quite full screen to allow "peeping" to encourage the user to scroll to the information below.

Information is presented in short, defined sections to prevent user fatigue and these are structured consistently with the sections on the home page to provide a familiar, comfortable experience.

Diagrams are used to provide a visual representation of the data provided and help facilitate understanding.

The bottom of the article contains a link to the next page in the logical progression of the website.

#### Types
This page mirrors the Science page in layout to provide a secure, intuitive experience for the user.  Sections are once again defined in short digestible chunks and supported by visual aids.  The page again, ends with a link to the next page in the sequence.

#### Actions
As with the Science and Types pages, design remains focussed on provision of information in small defined sections.  Icons and Bootstrap accordion components are used to provide graphic relief from large bodies of text and introduce splashes of colour.  These are used in place of the diagrams shown in previous sections which do not apply here and helps to keep the consistency of design by maintaining the presence of small images amongst the body.  Embedded video provides further relief from a particularly text-heavy page.  A link encourages the user to the next page just before the footer.

#### More Info
Still following the design of the previous pages, clear and defined information sections are provided, here also relieved by the use of icons to break up the text content.  A link to the Contact Us page encourages the user to engage further.

This is where the content of the website ends.  In line with the purpose of the owner to grow the community, links to external resources which provide further, more specific information are provided here with descriptions of what can be found at each.

#### Contact
A large image is shown at the top of the page to provide continuity with the rest of the website.  A contact form is provided to encourage users to engage with the community, which will help with retention rates.

### **Features for Future Implementation**
1. Connect contact form to email | Requires Javascript.
2. Add pages for type specific care, to be accessed via a hair type sorter | Time constraints and technical knowledge both prevent this item from progressing at this time.
3. Add pages for type specific haircare products, possibly with sponsored links | Time constraints prevent addition of more in-depth pages at this time.  Lack of industry contacts prevent the addition of sponsored links.

## Testing

This information is held in the file [TESTING.md](TESTING.md)

## Technologies Used

* HTML5 is used to provide the basic structure of the website.
  * About: [HTML5 Wiki](https://en.wikipedia.org/wiki/HTML5)
  * Creator: [W3 Consortium](https://www.w3.org/)
* CSS3 is used to provide most of the styling for the website.
  * About: [CSS3 Wiki](https://en.wikipedia.org/wiki/CSS)
  * Creator: [W3 Consortium](https://www.w3.org/)
* Bootstrap5 is used to provide the grid functionality for uniform design, responsiveness and to enable the use of modal and hamburger menu.
  * About: [Bootstrap Home](https://getbootstrap.com/)
  * Creator: [Bootstrap History](https://getbootstrap.com/docs/5.0/about/overview/)
* Google Fonts are used to provide the typography for the website.
  * Link: [Google Fonts](https://fonts.google.com/)
* Font Awesome is used to provide the icons for the website. (Version 4.7 is used to avoid the need to create "collections" which can be overwritten and therefore pose a risk to the site).
  * Link: [Font Awesome - V4.7](https://fontawesome.com/v4.7.0/get-started/)

## Deployment

The website was created using [GitPod](https://www.gitpod.io/). Version control was undertaken by committing to [Git](https://git-scm.com/) and pushing to [GitHub](https://github.com/) using the functions within GitPod.

### **Deployment of the Page**
1. In GitPod, ensure the tree is clean, and all required items have been committed and pushed to the repository in GitHub.
2. Sign in to GitHub.
3. A list of repositories should display on the left of the page. Choose the appropriate repository: lilblupig/curls-ms1
4. From the repository menu, choose Settings.
![GitHub menu snip](assets/images/deploy-1.png)
5. Scroll down the page to find the Pages section.
6. From the first dropdown box, choose the Master branch, then click save.
![GitHub Pages snip](assets/images/deploy-2.png)
7. The page will refresh, and the Pages section now shows a URL for the deployed site.
8. Click the URL to view the deployed website.

### **How to Run the Code Locally**
There are slightly different approaches should you choose to use GitPod to clone the project, or a local IDE.

#### Cloning a Project into GitPod
1. Use [Google Chrome](https://www.google.com/intl/en_uk/chrome/). *(This can also be undertaken in Firefox)*
2. If you do not already have one, [create a GitHub account](https://github.com/join).
3. Install the [GitPod browser extension for Chrome](https://chrome.google.com/webstore/detail/gitpod-dev-environments-i/dodmmooeoklaejobgleioelladacbeki).
4. Restart Chrome.
5. In GitHub, find the [project repository](https://github.com/lilblupig/curls-ms1).
6. From the repository menu, choose the green GitPod button.
![GitPod button snip](assets/images/deploy-3.png)
7. A new GitPod workspace will open containing the project code.

#### Cloning a Project into a Local IDE
1. Navigate to the [GitHub Repository](https://github.com/lilblupig/curls-ms1).
2. Choose the Code dropdown menu, and copy the URL.
![GitHub code download snip](assets/images/deploy-4.png)
3. Open your local IDE and then open a terminal.
4. Set the current working directory to your preferred location for the cloned project.
5. Type in "git clone " followed by the copied URL. Be sure to include a space between git clone and the url, then press enter.
6. The cloned project will be created.

You can find more information on cloning a repository from GitHub [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

## Credits

### **Website Credits**

#### Content
The content used for the website is drawn directly from the knowledge of the creator.  This was checked to a number of sources to verify that it is still correct and current, which are shown below:
* Science Page - Section 1 - [Lush Cosmetics](https://uk.lush.com/article/understanding-hair-structure)
* Science Page - Section 2 - [Helix](https://helix.northwestern.edu/blog/2014/05/science-curls)
* Types Page - Section 1 - [Allure](https://www.allure.com/gallery/curl-hair-type-guide/amp)
* Types Page - Section 2 - [L'Oreal](https://www.lorealparisusa.com/beauty-magazine/hair-care/damaged-hair/hair-porosity.aspx)

#### Media
* The photographs used for the website were obtained from [Pexels.com](https://www.pexels.com/):
    * Home Hero - [Keira Burton](https://www.pexels.com/photo/multiracial-positive-male-and-female-students-using-smartphones-in-city-park-6146931/)
    * Types Hero - Composite image collated by creator from [Nataliya Vaitkevich](https://www.pexels.com/photo/photo-of-woman-looking-serious-4450401/), [Владимир Васильев](https://www.pexels.com/photo/woman-in-light-white-dress-in-forest-5003435/) and [Gift Habeshaw](https://www.pexels.com/photo/young-black-man-with-curly-hair-against-neon-cross-3905285/)
    * Actions Hero - [cottonbro](https://www.pexels.com/photo/woman-in-bathtub-with-water-4155482/)
    * More Hero - [cottonbro](https://www.pexels.com/photo/man-people-woman-coffee-5529908/)
    * Contact Hero - [Christina Morillo](https://www.pexels.com/photo/photography-of-woman-using-laptop-1181742/)

* The diagrams used for the website were obtained from various places:
    * Science Hero - [By CSIRO](https://commons.wikimedia.org/w/index.php?curid=35489670), [Creative Commons licence](https://creativecommons.org/licenses/by/3.0), changes: Crop to include only human hair, remove merino wool fibre
    * Science Hair Structure Diagram - made by creator in Paint3D for this project
    * Science Hair Follicle Diagram - [By HairFollicle](https://commons.wikimedia.org/w/index.php?curid=6910143), Creative Commons Licence
    * Types Hair Typing Diagrams x 4 - made by creator in Google Keep notes 

* The embedded video used in the Actions page is from YouTube:
    * [Manes By Mell](https://www.youtube.com/watch?v=Fk-pLSxYPh8&t=1s)

* The hamburger SVG was obtained from the website [Icons8](https://icons8.com/icons/set/hamburger)

#### Acknowledgements
* This project was created using the following resources:
  * [Code Institute Full Template](https://github.com/Code-Institute-Org/gitpod-full-template)
  * [DailyMotion Aspect Preservation](https://faq.dailymotion.com/hc/en-us/articles/360022841393-How-to-preserve-the-player-aspect-ratio-on-a-responsive-page)
  * [101 Computing Favicons](https://www.101computing.net/html-how-to-add-a-favicon/)

### **README Credits**

#### Content
* Structure and content based heavily on:
  * [Code Institute Solutions - README Template](https://github.com/Code-Institute-Solutions/readme-template)
  * [Anna Greaves - Portrait Artist README](https://github.com/AJGreaves/portrait-artist/blob/master/README.md)
  * [Karina Finnegan - Tunnel Focus README](https://github.com/kairosity/mp2-tunnel-focus/blob/master/README.md)
  * [Anna Greaves - Portrait Artist TESTING](https://github.com/AJGreaves/portrait-artist/blob/master/TESTING.md)
  * [Daisy McGirr - Code Institute Testing Webinar](https://us02web.zoom.us/rec/play/9FIKllHX2ZiQNFRhYPn_hBh_ZeA8964ZvIDLnhpKGAf1NLVc3_hBJ6zSL8Hv5Hx7ALnPtDmbg8CmFAs.YVsZ9LR_uI7OjEwH)

#### Media
* The images for this README are from the following sources:
  * Snips taken from GitHub.
  * [Am I Responsive](http://ami.responsivedesign.is/).
  * Wireframes created with [Balsamiq](https://balsamiq.com/).
  * Colour mockups created with [Coolors](https://coolors.co/).

#### Acknowledegments
  * Markdown basic taken from [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).