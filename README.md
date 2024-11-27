# PeacefulMinds
![Responsive Mockup](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/ResponsiveMockup.png)

| [Live Project](https://mc5g204.github.io/PeacefulMinds/) |

## Introduction
PeacefulMinds is a assessed portfolio project developed as part of the Code Institute Full Stack Software Developer Bootcamp, with the intention of demonstrating proficiency in HTML5, CSS and Bootstrap to create a static website which fits the requirements provided in the project brief (which is shown below).

![Project Brief](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/ProjectBrief.png)

## Features 
Several features were implemented to ensure the project met the requirements of the project brief. The website consists of three pages with distinct sections to ensure a good user experience.

All features on the website were implemented using a combination of HTML5, CSS and Bootstrap and are responsive on multiple device sizes in accordance with appropriate breakpoints. 

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Homepage, Resources and Comments pages and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

- __Hero Section__

  - The homepage includes a jumbotron in the hero section with text overlay to grab the user's attention.
  - This is followed by a brief introductory text to introduce the user to the website.

![Nav Bar & Hero Section](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/Website_NavBar.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites. The links will open to a new tab to allow easy navigation for the user.
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/Website_Footer.png)

- __Bootstrap Cards__

  - The Bootstrap Card feature was used several times throughout the website to provide a clean organised interface and consistent design across the pages.
  - The homepage cards have a lot of information and they have no attached images to ensure easy navigation on the website.
  - The Resources cards have less text so images were included to make the page more visually appealing.

![Homepage Cards](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/Website_HomepageCards.png)
![Resources Cards](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/Website_ResourcesCards.png)

- __Table of Links__

  - This section in the Resources page was included to format the links in a appropriate manner and give a brief description of the linked resources to guide users.
  - The links will open to a new tab to allow easy navigation for the user. 

![Resource Links](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/Website_ResourceLinks.png)

- __Side Panel__

  - The Comments page has a side panel overlay appear on the screen when the user clicks a button.
  - An overlay was selected instead of having the panel showing at all times as this would be less distracting to users who just wanted to view the page and not contribute.

![Side Panel Overlay](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/Website_SidebarActive.png)

---

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Google Lighthouse Testing

High scores (90+) were achieved for both Desktop and Mobile when passing through the official [Google Lighthouse](https://pagespeed.web.dev/)

- Desktop
![Desktop Results](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/Lighhouse_Desktop.png)

- Mobile
![Mobile Results](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/Lighhouse_Mobile.png)

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)

![HTML Validation Homepage](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/HTMLValidation_Homepage.png)
![HTML Validation Resources](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/HTMLValidation_Resources.png)
![HTML Validation Comments](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/HTMLValidation_Comments.png)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

![CSS Validation](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/CSSValidation.png)

### Unfixed Bugs

- There was an issue with showing the background image for the Jumbotron in the hero section of the Hompage. The image will not load.

### Features Left to Implement

- Adding the functionality for users to be able to sumbit their own encouraging comments to the Comments page: this requires JavaScript, which is not currently in scope for this project.
- Adding a more contrasting colour scheme or dark mode for better accessibility: the Lighthouse assessment suggested the current contrast level could be improved on.
- Implementing more interactive features or videos to make the user experience better.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - [PeacefulMinds, https://mc5g204.github.io/PeacefulMinds/](https://mc5g204.github.io/PeacefulMinds/)


## Credits 

### Content 

- The text and content included in the website was generated using Microsoft Copilot
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media
- The photos used on the home and sign up page are from This Open Source site
- The images used for the hero section on the Homepage and Resources page are from: [https://pixabay.com/users/lavnatalia-5858294/](https://pixabay.com/users/lavnatalia-5858294/)
