# Cleanup & Connect - Website

**Location:** Tale Town, Germany (fictional place) 

Cleanup & Connect is a community-driven initiative focused on organizing local cleanups and strengthening social ties in Tale Town, Germany. The website shares information about upcoming cleanup dates, highlights the benefits of getting involved, has a gallery and offers a simple signup form for volunteers. The site targets interested locals and guests alike to join upcoming cleanups, to do something good for the environment, community and themselves. 

![Screenshot 2025-04-28 at 16 25 01](https://github.com/user-attachments/assets/03079507-033c-4399-bac4-b14a383f10c9)

## Features
### Navigation Bar
A fully responsive Navigation bar is featured on all pages, including links to the Logo (home page), Home page, Gallery and Sign up form. It is identical on each page and fixed to the top of the screen to easily navigate the different sections and pages. On devices with a width of less than 768px the menu is toggable and will open in a dropdown list.

![Screenshot 2025-04-29 195250](https://github.com/user-attachments/assets/0c09014a-42ed-427d-a65b-13df2df34ccc)
![Screenshot 2025-04-29 195314](https://github.com/user-attachments/assets/36d8f557-0b6f-45f8-8556-3be86838d349)

### Hero Image on the landing page
An eyecatching image of a group of people collecting trash together provides the users an initial insight into the initiative. The name of the initiative is included as a text overlay in the image.

![Screenshot 2025-04-29 195116](https://github.com/user-attachments/assets/456f97dc-1f55-4058-bd43-7be5fba920a0)

### "Who we are" section
The "Who we are" section provides an introductory overview of the initiative, its background and target group, and aims to build trust and connection with the user. 

![Screenshot 2025-04-29 195422](https://github.com/user-attachments/assets/bbf6e864-7cac-4460-bd14-c9fd43ec543f)

### "Why Join" section 
The "Why join" section highlights key benefits of the initiative on a general and personal scale. This section should motivate interested people to join a cleanup.

![Screenshot 2025-04-29 195450](https://github.com/user-attachments/assets/8341df1a-fc0b-4913-8636-fcefac429710)

### Upcoming Dates section
In this section the user gets an overview of all upcoming cleanup dates. The date, time and meeting place is included for all cleanups to provide the user with all relevant information, so that they can decide if they are able to join.

![Screenshot 2025-04-29 195542](https://github.com/user-attachments/assets/cd0770c8-ef3f-4bab-82c2-228794002681)

### Footer
The footer includes links to social media sites for Cleanup & Connect. The links will open in new tabs and are accessible through each social media platform's generally known icon (Facebook, Instagram, X and YouTube). The icons in the footer are responsive, as they change their colour when hovered on. 

![Screenshot 2025-04-29 195610](https://github.com/user-attachments/assets/4b0ab59c-4d46-4115-8cb9-32381049b49b)

### Gallery 
The gallery shows a variety of images of cleanups, trash in nature and clean landscapes, to provide an overall insight of what a cleanup looks like, and what changes can be achieved by showing examples of before and after photographs. 

![Screenshot 2025-04-29 195709](https://github.com/user-attachments/assets/c2f92e72-38f7-476b-9b62-76b1fd75ead1)

### Sign up page
The Sign up page allows interested users to stay informed about the Cleanup & Connect initiative and signup for future cleanup dates through a form.The user is required to provide their full name, email address and message, and has the option to select  upcoming cleanup dates.

![Screenshot 2025-04-29 195946](https://github.com/user-attachments/assets/cdc5338e-0423-4cf0-abad-670adb2952f3)

### Success page (sign up confirmation)
Following the submittance of the sign up form the user is directed to a success page to signal that their information has been sent and received. The success page includes a short positive message and a button to return to the home page.

![Screenshot 2025-04-29 200236](https://github.com/user-attachments/assets/ef5c6ef1-6171-474f-bc2b-25dc86b258e5)

## Potential additional features that could be added in the future
- announce cleanups in further places 
- add a page with general information on recycling and avoiding trash
- add a page with information about previous cleanups (i.e. what was collected, how much trash was collected, interesting findings)
- add a page to look for sponsors and partners for the cleanups

## Design & Layout
- Responsive design (mobile-first approach)
- Consistent layout for intuitive navigation
- Nature-inspired, minimalist styling with green tones
- Custom white logo and consistent branding

![Screenshot 2025-04-29 201145](https://github.com/user-attachments/assets/9e9a29ad-d19d-4b08-bb3d-48ffdd8840e6)
![Screenshot 2025-04-29 201207](https://github.com/user-attachments/assets/ad896e7c-a0cc-4d22-8df8-ca42717b9e00)
![Screenshot 2025-04-29 201219](https://github.com/user-attachments/assets/e3c0159b-ccf8-4f12-8286-cecbbb262f60)

## Testing
### Manual Testing 
The website was tested on screen sizes from small to extra large for its responsiveness, navigation and overall layout. All pages of the website are repsonsive. All external links open in new tabs and respond upon hovering over them. The internal links lead to the correct page on the website and also respond upon hovering over them. 

### Lighthouse Testing 
Perfomance, Accessibility, Best Practises and SEO were analyzed through Lighthouse. All categories show good results. 

![Screenshot 2025-04-28 at 16 27 25](https://github.com/user-attachments/assets/3ae6b5ca-6043-45f9-b32d-fa439bd9ad06)

### Validator Testing
- HTML validator
  - No errors or warnings were shown when passing through the official [W3C validator](https://validator.w3.org/)
  
![Screenshot 2025-04-28 at 16 28 37](https://github.com/user-attachments/assets/fbf8eb9e-459c-40d9-9a45-c62286ef0ed4)

- CSS Validator
  - No errors or warnings were shown when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator.html.en)

![Screenshot 2025-04-28 at 16 29 00](https://github.com/user-attachments/assets/35c64637-a0a5-4936-9590-d35551ddd29f)

- WAVE® Evaluation Tool
  - No errors were shown when passing through the [WAVE Web Accessibility Evaluation Tools](https://wave.webaim.org/)

![Screenshot 2025-04-28 at 16 33 23](https://github.com/user-attachments/assets/b2bb44a9-f1b9-4def-9160-cae9cfa55e41)

### Fixed Bugs
- Faulty connection between the pages due to a misspelling of the style.css file (bug: stlye.css).
- Low performance and slow loading of the site fixed by adjusting the size of all images used.
- Center alignment of social links in the footer ensured by adding a margin-right value of 16px.

### Unfixed Bugs
None

## Deployment
The site was deployed to GitHub pages. The steps to deploy are as follows:
1. Go to the **Settings** tab in the GitHub repository
2. In the sidebar on the left select **Pages** (in the Code and automation section)
3. Ensure to:
- select "Deploy from a branch" under source 
- select "main" under Branch
- set the folder to "/ root"
4. Click **save** (located in Branch section)
5. Return to the "<> Code" tab 
6. Refresh the page after a couple of minutes, until a new section "Deployments" is available in the sidebar on the right
7. Click on **github-pages** in this new section 
8. The link to the latest deployment is accessible through a link in a box at the top of the page 

The live link to the Cleanup & Connect website is accessible here - https://jene87.github.io/p1-cleanup-connect/

## Credits
### Code
All code is inspired by lessons and modules included in the Code Institute's Full Stack Software Development Common Curriculum in the Learning Management System.

### Content & Media
- Font used: [National Park](https://fonts.google.com/specimen/National+Park) (Google Fonts), with sans-serif as the backup font
- Images were downloaded from the open source sites [Pexels](pexels.com) and [Unsplash](unsplash.com)
- Colors and color palette were chosen from [Canva](canva.com) and [Coolors](coolors.co)
	- #08392B (dark green) 
	- #87C38F (light green) 
	- #BF4E30 (orange) 
	- #F4F0BB (yellow)
- The [Recycling Favicon](https://favicon.io/emoji-favicons/recycling-symbol/) was downloaded from Favicon.io.
- The logo was created by [ChatGPT](chatgpt.com)
- The texts were written by the author with support by [ChatGPT](chatgpt.com)
