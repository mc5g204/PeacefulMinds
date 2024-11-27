# PeacefulMinds
![Responsive Mockup](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/ResponsiveMockup.png)

| [Live Project](https://mc5g204.github.io/PeacefulMinds/) |

## Introduction
PeacefulMinds is a assessed portfolio project developed as part of the Code Institute Full Stack Software Developer Bootcamp, with the intention of demonstrating proficiency in HTML5, CSS and Bootstrap to create a static website which fits the requirements provided in the project brief (which is shown below).

![Project Brief](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/ProjectBrief.png)

## UX Design

### Wireframes

Wireframes for all pages of the website were created before coding began. Versions for desktop, tablet and mobile size were created to reflect the responsive design expected. 

For the most part, the designs remained consistent with the implementation, but some changes were made - they will be shown and explained below.

- Homepage

  - The fieldset for the cards was removed as feedback suggested it was not consistent with the rest of the website and reduced the padding between the cards making them looked cramped.
  - The idea for an accordian display for the mobile size was also removed as it was not consistent with the rest of the website.

![Homepage Desktop](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/WireframeHomepage_Desktop.png)
![Homepage Tablet](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/WireframeHomepage_Tablet.png)
![Homepage Mobile](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/WireframeHomepage_Mobile.png)

- Resources

  - The Resources page changed the least.
  - The only difference from the design to the final product was the addition of a table to organise the resource links better.

![Resources Desktop](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/WireframeResources_Desktop.png)
![Resources Tablet](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/WireframeResources_Tablet.png)
![Resources Mobile](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/WireframeResources_Mobile.png)

- Comments

  - The idea was to include a side panel which would allow users to enter their own comments and eventually have them displayed on the webpage.
  - The site has is static, so only the elements were implemented with no JavaScript funtionality.
  - Instead of a permanently displayed panel, it was changed to an overlay that could be viewed after clicking a button for better consistence across devices and a less obtrusive user experience.
  
![Comments Desktop](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/WireframeComments_Desktop.png)
![Comments Tablet](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/WireframeComments_Mobile.png)
![Comments Mobile](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/WireframeComments_Mobile.png)

### Colours & Font

- Font
  - The fonts used were taken from [Google Fonts](https://fonts.google.com/)
  - Nokora was used for general text throughout the website.
  - Offside was used for headings throughout the website.
 
- Colours
  - The colours used were taken from [Coolors](https://coolors.co/)
  - Shades of blue were chosen to be used throughout the website as they are a calm colour.

![Colour Palette](https://github.com/mc5g204/PeacefulMinds/blob/main/assets/images-readme/PeacefulMinds_ColorPalette.png)


###

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


## Testing 

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

### Manual Testing
| Function | Expected Outcome | Does it work? |
| ----------- | ----------- | ----------- |
| General - Header | The header is displayed at the top of the page and sticks there. | Yes |
| General - Logo Link | The logo and title will direct the user to the homepage when clicked. | Yes |
| General - NavBar | The NavBar links will direct the user to the relevant pages when clicked. | Yes |
| General - Footer | The footer is displayed at the bottom of the page and shows social media links and a copyright. | Yes |
| General - Footer Links | The social media links will direct the user to the relevant websites when clicked. | Yes |
| General - Footer Links New Page | The social media links will open in new pages. | Yes |
| Homepage - Hero Section | The Jumbrotron is displayed with a background image and text overlay. | No |
| Homepage - Info Cards | The cards in the Common Issues section are displayed side by side with titles and text. | Yes |
| Resources - Info Cards | The cards are displayed side by side with titles and text. | Yes |
| Resources - Info Cards Images | The cards are displayed with appropriate images showing in their headers. | Yes |
| Resources - Table | The table is displayed and has no formatting issues. | Yes |
| Resources - Table Links | The resource links in the table are displayed as a hyperlink and will direct the user to the relevant pages when clicked. | Yes |
| Resources - Table Links New Page | The resource links will open in new pages. | Yes |
| Comments - Info Cards | The cards are displayed side by side with titles and text. | Yes |
| Comments - Button Hover | The button will change colour when hovered over. | Yes |
| Comments - Button Click | The button will open a side panel overlay when clicked. | Yes |
| Comments - Side Panel | The side panel overlay will display text, an input box and submit button. | Yes |
| Comments - Side Panel Close | The side panel overlay will close when (x) is clicked or when the user clicks outside the overlay. | Yes |

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
- The fonts were taken from [Google Fonts](https://fonts.google.com/)
- The colours were taken from [Coolors](https://coolors.co/)

### Media
- The images used for the hero section on the Homepage and Resources page are from: [https://pixabay.com/users/lavnatalia-5858294/](https://pixabay.com/users/lavnatalia-5858294/)
