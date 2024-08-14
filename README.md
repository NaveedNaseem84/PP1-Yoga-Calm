# Yoga Calm 
Yoga calm is a website aiming to provide tailored yoga information to individuals working remotely. The purpose is to provide everything in one place without the need to navigate externally, and acts as a reference guide for time in between meetings or at the end of the day to stretch your back or wind down and relax.

## Landing page (index.html)
The landing page highlights the benefits of yoga and promotes the benefits of using the yoga calm website with an invitation to win a free yoga mat.

![Yoga calm shown on different devices](readme-images/Responsive-on-all-devices.png)

_**Image above generated using https://ui.dev/amiresponsive illustrating the responsiveness of the site.**_

An inspirational quote by a yoga user is also displayed towards the bottom of the landing page:

![Quote on landing page](readme-images/quote.png)

### Features
#### Navigation
* The top of the page features a navigation bar displaying the Yoga Calm logo to the left and the website links to the right.
* Clicking the Yoga Calm logo will always take the user back to the home page.
* Start Yoga and Win! Links: these take the user to respected pages.
* The navigation menu is available throughout the site and is styled reflecting which page the user is currently on – red, underlined.

![The navigation menu](readme-images/navigation-menu.png)

#### Menu Toggle
* Devices running in mobile view are presented with a toggle version of the menu that can dropped down as needed providing the same functionality as the full navigation bar:

![The navigation menu toggle](readme-images/menu-toggle.png)

#### Cover Text
* Located to the left of the screen, this contains introductory text for the landing page. 
* It also contains a button labelled “know more” which navigates the user to the Start Yoga page. 

![Cover text from landing page](readme-images/cover-text.png)

#### Footer

* The footer contains font awesome icons linked to the respective social media sites Facebook, Instagram, X and YouTube.
* Clicking on any of these opens a new tab with the Yoga Calm window unaffected.
* The footer is available on all pages of the site.
* **Please note**: the links are not linked to any active pages for Yoga Calm and are placeholders only.

![The footer with social media icons](readme-images/footer.png)

## Start Yoga Page (startyoga.html)
### Features
The start yoga page firstly begins by presenting the user with a warm welcome and congratulating them on taking the first step. It further describes the intention of the yoga poses selected and their proposed aim. 

As the landing page introduced, the poses selected are tailored to help people working remotely. For example, individuals sitting down for extended periods of time resulting in back pain or the need to stretch their legs!
The content on the page is displayed so it is easy to follow: the instructions placed on the left with image displayed to the right. 

![A snapshot from the startyoga](readme-images/start-yoga-snapshot.png)

The bottom of the page also holds a brief disclaimer:

![Disclaimer](readme-images/disclaimer.png)

## Win! Page (feedback.html)
### Features
The motivation on this page is the offer to win a free mat on providing feedback.

This page features a form collating information about the user and a chance to provide some feedback.
The information collected is: 
* Name.
* Email address.
* Age.
* How many days worked from home.
* Additional feedback. 
* Option to join a mailing list. 

Required fields on the form are:
* Name.
* Email Address (in the correct format).
* How many days working from home.

![A snapshot from the Win page](readme-images/win-snapshot.png)

Submitting the form successfully posts the data to a holding page, ready to be processed. An example of this can be seen [here.](readme-images/form-submitted.png)


## Testing

* The site has been tested on desktop versions: Chrome and Edge 
* The site has been tested on mobile versions of Chrome and Safari on the following devices:
  * Samsung S24 Ultra
  * Samsung A32 5G
  * iPhone 14 Pro 

* The site has been tested using the built-in window Narrator from an accessibility point of view.
* The navigation and menu toggle has been tested on desktop and mobile views for functionality and clarity.
* The form has been tested to ensure the required fields receive focus if left out.
* The email address field will only accept the correct format for an email address.

### Bugs
**Issue:** Backgrounds/images were taking longer than normal to load up specifically on mobile devices and affected the lighthouse results.

**Fix:** Using the web optimisation tools (listed under tools and Technology), the images were optimised and converted to webp files. This drastically improved the performance and user experience.

### Validation Testing

* HTML
   * No errors returned when running the official W3C validator on all three pages [W3C HTML Validator ](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnaveednaseem84.github.io%2FPP1-Yoga-Calm%2Findex.html)
 * CSS
    * No errors were found when running the official jigsaw Validator tool on all three pages [(Jigsaw) Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fnaveednaseem84.github.io%2FPP1-Yoga-Calm%2Ffeedback.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) 

### Accessibility/performance
Lighthouse in devtools produced the following results:

 **Index page:**

  ![Lighthouse score for the index page](readme-images/index-lighthouse-score.png)

**Start yoga page:**

![Lighthouse score for the start yoga page](readme-images/startyoga-lighthouse-score.png)

**Feedback page:**

![Lighthouse score for the feedback page](readme-images/feedback-lighthouse-score.png)

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:
* In the GitHub repository, navigate to the Settings tab
* From the source section drop-down menu, select the Master Branch
* Once the master branch has been selected, the page will be automatically refreshed (a manual refresh may sometimes be needed) with a detailed ribbon display to indicate the successful deployment.

