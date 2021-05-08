# Testing

## Table of contents 

- [HTML W3 Code Validator](#html-w3-code-validator) 
- [W3C CSS Validator](#w3c-css-validator)
- [WAVE](#wave)
- [Dev Tools](#google-chrome-developers-tools)
- [Responsiveness Testing](#responsiveness-testing)
- [Browser Compatibility](#browser-compatibility)
- [Testing User Stories](#testing-user-stories)
- [Further Testing](#further-testing)
- [Bugs](#bugs)


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
## Testing User Stories 

The initial scope of the project turned out to be a little ambitious so had to be scaled down. The most important aspects of the user experience which were identified have been met. Furthermore, the foundations have been laid to smoothly develop the site and meet the future user demands. 

-   #### Business Goals
    -  As the business owner, I want features and content that will engage new users quickly, encourage them to explore the site and draw them back in the future.
        - The home page has a lively and inviting feel to it. The hero image and text immediately pull the user in. The call to action invites them to explore further, using the well defined navigational elements.  

- As the business owner, I want to advertise the great aspects of our business which make us special.
    - Beer and music are highlighted immediately with the hero image and the alert banner. It is clear from the images and testimonials where the business strengths lie.
- As the business owner, I want to project a positive image and for users to feel that they can trust us.
    - The previous user testimonials plus Trip Advisor rating immediately make the user feel at ease.   
- As the business owner, I want to make a connection with users and enable us to contact and be contacted by them.
    - Site-wide call to action buttons, social media buttons and banners advertise how the user can make contact with the business. Users are lead to an informative contact page with various options on how they may make connect.

- As the business owner, I would like to be able to get customer user feedback to help identify where we are going right and where there is room for improvement.
    - There is a consistent message that the site cares about the user and wants their opinion. Users are encouraged to leave Trip Advisor reviews, go on social media sites and to submit a contact form on any subject. Users are also encouraged to subcribe to mailing list with the enticement of prizes.
- As the business owner, I want to provide users with useful information without overloading them.
    - The site is not overloaded with paragraphs of text but is fresh and lively. The home page sections provide important information, such as opening times, in a clear manner without getting lost among periphery material.   
- As the business owner, I want the site to be accessible to all users.
    - The site uses assistive technology, such as aria labelling and ```sr-only``` Bootstrap classes. Semantic ```html``` is used to further assist screen readers. 

 - #### User Goals (general)

- As a user, I want to be immediately drawn into the site and understand its main purpose.
    - The first experience of the site, with a hero image of live music in a rock bar, with dark colours, gothic font and 'beer and heavy metal' pushed forward make the site purpose very clear.
- As a user, I want to be able to easily identify what I need and navigate the site to get to it.
    - The navigation bar at the top of the page is clear and catches the eye straight away. There are no gimmicky words used here, just plain, simple and unambiguous. The navigation links make it clear which page the user is on and how they can get to other areas of interest. Icons and buttons assist the identification process.
- As a user, I want concise but informative content, displayed in an aesthetic manner.
    - Information is clearly laid out and to the point. Colours, rounded corners and a carefully thought through design layout make the site visually appealing and do not assault the senses.
- As a user, I want to be able to view the site clearly and intuitively on different device sizes.
    - The site is designed from a mobile user first perspective. Building on the Bootstrap design, device responsiveness is at the heart of the process. Content layout changes fluidly depending on the screen size so that the user experience should be the same, whether on a desktop or mobile device. 
- As a user, I expect the site to be fully accessible.
    - As per the business user story, accessible needs are always considered when building the site. From the choice of colours and contrasts to use to assisitive labelling, the design is made to be used by all. The positive WAVE and Lighthouse scores reflects this.

-   #### User Stories (customer users)

- As a new visitor, I want to be quickly reassured that this site will be of interest to me.
    - As mentioned previously, it is quickly apparent from the home page hero section what the site is about.
- As a new visitor, I want to be able to identify the content of the site and be able to easily navigate to areas of interest, such as the facilities and drink selection offered.
    - The navigation on the site is very clear. It is positioned predictably, along the top on a desktop/large tablet and collapsed in a hamburger icon on smaller devices. Future features, such as a drinks page, can be easily assimilated into the navigational layout as the site develops. Users are no more than two clicks away from a destination. There is also a floating 'scroll to top' arrow on larger devices to aid the navigation process.
- As a new visitor, I would like to know the experiences of previous customers to help evaluate whether it would be an experience that I would enjoy.
    - The testimonials section provides previous user feedback and helps to build trust in the user. The site owners are actively asking for user feedback, which provides further assurance. There is a testimonial navigation link in the main navigation bar to quickly direct users to the section.
- As a new visitor, I would like easily located social media links so I can see the pub's following, visitor comments and any uploaded media.
    - Social media links, with commonly identifiable and reactive icon links populate the site. The icons have been sized so as to be easy to see and use without being obtrusive. They are included in every page footer and on the hero section that first greets visitors to the site.   
- As a new or returning visitor, I would like to know opening times and contact information so that I can locate the pub and contact the owners if I require any further information. Many people prefer an easy to fill contact form rather than contacting by phone.
    - There is a dedicated 'hours section', which not only includes opening times but other times of interest, such as live event times. There is also a navigation link to take users directly to this popular information section. There is also a dedicated page to where the venue is located and a choice of email, telephone, social media or easy-to-fill contact form to get in touch with the pub.
- As a returning visitor, I would like to view the range and prices of food and drink on offer plus information on upcoming live music.
    - Up to date information is provided to users regarding the impact of COVID-19 by way of a striking red button on the navbar, which opens a modal informing the user of the current situation. Dedicated pages to drink and music, once restrictions are fully lifted, can be easily assimilated into the site and link with existing sections.
- As a frequent visitor, I would like to be kept informed of any new content, such as promotions or new live band dates. New content should be easily identified on the site plus I would like to sign up to be notified personally.
    - Call to action buttons prevail on the home page, inviting users to subscibe to the mailing list so they can be kept informed. The site top banner displays the latest announcements and the social media links are prevalent.
- As a frequent visitor, I would like to be able to share my experiences and connect with other users on the site.
    - Social media links plus Trip Advisor reviews and link enable this.
- As a frequent visitor, I would like there to be the option of accompanying music and videos, in line with the pub theme, to add to my user experience.
    - This is something which can be assimilated into the site in the future, now that the primary user needs have been addressed.

## Further Testing

-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

- Peer reviews by fellow Code Institute students, mentors and tutors helped to identify areas I may have overlooked.

-   A large amount of testing was done to ensure that all buttons and links have the desired function. 

All links to external sites should open in a new tab.

**Home Page**
| Location | Type | Expected Outcome | Pass/Fail|
-----|-----|-----|-------|
Alert bar | Text Link | Navigate to contact.html| Pass
Alert bar | Dismiss Button | Collapse Alert Bar | Pass
Navbar | Logo | Navigate to index.html| Pass
Navbar | COVID-19 Button Link | Open COVID-19 modal | Pass
Navbar | Close Button | Close COVID-19 modal | Pass
COVID-19 Modal | Contact Button link | Navigate to index.html | Pass
Navbar | Home Link | Navigate to index.html | Pass
Navbar | Hours Link | Navigate to index.html#hours | Pass
Navbar | Facilities Link | Navigate to index.html#facilities | Pass
Navbar | Testimonials Link | Navigate to index.html#testimonials | Pass
Navbar | Contact Link | Navigate to contact.html | Pass
Navbar | Subscribe Button | Navigate to contact.html#contact-us| Pass
Hero Text | Social Media Link | Open Facebook | Pass
Hero Text | Social Media Link | Open Instagram | Pass
Hero Text | Social Media Link | Open Twitter | Pass
Hero Text | Social Media Link | Open YouTube | Pass
Hero Text | Subscribe Button | Navigate to contact.html#contact-us| Pass
Facilities Section | Contact Button | Navigate to contact.html | Pass
Testimonials Section | Social Media Button & Text | Open Trip Advisor Page | Pass
Testimonials Section | Contact Button | Navigate to contact.html | Pass
Footer | Text Link | Navigate to index.html | Pass
Footer | Text Link | Navigate to index.html | Pass
Footer | Text Link | Navigate to index.html | Pass
Footer | Text Link | Navigate to contact.html | Pass
Footer | Email Link | Open New Email | Pass
Footer | Telephone Link | Open New Phone Call | Pass
Footer | Social Media Link | Open Facebook | Pass
Footer | Social Media Link | Open Instagram | Pass
Footer | Social Media Link | Open Twitter | Pass
Footer | Social Media Link | Open YouTube | Pass
Floating | Scroll To Top Button | Navigate to top of page | Pass


**Contact Page**
| Location | Type | Expected Outcome | Pass/Fail|
-----|-----|-----|-------|
Alert bar | Dismiss Button | Collapse Alert Bar | Pass
Navbar | Logo | Navigate to index.html| Pass
Navbar | COVID-19 Button Link | Open COVID-19 modal | Pass
Navbar | Close Button | Close COVID-19 modal | Pass
COVID-19 Modal | Contact Button link | Navigate to index.html | Pass
Navbar | Home Link | Navigate to index.html | Pass
Navbar | Hours Link | Navigate to index.html#hours | Pass
Navbar | Facilities Link | Navigate to index.html#facilities | Pass
Navbar | Testimonials Link | Navigate to index.html#testimonials | Pass
Navbar | Contact Link | Navigate to contact.html | Pass
Navbar | Subscribe Button | Navigate to contact.html#contact-us| Pass
Contact Body | Email Link | Open New Email | Pass
Contact Body | Telephone Link | Open New Phone Call | Pass
Contact Body | Social Media Link | Open Facebook | Pass
Contact Body | Social Media Link | Open Instagram | Pass
Contact Body | Social Media Link | Open Twitter | Pass
Contact Body| Social Media Link | Open YouTube | Pass
Contact Form | Input Name Required | Require Name | Pass
Contact Form | Input Name Required | Require Name | Pass
Contact Form | Input Email Required | Require Email Address Including '@' | Pass
Contact Form | Radio Button | One Selection Required | Pass
Contact Form | Send Button | Require All Fields; Open Sent Confirmation Page | Pass
Contact Form | Reset Button | Clear Contact Form Entries | Pass
Footer | Text Link | Navigate to index.html | Pass
Footer | Text Link | Navigate to index.html | Pass
Footer | Text Link | Navigate to index.html | Pass
Footer | Text Link | Navigate to contact.html | Pass
Footer | Email Link | Open New Email | Pass
Footer | Telephone Link | Open New Phone Call | Pass
Footer | Social Media Link | Open Facebook | Pass
Footer | Social Media Link | Open Instagram | Pass
Footer | Social Media Link | Open Twitter | Pass
Footer | Social Media Link | Open YouTube | Pass
Floating | Scroll To Top Button | Navigate to top of page | Pass

---
## Bugs
### Resolved Bugs

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
- After testing site responsiveness on various devices in Google Dev Tools, there was an issue with some smaller landscape device screens. There was a slight overflow of the hero paragraph text into the following section on a few landscape views (generally wider with relatively little height). I tried many media queries to change container heights. Increasing the hero container height on landscape viewports within the problem width parameters did help but caused another issue. In some cases, it would push the 'Hours' section beneath the 'Facilities' section. I decided to think along another line and removed the paragraph text from all landscape views under 992px. The CTA 'Subscribe' button linking to the contact form remained, which is the most important part - particularly on mobile devices as the CTA button is not displayed on the navbar. Although this provided a satisfactory solution, I would like to explore a way to keep the text on landscape devices without overflowing.
 

   