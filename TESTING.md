# Curls

## Testing
---

### Validation Testing
The project code has been passed through the following code validators:
* [HTML Code Validator](https://validator.w3.org/)
* [CSS Code Validator](https://jigsaw.w3.org/css-validator/)

### Client Stories Testing
1. As a new user, I want to quickly determine if the website contains information I need, so that I know quickly whether to stay on the page.
    1. The navigation bar is shown on every page with descriptive headings.
    2. Both the logo and Home links will take the user to the homepage with summaries of each section.
2. As a new user, I want to easily determine and navigate to a point on the website which is appropriate for my existing knowledge, so that I do not waste time.
    1. The navigation bar is shown on every page with descriptive headings.
    2. Both the logo and Home links will take the user to the homepage with summaries of each section.
3. As a new user, I want to learn about basic techniques that I can use right away, so that I can start putting research into action.
    1. The website is structured such that the user works through the pages Home > Science > Types > Actions.
4. As a returning user, I want to determine my hair type and porosity, so that I can tailor the techniques I learned before.
    1. The user can navigate to the Types page directly from any page on the website.
5. As a returning user, I want to be able to easily contact the site owners with questions, so that I can obtain tailored information or troubleshoot issues.
    1. There is a Contact page link in the header, and a Contact modal in the footer of every page.
6. As a frequent user, I want to be able to navigate quickly and easily to the relevant part of the website which contains the information I need, so that I can quickly fulfil the reason for my visit.
    1. All sections of the website are clearly linked to from the Navigation bar which is present on every page.

## Manual Testing

------------------------------TO DO----------------------------------- <br>
Home Page:
Navigation bar:

Go to the "Home" page from a desktop.
Change the screen size from desktop to tablet to verify that the navigation bar is responsive and switches from in line menu to burger icon dropdown menu at the appropriate place.
When checking responsiveness of navbar, verify that there is no overflow causing ugly size changes to menu items. During testing there were overflow problems here. This was fixed by reducing size of the button and logo margins
Hover over the logo in the navigation bar and verify that the alt text appears. During testing this did not happen, so I added a title attribute to the logo to fix
Click on the logo in the navigation bar and verify that it links to the home page.
Click on each navigation menu item and verify that it links to the correct page.
Hover over the "request quote" button and verify the hover colour change works as expected.
Click on the "request quote" button and verify that it links to the contact page.
Change screen size to small and click burger icon, verify that the menu drops down and that the menu text is centred.
Repeat verification of functionality and responsiveness on my mobile phone and tablet.
Hero image / video:

Go to "Home" page from a desktop.
Confirm video is visible, autoplays on mute and is 100% width of the screen.
Reduce the width of the window to confirm that the video switches to static image in mobile.
Reduce and expand width of window to confirm that the overlay on top of image / video responds correctly and does not obscure important features.
Compelling copy section:

Reduce and expand width of window to confirm that the text in this section responds correctly and looks good on all device widths.
Testimonials:

Reduce and expand width of window to confirm that 3 testimonials display on medium to large screens, but one is hidden on mobile devices.
Call to action button:

Hover over call to action button and verify the hover colour change.
Click the call to action button and verify that it links to the correct page.
Footer:

Hover over each social media icon and confirm colour and size transitions expected.
Click on each icon to confirm it opens a separate tab for it's link.
Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths.
Review all functionality and responsiveness on my mobile phone and tablet.

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.