The live link to the site can be found here: [Yoga Calm](https://naveednaseem84.github.io/PP1-Yoga-Calm/index.html)

## Technologies Used
### Languages used
* HTML

* CSS

### Frameworks, Libraries and Programs Used
* #### Google Fonts: [Google Poppins font](https://fonts.google.com/specimen/Poppins)
  * The ‘Poppins’ font was imported into the style sheet (style.css) and used throughout the project.

* **Font Awesome:** [Font awesome](https://fontawesome.com/)

  * The social media icons on the footer and the toggle menu icon were placed used font awesome. The classes used are listed in the UX view section below.

* **Git/Gitpod:**

  * Gitpod’s workspace was used using the VSCode online editor using git to push to GitHub using version control. 

* **GitHub:**

  * GitHub has been used to store the version control repository for the project and provide a live working external link once deployed.

* **Figma**: [Figma: The Collaborative Interface Design Tool](https://figma.com/)

  * Figma has been used to create the Yoga Calm logo and the UX illustration of the site.
It has also been used to create the site map.

* **Tiny PNG:** [TinyPNG – Compress WebP, PNG and JPEG images intelligently](https://tinypng.com/)

* **Pixelied:** [Pixeled](https://pixelied.com/convert/jpg-converter/jpg-to-webp)

  * Tiny PNG and Pixelied were used to optimise the images for web use. 

## User Experience (UX)
### User Stories

  * As a first-time timer user, I want to see a clear landing page that loads quickly and is appealing to the eye.
  * As a first-time user, I want to be able to understand the purpose of the site with easy points of navigation.
  * As a user of the site, I want to be able to easily sign up so that I can keep up to date for any new content or news.
  * As a user of the site, I want to be able to navigate on to the social platforms for the site to see how others feel about the content or style of the site and share my thoughts.
  * As a regular user of the site, I want the option to view the site either on a desktop or mobile so I can continue my reading where and when it suits.

### Mind Map: Ideas
An "initial pen to paper" ideas map was created on potential structure and content ideas. This can be viewed [here.](readme-images/mindmap.png)


### Wireframe Designs
Following on from the mind map, a wireframe design was created.

* [Landing Page](readme-images/wireframe-landing.png)
* [Start Yoga Page](readme-images/wireframe-startyoga.png)
* [Feedback Page](readme-images/wireframe-feedback.png)


### UX View of Site

Following on from the wireframe design, a final UX view of the site was designed and can be viewed [here.](readme-images/final-ux-design.png)

### Site Map

A top-level site map for the site can be viewed [here.](readme-images/site-map.png)

## Future Developments
There are two potential future developments for this project.

1. Implementation of videos: Visual instructions of the poses for those that would like to watch and learn.
2. The option to search the site for a particular pose.

## Credits
### Content
* The following stylesheet code was used from the Love Running project to remove any default styling:
 * `{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}`
* The code for the toggle menu, navigation menu, and the idea for the footer social icons was taken from the love running CI project and adapted to the Yoga Calm project requirements.

* The favicons used were also from the Love Running project.

 Reference links for both:
  [Love Running walkthrough Project](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRFX101+5/courseware/e805068059af42af87681032aa64053f/7525117e5cd144daa2a7b0c57843bbee/?child=first)

#### Landing page:
* The background was taking from: [A Person doing Yoga - Pexels](https://www.pexels.com/photo/a-person-doing-yoga-6648548/)

* The quote  was taken from:  [105 Best Yoga Quotes to Inspire your Practice - Parade](https://www.pexels.com/photo/a-person-doing-yoga-6648548/)

#### Start Yoga page:
* Yoga general facts:
  * [Yoga - Wikipedia](https://en.wikipedia.org/wiki/Yoga) 
  * [Explore The Ancient Roots of Yoga — Google Arts & Culture](https://artsandculture.google.com/story/explore-the-ancient-roots-of-yoga/rAKCRDl92CPuJg)

* The tree pose image was taken from: [Cheerful sportswoman practicing yoga tree pose - Pexels](https://www.pexels.com/photo/cheerful-sportswoman-practicing-yoga-tree-pose-4498150/)
 

* The seated twist pose was taken from: [A Woman in the Living Room Sitting on the Yoga Mat -Pexels](https://www.pexels.com/photo/a-woman-in-the-living-room-sitting-on-the-yoga-mat-6975772/)

* The forward roll pose image was taken from: [A Woman Bending Her Body while Standing on a Yoga Mat - Pexels](https://www.pexels.com/photo/a-woman-bending-her-body-while-standing-on-a-yoga-mat-4534679/)

In addition to my own understanding and usage of the poses on this page, the following sources were used as a reference guide for the yoga pose instructions:
* [Tree Pose - Ekhart Yoga ](https://www.ekhartyoga.com/resources/yoga-poses/tree-pose)
* [How to Do Easy Pose with Twist – EverydayYoga.com](https://www.everydayyoga.com/blogs/guides/how-to-do-easy-pose-with-twist)
* [Standing Forward Bend - Ekhart Yoga](https://www.ekhartyoga.com/resources/yoga-poses/standing-forward-bend)


#### Feedback page:
*  The background was taken from: [Man Stretching Leg - Pexels](https://www.pexels.com/photo/man-stretching-leg-6698496/)

## Personal Summary
The project on a whole has brought with it reasonable learning curve. Ranging from the dos and don’ts from an industry standard point of view to the amazing support available on the slack channels, and the invaluable advice from an amazing mentor. This learning has been noted and any actions arisen as a result to work upon.

One of the main points that I have taken away is around GitHub. As this was my first project using GitHub and proper version control , the use and understanding has increased whilst pushing out to my repository. Reflecting back, there may have been some commits that could have combined with others, but I endeavor to take this on as an action to practice and refine for future projects.


