# Testing

## [HTML W3 Code Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
All pages were tested for validation to ensure there were no HTML syntax errors in the project.

[One error](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/html-val-2.JPG) was returned. This stated that a % should not be used to set the width of an iframe. This actually gave me the best result, particularly when it came to responsiveness. However, I changed the width to a set number as requested.
Both the [home](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/html-val-1.JPG) and [contact](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/html-val-3.JPG) pages now show no errors.

---
## [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
All pages were tested for validation to ensure there were no CSS syntax errors in the project.

The [test results](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/css-valid.JPG) only highlighted two errors from the Bootstrap library so the project syntax is good.

---
## [WAVE](https://wave.webaim.org/)
The Web Accessibility Evaluation Tool was used to check the accessibility standards of the site. 

The site scored very well, with the [home page](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/wave-1.JPG) scoring 0 errors and contrast errors. 

The [contact page](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/wave-2.JPG) initially scored 4 errors, relating to labelling of form fields. Three of these had ```sr-only``` classes added. However, the 'last name' field moved out of position when the ```sr-only``` class was added so that one error alone remains.

---
## [Google Chrome Developers Tools](https://developer.chrome.com/docs/devtools/)
- Google Dev Tools was used extensively during project development to help identify and solve any syntax issues.
- The Dev Tools [Lighthouse tool](https://developers.google.com/web/tools/lighthouse) is useful to check the performance quality of the site.
    - **Desktop** The desktop performance comes up with a high performance score of 98%. Accessibility is 98%, Best Practices 100% and SEO 100%. See [link](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/lighthouse-1.pdf) for a copy of the report.
    - **Mobile** The mobile performance originally came in at 78%, prinicipally due to the image sizes, although they had been compressed. Images were compressed further and the score is now 83%. Other scores remain high, with Accessibilty 99%, Best Practices 100% and SEO 100%. See [link](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/lighthouse-2.pdf) for a copy of the report.
- Responsiveness of different screen sizes was continually checked during the development process to ensure that the site rendered as well as possible of differing screen sizes and orientations. Although helpful, this is not foolproof so further responsiveness testing was required.

---
## Responsiveness Testing
-   [Responsinator](https://www.responsinator.com/) was used to test the completed project on different devices. This highlighted some issues which were not apparent on Google Dev Tools, mostly involving landscape viewports. These were addressed and all devices are rendering well - please see [link](https://www.responsinator.com/?url=https%3A%2F%2Fstevekennyuk.github.io%2Fthe-anvil-metal-pub%2Findex.html) for results.
- In addition to automated tests, using real devices is desirable. Thanks to friends and family, I was able to test the site on various devices, including Samsung Galaxy S8, Samsung Galaxy S9, various iPhones, iPads, Samsung Galaxy Tabs, Asus Zenbook and Lenovo ThinkPad. Results were very positive. The only issue was with a narrow and long screen on a Galaxy Tab, where some elements were almost overlapping. Having already spent a long time using media queries to try to resolve landscape issues on smaller devices, I feel that this would be best looked at in the future. There could be a lot of rewriting to try to accommodate an extremely small number of devices. Although ideally all devices should be accommodated, this may not always be an efficient use of resources.

---
## Browser Compatibility

The site was tested on a ASUS Zenbook desktop, Samsung Galaxy mobile and iPhone 11 using various browsers.
- **Chrome** The site was developed using Chrome so works well. See [desktop screenshot](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/chrome-desktop.JPG). Mobile view was good in portrait and landscape.
- **Mozilla Firefox** [Desktop](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/mozilla-desktop.JPG) and mobile views were good.
- **Edge** [Desktop](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/edge-desktop.JPG) and mobile views were good.
- **Opera** [Desktop](https://github.com/SteveKennyUK/the-anvil-metal-pub/blob/master/assets/images/testing/opera-desktop.JPG) and mobile views were good.

---
### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the organisation.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Text and a "Learn More" Call to action button.
        2. The main points are made immediately with the hero image
        3. The user has two options, click the call to action buttons or scroll down, both of which will lead to the same place, to learn more about the organisation.

    2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.
        2. At the bottom of the first 3 pages there is a redirection call to action to ensure the user always has somewhere to go and doesn't feel trapped as they get to the bottom of the page.
        3. On the Contact Us Page, after a form response is submitted, the page refreshes and the user is brought to the top of the page where the navigation bar is.

    3. As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their following on social media to determine how trusted and known they are.
        1. Once the new visitor has read the About Us and What We Do text, they will notice the Why We are Loved So Much section.
        2. The user can also scroll to the bottom of any page on the site to locate social media links in the footer.
        3. At the bottom of the Contact Us page, the user is told underneath the form, that alternatively they can contact the organisation on social media which highlights the links to them.

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to find the new programming challenges or hackathons.

        1. These are clearly shown in the banner message.
        2. They will be directed to a page with another hero image and call to action.

    2. As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.

        1. The navigation bar clearly highlights the "Contact Us" Page.
        2. Here they can fill out the form on the page or are told that alternatively they can message the organisation on social media.
        3. The footer contains links to the organisations Facebook, Twitter and Instagram page as well as the organization's email.
        4. Whichever link they click, it will be open up in a new tab to ensure the user can easily get back to the website.
        5. The email button is set up to automatically open up your email app and autofill there email address in the "To" section.

    3. As a Returning Visitor, I want to find the Facebook Group link so that I can join and interact with others in the community.
        1. The Facebook Page can be found at the footer of every page and will open a new tab for the user and more information can be found on the Facebook page.
        2. Alternatively, the user can scroll to the bottom of the Home page to find the Facebook Group redirect card and can easily join by clicking the "Join Now!" button which like any external link, will open in a new tab to ensure they can get back to the website easily.
        3. If the user is on the "Our Favourites" page they will also be greeted with a call to action button to invite the user to the Facebook group. The user is incentivized as they are told there is a weekly favourite product posted in the group.

-   #### Frequent User Goals

    1. As a Frequent User, I want to check to see if there are any newly added challenges or hackathons.

        1. The user would already be comfortable with the website layout and can easily click the banner message.

    2. As a Frequent User, I want to check to see if there are any new blog posts.

        1. The user would already be comfortable with the website layout and can easily click the blog link

    3. As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.
        1. At the bottom of every page their is a footer which content is consistent throughout all pages.
        2. To the right hand side of the footer the user can see "Subscribe to our Newsletter" and are prompted to Enter their email address.
        3. There is a "Submit" button to the right hand side of the input field which is located close to the field and can easily be distinguished.

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Resolved Bugs
---

-   After repositioning and resizing the navbar elements, then setting ```class="d-none d-md-block"```, the CTA button on the right hand side of the navbar would not display on tablet devices. 
    
    - I played around with the d-class to see if that would make a difference but the issue was still there if the class was removed entirely. This suggested that the bug may be related to the stylings I had added. 
    - Some research on [Stack Overflow](https://stackoverflow.com/questions/26674303/bootstrap-navbar-not-displaying-correctly-on-tablet) suggested that indeed the measurements used to style the navbar may be the issue. Changing the navbar margins and font size confirmed this theory. Removing the margin and reducing the font size displayed the CTA on tablet devices.
    - However, I did not like what this did to the desktop screen displays. There was an option to remove the CTA from tablets or replace the menu with a toggler, as with mobile devices. I felt that there was room for the menu names and the CTA button on the tablets and it looked better so I set media queries for the tablet sizes to reduce the margin and font size. I then set a media query to increase margin and font size for 4K devices so that the nav items displayed as desired on all device sizes.
    
    **UPDATE** - following the decision to abandon the fixed-top navigation bar (see [Unresolved Bugs](#unresolved-bugs)), I felt that there was no need for a 'Subscribe' button on the navbar as there is one on the hero image text, which would be visible on the home page upon entering the site. The initial idea was for the button to always be visible to the user, as part of the fixed navbar. The introduction of a 'COVID-19' information modal button to the navbar would be more useful to the user.
-  I wanted to arrange the footer bar so that the social media icons would display first in mobile view then move to the right on larger screen sizes. I added ```d-flex``` and ```flex-row-reverse``` to enable this. 
    - The first issue was the columns bunching up on the right rather than spread evenly across the footer. I tried various justify positioning techniques before finally realising it was a fairly simple fix. I had placed each column in one row, rather than placing them in a different row within the container.
    - There was then a second issue. Every word or icon within the columns was displaying in a narrow column rather than flowing horizontally. Dev Tools indicated that I had created flexboxes within flexboxes (with Bootstrap being built on flex) so I removed some flex code I had written and the issue was resolved.
- On mobile view, the hero image was overflowing onto the sections below. I decided to hide the overflow so that users could scroll to reveal the bottom of the hero image. This created scroll bars so, following advice from [W3Schools](flex-row-reverse), I added ```overflow-x: hidden;``` which removed the scrollbars. I then had an issue where, in Dev Tools responsive testing, the y-scroll bar would periodically appear then disappear. I added ```overflow-y: hidden;``` but this disabled the image from scrolling altogether. I had not wanted the hero image to be too long on the mobile device screens so the user would not need to scroll too much to get to lower content. However, I increased the image height to 120vh on mobile screens to remove any scrolling issues and believe that this is actually a better option for the user than having some of the image hidden.  
- After deploying the site to check if it was displaying in the same way as the Gitpod browser, there was a major issue. Only one of the images was showing correctly. The rest were displaying the ```alt``` description. I checked on Slack and this was an issue faced previously and fortunately the experience of fellow students pointed me in the right direction, which was the file path. Although ```/assets/...```would display the image on Gitpod, I needed to remove the initial / for the image to display on the deployed site.      
### Unresolved Bugs
---
- When using the Bootstrap ```.fixed-top``` class to make the navbar fixed, the navbar would then cover the container below and the alert bar above. I resolved the container overlay by adding some margin to the top of the container. Adding margin to the bottom of the alert bar did not work so I added margin at the top of the navbar. This did reveal the alert bar but when scrolling, the alert bar would also scroll up. I needed to find another way to make the alert bar visible and stick in position. Using ```position-fixed``` and a z-index above the navbar z-index set in Bootstrap seemed to work. However, if the alert bar was dismissed, a blank space was left rather than the navbar moving up to replace it. I decided to leave the navbar without fixed positioning as links to other pages would be included in sections further down the page.
- On the 'Testimonials' page, I wanted to place the introductory text in the middle of the testimonial images and text on tablet devices upwards. This was accomplished for laptop screens, using ```order``` and ```margin``` to move the introductory section in place. However, on the laptop size screens, the left-hand images overlapped the introductory text. I tried to target the cards, which were used to create the testimonials. No matter what I tried, including using IDs, I could not change the card sizes or move them. Even when I tested targetting ```.card```, the stylings would affect the cards in other sections but not the ones I was trying to target. I could not resolve why these cards would not be targetted so eventually decided to place the introductory text at the top of the section and have rows of two testimonials beneath for tablet sizes.
- After testing site responsiveness on various devices in Google Dev Tools, there was an issue with some smaller landscape device screens. There was a slight overflow of the hero paragraph text into the following section on a few landscape views (generally wider with relatively little height). I tried many media queries to change container heights. Increasing the hero container height on landscape viewports within the problem width parameters did help but caused another issue. In some cases, it would push the 'Hours' section beneath the 'Facilities' section. I decided to think along another line and removed the paragraph text from all landscape views. The CTA 'Subscribe' button linking to the contact form remained, which is the most important part - particularly on mobile devices as the CTA button is not displayed on the navbar. Although this provided a satisfactory solution, I would like to explore a way to keep the text on landscape devices without overflowing.
 

   