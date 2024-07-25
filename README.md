# [GRAVITY FIGHTERS](https://ash-5p.github.io/Gravity-Fighters)

[![GitHub commit activity](https://img.shields.io/github/commit-activity/t/Ash-5p/Gravity-Fighters)](https://github.com/Ash-5p/Gravity-Fighters/commits/main)
[![GitHub last commit](https://img.shields.io/github/last-commit/Ash-5p/Gravity-Fighters)](https://github.com/Ash-5p/Gravity-Fighters/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/Ash-5p/Gravity-Fighters)](https://github.com/Ash-5p/Gravity-Fighters)
---

This project is a static website to promote a weightlifting club called "Gravity Fighters". It provides information about the different types of weightlifting to people who are interested in getting into the sport/hobby, and will emphasize the difference between the training styles and outcomes of each. There is a page of example workouts to try for each type of lifting, and a page offerening high-protein meal recipes with nutritional information. Gravity Fighters website's main goal is to introduce people to the club and encourage everyone from beginner to advanced lifter to try the different lifting sports.

![screenshot](documentation/homepage.webp)

![screenshot](documentation/workouts-page.webp)

![screenshot](documentation/recipes-page.webp)

Click the below link to view the site on Am I Responsive:
https://ui.dev/amiresponsive?url=https://ash-5p.github.io/Gravity-Fighters

---

GitHub now supports CALLOUTS in Markdown files.
There are some callouts already embedded in this application for you.
However, if you feel that you want to add more, there are certain ones you can use.

NOTE: the preview for callouts isn't yet supported in Gitpod/Codeanywhere/VSCode/etc.
You'll have to commit/push the changes to GitHub to see it in action.

> [!NOTE]  
> BLUE: Highlights information that users should take into account, even when skimming.

> [!TIP]  
> GREEN: Optional information to help a user be more successful.

> [!IMPORTANT]  
> PURPLE: Crucial information necessary for users to succeed.

> [!WARNING]  
> YELLOW: Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]  
> RED: Negative potential consequences of an action.

Source: https://github.com/orgs/community/discussions/16925

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

![screenshot](documentation/mockup.png)

source: [amiresponsive](https://ui.dev/amiresponsive?url=https://ash-5p.github.io/Gravity-Fighters)

## UX

🛑🛑🛑🛑🛑🛑🛑🛑🛑START OF NOTES (to be deleted)

Initial mockup design was done using Balsamiq Wireframes to establish a general layout. 

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

### Colour Scheme

🛑🛑🛑🛑🛑🛑🛑🛑🛑START OF NOTES (to be deleted)

The dark grey tones were chosen for the header and footer to emulate the dark gritty asthetic seen in a lot of weightlifting imagery, like the hero image on the homepage. White text was then chosen to contrast the dark colors for a better user experience.
These colors were then inverted for the main section of each page, as the images popped better on a white background.

- `#444444` used for primary text.
- `#FAFAFA` used for primary highlights.
- `#FAFAFA` used for secondary text.
- `#585858` used for secondary highlights.

I used [coolors.co](https://coolors.co/fafafa-585858-444444) to generate my colour palette.

![screenshot](documentation/color-scheme.webp)

### Typography

- [Anton SC](https://fonts.google.com/specimen/Anton+SC?query=anton+sc)was used for all headings and the site logo, as the large block letters was inkeeping with the theme of strength.

- [Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed?query=roboto+co) was used for all other secondary text.

- [Font Awesome](https://fontawesome.com) icons were used throughout the site, such as the social media icons in the footer, and the dumbell icon in the site logo and navbar.

## Features

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑 START OF NOTES (to be deleted)

In this section, you should go over the different parts of your project,
and describe each in a sentence or so.

You will need to explain what value each of the features provides for the user,
focusing on who this website is for, what it is that they want to achieve,
and how your project is the best way to help them achieve these things.

For some/all of your features, you may choose to reference the specific project files that implement them.

IMPORTANT: Remember to always include a screenshot of each individual feature!

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

### Existing Features

- **Header**

    - The header houses the site logo and navbar, and is fixed to ensure these features are always visible to the user no matter where they are on the current page.

![screenshot](documentation/features/header.png)

- **Gravity Fighters Logo**

    - The Gravity Fighters logo immediately draws attention due to the box-shadow effect which gives it a 3D appearence. The dumbell icon lets the user know that Gravity Fighters is a weightlifting focused website. 

![screenshot](documentation/features/logo-tablet.png) ![screenshot](documentation/features/logo-mobile.png)

- **Navbar**

    - The navbar provides the main means to navigate the whole site. This is attached to a fixed header, allowing user to switch between each page without having to scroll back to the top of the current page. The currently selected page with be indicated by a dumbell icon on the navbar.

![screenshot](documentation/features/navbar.png)

- **Footer**

    - The footer houses another logo and all of the links to the Gravity Fighters social media pages. It serves as an indicator to the user that they have reached the bottom of the page and there is no more content below.

![screenshot](documentation/features/footer.png)

- **Social Media Icons**

    - The social media icons, housed in the footer, act as links to the corresponding Gravity Fighters social media pages.

![screenshot](documentation/features/social-icons.png)

- **Homepage**

    - The homepage serves as a landing point for the user and makes it immediately apparent what the site is about. It contains a hero image of a person preparing to perform a lift, and an introduction into what/who Gravity Fighters are. It also contains an overview of the types of weightlifting.

![screenshot](documentation/features/home-page.png)

- **Types of Weightlifting Section**

    - This section provides a brief summary and a visual representation of the different types of weightlifting, allowing the user to compare them to see which format would interest them the most. Sections of the text containing key words contain links to their corrisponding wikipedia pages to encourage the user to research deeper.

![screenshot](documentation/features/lifting-types.png)

- **Workouts Page**

    - The workouts page offers a selection of sample workouts for each of the different types of lifting talked about on the homepage. This allows users to try out each style to see whch one best suits them.

![screenshot](documentation/features/workouts-page.png)

- **Workouts Summary/Detail**

    - The workouts on the workouts page are displayed using the summary/detail elements, which allow the only workout name to be shown initially until clicked on, and will then extend to reveal the full workout. This feature serves to make the page less cluttered, producing a positive response from the user, and making it obvious that their is more content below.

![screenshot](documentation/features/workouts-summary.png) ![screenshot](documentation/features/workouts-detail.png)

- **Recipes Page**

    - The recipes page

![screenshot](documentation/features/recipes-page.png) 

- **Recipes Page Navbar**

    - The recipes page navbar    

![screenshot](documentation/features/.png)

- **Competition Form**

    - Competition form

![screenshot](documentation/features/.png)

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑 START OF NOTES (to be deleted)

Repeat as necessary for as many features as your site contains.

Hint: the more, the merrier!

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

### Future Features

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑 START OF NOTES (to be deleted)

Do you have additional ideas that you'd like to include on your project in the future?
Fantastic! List them here!
It's always great to have plans for future improvements!
Consider adding any helpful links or notes to help remind you in the future, if you revisit the project in a couple years.

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

- YOUR-TITLE-FOR-FUTURE-FEATURE-#1
    - Any additional notes about this feature.
- YOUR-TITLE-FOR-FUTURE-FEATURE-#2
    - Any additional notes about this feature.
- YOUR-TITLE-FOR-FUTURE-FEATURE-#3
    - Any additional notes about this feature.

## Tools & Technologies Used

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑 START OF NOTES (to be deleted)

In this section, you should explain the various tools and technologies used to develop the project.
Make sure to put a link (where applicable) to the source, and explain what each was used for.
Some examples have been provided, but this is just a sample only, your project might've used others.
Feel free to delete any unused items below as necessary.

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

- ⚠️⚠️ REQUIRED <-- delete me ⚠️⚠️
- [![Markdown Builder](https://img.shields.io/badge/Markdown_Builder-grey?logo=markdown&logoColor=000000)](https://tim.2bn.dev/markdown-builder) used to generate README and TESTING templates.
- [![Git](https://img.shields.io/badge/Git-grey?logo=git&logoColor=F05032)](https://git-scm.com) used for version control. (`git add`, `git commit`, `git push`)
- [![GitHub](https://img.shields.io/badge/GitHub-grey?logo=github&logoColor=181717)](https://github.com) used for secure online code storage.
- ⚠️⚠️ CHOOSE ONLY ONE <-- delete me ⚠️⚠️
- [![Gitpod](https://img.shields.io/badge/Gitpod-grey?logo=gitpod&logoColor=FFAE33)](https://gitpod.io) used as a cloud-based IDE for development.
- [![Codeanywhere](https://img.shields.io/badge/Codeanywhere-grey?logo=ebox&logoColor=7F3F98)](https://codeanywhere.com) used as a cloud-based IDE for development.
- [![VSCode](https://img.shields.io/badge/VSCode-grey?logo=visualstudiocode&logoColor=007ACC)](https://code.visualstudio.com) used as my local IDE for development.
- ⚠️⚠️ CHOOSE ALL APPLICABLE <-- delete me ⚠️⚠️
- [![HTML](https://img.shields.io/badge/HTML-grey?logo=html5&logoColor=E34F26)](https://en.wikipedia.org/wiki/HTML) used for the main site content.
- [![CSS](https://img.shields.io/badge/CSS-grey?logo=css3&logoColor=1572B6)](https://en.wikipedia.org/wiki/CSS) used for the main site design and layout.
- ⚠️⚠️ CHOOSE ONLY ONE <-- delete me ⚠️⚠️
- [![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-grey?logo=githubpages&logoColor=222222)](https://pages.github.com) used for hosting the deployed front-end site.
- ⚠️⚠️ CHOOSE ONLY ONE (if applicable) <-- delete me ⚠️⚠️
- [![Bootstrap](https://img.shields.io/badge/Bootstrap-grey?logo=bootstrap&logoColor=7952B3)](https://getbootstrap.com) used as the front-end CSS framework for modern responsiveness and pre-built components.
- [![Materialize](https://img.shields.io/badge/Materialize-grey?logo=materialdesign&logoColor=F5A5A8)](https://materializecss.com) used as the front-end CSS framework for modern responsiveness and pre-built components.
- ⚠️⚠️ CHOOSE ALL APPLICABLE <-- delete me ⚠️⚠️
- [![Google Sheets](https://img.shields.io/badge/Google_Sheets-grey?logo=googlesheets&logoColor=34A853)](https://docs.google.com/spreadsheets) used for storing data from my Python app.
- [![Jest](https://img.shields.io/badge/Jest-grey?logo=jest&logoColor=c21325)](https://jestjs.io) used for automated JavaScript testing.
- [![Flask](https://img.shields.io/badge/Flask-grey?logo=flask&logoColor=000000)](https://flask.palletsprojects.com) used as the Python framework for the site.
- [![MongoDB](https://img.shields.io/badge/MongoDB-grey?logo=mongodb&logoColor=47A248)](https://www.mongodb.com) used as the non-relational database management with Flask.
- [![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-grey?logo=sqlalchemy&logoColor=D71F00)](https://www.sqlalchemy.org) used as the relational database management with Flask.
- [![Django](https://img.shields.io/badge/Django-grey?logo=django&logoColor=092E20)](https://www.djangoproject.com) used as the Python framework for the site.
- [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-grey?logo=postgresql&logoColor=4169E1)](https://www.postgresql.org) used as the relational database management.
- [![PostgreSQL by Code Institute](https://img.shields.io/badge/PostgreSQL_by_Code_Institute-grey?logo=okta&logoColor=F05223)](https://dbs.ci-dbs.net) used as the Postgres database from Code Institute.
- [![ElephantSQL](https://img.shields.io/badge/ElephantSQL-grey?logo=postgresql&logoColor=36A6E2)](https://www.elephantsql.com) used as the Postgres database.
- [![Cloudinary](https://img.shields.io/badge/Cloudinary-grey?logo=cloudinary&logoColor=3448C5)](https://cloudinary.com) used for online static file storage.
- [![WhiteNoise](https://img.shields.io/badge/WhiteNoise-grey?logo=python&logoColor=FFFFFF)](https://whitenoise.readthedocs.io) used for serving static files with Heroku.
- [![Stripe](https://img.shields.io/badge/Stripe-grey?logo=stripe&logoColor=008CDD)](https://stripe.com) used for online secure payments of ecommerce products/services.
- [![Gmail API](https://img.shields.io/badge/Gmail_API-grey?logo=gmail&logoColor=EA4335)](https://mail.google.com) used for sending emails in my application.
- [![MailChimp](https://img.shields.io/badge/MailChimp-grey?logo=mailchimp&logoColor=FFE01B)](https://mailchimp.com) used for sending newsletter subscriptions.
- [![AWS S3](https://img.shields.io/badge/AWS_S3-grey?logo=amazons3&logoColor=569A31)](https://aws.amazon.com/s3) used for online static file storage.
- [![Balsamiq](https://img.shields.io/badge/Balsamiq-grey?logo=barmenia&logoColor=CE0908)](https://balsamiq.com/wireframes) used for creating wireframes.
- [![Figma](https://img.shields.io/badge/Figma-grey?logo=figma&logoColor=F24E1E)](https://www.figma.com) used for creating wireframes.
- [![Canva](https://img.shields.io/badge/Canva-grey?logo=canva&logoColor=00C4CC)](https://www.canva.com/p/canvawireframes) used for creating wireframes.
- [![Google Maps API](https://img.shields.io/badge/Google_Maps_API-grey?logo=googlemaps&logoColor=4285F4)](https://developers.google.com/maps) used as an interactive map on my site.
- [![Leaflet](https://img.shields.io/badge/Leaflet-grey?logo=leaflet&logoColor=199900)](https://leafletjs.com) used as a free open-source interactive map on my site.
- [![Font Awesome](https://img.shields.io/badge/Font_Awesome-grey?logo=fontawesome&logoColor=528DD7)](https://fontawesome.com) used for the icons.
- [![ChatGPT](https://img.shields.io/badge/ChatGPT-grey?logo=chromatic&logoColor=75A99C)](https://chat.openai.com) used to help debug, troubleshoot, and explain things.

## Testing

> [!NOTE]  
> For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://github.com/Ash-5p/Gravity-Fighters), navigate to the Settings tab 
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://ash-5p.github.io/Gravity-Fighters)

### Local Deployment

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/Ash-5p/Gravity-Fighters) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
	- `git clone https://github.com/Ash-5p/Gravity-Fighters.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Ash-5p/Gravity-Fighters)

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Ash-5p/Gravity-Fighters)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

Use this space to discuss any differences between the local version you've developed, and the live deployment site on GitHub Pages.

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

## Credits

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

In this section you need to reference where you got your content, media, and extra help from.
It is common practice to use code from other repositories and tutorials,
however, it is important to be very specific about these sources to avoid plagiarism.

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

### Content

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

Use this space to provide attribution links to any borrowed code snippets, elements, or resources.
A few examples have been provided below to give you some ideas.

Ideally, you should provide an actual link to every resource used, not just a generic link to the main site!

⚠️⚠️ EXAMPLE LINKS - REPLACE WITH YOUR OWN ⚠️⚠️

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

| Source | Location | Notes |
| --- | --- | --- |
| [Markdown Builder](https://tim.2bn.dev/markdown-builder) | README and TESTING | tool to help generate the Markdown files |
| [Maxi Nutrition](https://www.maxinutrition.com/training/plans/Powerlifting-Training-Plan/) | workouts.html | Content for powerlifting workouts (Benchpress/Deadlift/Squat)|
| [TrainHeroic](https://www.trainheroic.com/blog/olympic-weightlifting-program/) | workouts.html | Content for olympic weightlifting workouts (Day1/Day2/Day3/Day4)|
| [Healthline](https://www.healthline.com/health/fitness/one-rep-max-how-to-calculate-and-use#how-to-calculate) | workouts.html | Content of powerlifting workouts (1RM Test) |
| [BBCgoodFOOD](https://www.bbcgoodfood.com/recipes/protein-pancakes-with-banana) | recipes.html | Protein pancakes with bannana recipe |
| [BBCgoodFOOD](https://www.bbcgoodfood.com/recipes/steak-burrito-bowl) | recipes.html | Steak burrito bowl recipe |
| [BBCgoodFOOD](https://www.bbcgoodfood.com/recipes/steak-burrito-bowl) | recipes.html | Vegan spinach omelette recipe |
| [Chris Beams](https://chris.beams.io/posts/git-commit) | version control | "How to Write a Git Commit Message" |
| [W3Schools](https://www.w3schools.com/howto/howto_js_topnav_responsive.asp) | entire site | responsive HTML/CSS/JS navbar |
| [W3Schools](https://www.w3schools.com/howto/howto_css_modals.asp) | contact page | interactive pop-up (modal) |
| [W3Schools](https://www.w3schools.com/css/css3_variables.asp) | entire site | how to use CSS :root variables |
| [Flexbox Froggy](https://flexboxfroggy.com/) | entire site | modern responsive layouts |
| [Grid Garden](https://cssgridgarden.com) | entire site | modern responsive layouts |
| [StackOverflow](https://stackoverflow.com/a/2450976) | quiz page | Fisher-Yates/Knuth shuffle in JS |
| [YouTube](https://www.youtube.com/watch?v=YL1F4dCUlLc) | leaderboard | using `localStorage()` in JS for high scores |
| [YouTube](https://www.youtube.com/watch?v=u51Zjlnui4Y) | PP3 terminal | tutorial for adding color to the Python terminal |
| [strftime](https://strftime.org) | CRUD functionality | helpful tool to format date/time from string |
| [WhiteNoise](http://whitenoise.evans.io) | entire site | hosting static files on Heroku temporarily |

### Media

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

Use this space to provide attribution links to any images, videos, or audio files borrowed from online.
A few examples have been provided below to give you some ideas.

If you're the owner (or a close acquaintance) of all media files, then make sure to specify this.
Let the assessors know that you have explicit rights to use the media files within your project.

Ideally, you should provide an actual link to every media file used, not just a generic link to the main site!
The list below is by no means exhaustive. Within the Code Institute Slack community, you can find more "free media" links
by sending yourself the following command: `!freemedia`.

⚠️⚠️ EXAMPLE LINKS - REPLACE WITH YOUR OWN ⚠️⚠️

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

| Source | Location | Type | Notes |
| --- | --- | --- | --- |
| [Alpha Coders](https://images6.alphacoders.com/100/thumb-1920-1001192.jpg) | index.html| image | hero image |
| [Alpha Coders](https://images.alphacoders.com/107/thumb-1920-1076955.jpg) | index.html| Bodybuilder Image (bodybuilder.webp) |
| [furrloveov](https://wallpapers.com/images/hd/man-with-large-muscles-weight-lifting-00g0gqx7ucmdosro.jpg) | index.html| Powerlifter Image (powerlifter.webp) |
| [Wallpapers.com](https://wallpapers.com/images/hd/passionate-fitness-junkie-weight-lifting-4hpw4d9d9k0ljvos.jpg) | index.html| Weightlifter Image (olympic-weightlifter.webp) |
| [Salt&Baker](https://saltandbaker.com/wp-content/uploads/2021/10/Chocolate-Peanut-Butter-Protein-Oatmeal-5.jpg) | recipes page | image | image of chocolate peanut butter protein overnight oats | 
| [Freepik](https://img.freepik.com/free-photo/almond-banana-pancake_1339-5262.jpg?t=st=1720985120~exp=1720988720~hmac=0fae57946d909be03ce08a276a2308b00d846f39943b90f0a29031618e84a6b5&w=996) | recipes page | image | image of pancakes with bannana |
| [BBCgoodFOOD](https://images.immediate.co.uk/production/volatile/sites/30/2020/08/steak-burrito-bowl-932949f.jpg?quality=90&webp=true&resize=375,341) | recipes page | image | image of steak burrito bowl|
| [BBCgoodFOOD](https://images.immediate.co.uk/production/volatile/sites/30/2023/05/Spinach-Omelette440x400-1c259f3.jpg?quality=90&webp=true&resize=375,341) | recipes page | image | image of vegan spinach omelette |
| [Pexels](https://www.pexels.com) | entire site | image | favicon on all pages |
| [Lorem Picsum](https://picsum.photos) | home page | image | hero image background |
| [Unsplash](https://unsplash.com) | product page | image | sample of fake products |
| [Pixabay](https://pixabay.com) | gallery page | image | group of photos for gallery |
| [Wallhere](https://wallhere.com) | footer | image | background wallpaper image in the footer |
| [This Person Does Not Exist](https://thispersondoesnotexist.com) | testimonials | image | headshots of fake testimonial images |
| [Audio Micro](https://www.audiomicro.com/free-sound-effects) | game page | audio | free audio files to generate the game sounds |
| [Videvo](https://www.videvo.net/) | home page | video | background video on the hero section |
| [TinyPNG](https://tinypng.com) | entire site | image | tool for image compression |

### Acknowledgements

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

Use this space to provide attribution to any supports that helped, encouraged, or supported you throughout the development stages of this project.
A few examples have been provided below to give you some ideas.

⚠️⚠️ EXAMPLES ONLY - REPLACE WITH YOUR OWN ⚠️⚠️

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

- I would like to thank my Code Institute mentor, [Tim Nelson](https://github.com/TravelTimN) for his support throughout the development of this project.
- I would like to thank the [Code Institute](https://codeinstitute.net) tutor team for their assistance with troubleshooting and debugging some project issues.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support; it kept me going during periods of self doubt and imposter syndrome.
- I would like to thank my partner (Lorna), for believing in me, and allowing me to make this transition into software development.
