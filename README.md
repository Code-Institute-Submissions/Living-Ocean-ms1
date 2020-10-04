[Link to live website here](https://rdgrover.github.io/Living-Ocean-ms1/)

# Living Ocean Trust Charity Website
This website has been created to promote the ideology of the Living Ocean Trust and to show clearly what they are doing and how the user can help. The oceans are currently
facing an ecological disaster the likes of which have never before been seen. Plastic, which was once praised as a miracle product is now polluting our waters, poisoning them
and large numbers of marine life. Unless we act soon we will no longer have a 'Living Ocean'.

### Website Purpose:
* Create awareness of the issues currently facing the ocean
* Make it clear what the Living Ocean Trust are doing and how the user can get involved
* Make donating available on the website, and make it clear how to donate

![Website displayed on multiple devices](https://github.com/RDGrover/ocean-charity/blob/master/assets/images/readme/multi-device.png)

# UX

### First time user goals:
* To understand what the trust's goals are and why they are trying to achieve it
* Easily navigate between pages
* Facts to show the need for the trust's existence
* Images to make you feel immersed, as though you are in the ocean
* Links that lead you through the website to the donation page

### Returning user goals:
* Access information and resources easily
* Find contact information and volunteer information to get in contact
* Get quick access to 'tips and tricks'

### Frequent user goals:
* Educators and businesses can easily find the website and it's resources
* Finding contact information easily to discuss use of resources or to organise an event

# Design

### Brand Colours:
* Blue #406ce4b2
* Orange #fc6a16
* Off-White #fafafa
* Dark Blue rgba(0, 14, 54, 0.7)
* Light Blue rgba(51, 148, 228, 0.55)
* Navy Blue #29438a
* Pale Blue #7096ff
* There were additional colours used for additional items

### Images: 
* All images are sourced from [unsplash](https://unsplash.com/) and [pexels](https://www.pexels.com/)

### Containers:
* All elements except the navbar are placed within the same container for consistency across all pages

### Features:
* Header and Navbar
  * Logo including a font awesome icon
  * Navbar has links to other pages on the website in hamburger menu
  * All navbar elements have a hover function to highlight which link you are selecting and an active attribute to show which page you are currently on

* Footer
  * Contact information
  * Link to social media including a hover function to indicate which link the user is selecting
  * A subscription form for a mailing list
  
* Homepage 
  * Jumbotron with a call to action directing them to donate 
  * Links to The Facts page


* The Facts Page
  * Link to How You Can Help page
  * Background image which changes to a new image on hover
  * Background image which zooms in on hover


* How You Can Help Page
  * Link to Donate page


* What We're Doing Page
  * Link to How You Can Help page


* Donate Page
  * Form element with two text inputs, an email input, two radio inputs and a submit button


# Wireframes
* Balsamiq wireframe [view](https://github.com/RDGrover/ocean-charity/blob/master/assets/images/readme/wireframe.pdf)

# Technologies Used

1. Languages used: HTML5 and CSS3
1. Bootstrap
   * Bootstrap v4.5, jQuery
1. Font Awesome 
   * Font Awesome v5.15, icons were used in headings to visually indicate its content
1. Git
   * Used for version control, code created in GitPod then committed and pushed to GitHub
1. GitHub
   * Code is stored using GitHub
1. w3school, stackoverflow and CSS tricks
   * All the above were used for guidance on how to style elements how I wanted, particularly the styling of background images in The Facts page
1. unsplash and pexels  
   * Used to source free images used throughout the website

# Testing 
* [W3C Markup Validator - Results](https://github.com/RDGrover/ocean-charity/blob/master/assets/images/readme/html-validator.png)
* [WSC CSS Validator - Results](https://github.com/RDGrover/ocean-charity/blob/master/assets/images/readme/css-validator.png)

### First time user goals:
* To understand what the trust's goals are and why they are trying to achieve it
  * Home page has two sections with information about the issues
  * The Facts page has further detailed information on the issues that the oceans face
  * What We're Doing page shows how the trust is addressing these issues
  
* Easily navigate between pages
  * Navbar is present as a hamburger menu across all pages 
  * Hamburger menu adheres to design conventions and is present in the top right corner of the header on a fixed top so it can always be accessed
  * Home page contains buttons that lead to How You Can Help, The Facts and Donate pages
  
* Facts to show the need for the trust's existence
  * Two sections on Home page outline the main issues the trust are combatting 
  * The Facts page has more detail on the issues and how they have come about

* Images to make you feel immersed, as though you are in the ocean
  * Background image across website is of an underwater scene
  * On Home page there are images next to the two sections to illustrate their content
  * On The Facts page the background of the containers alters when hovered over to make the page more dynamic
  
* Links that lead you through the website to the donation page
  * Button that leads directly to the Donate page is present in the callout on the Home Page
  * Button that leads directly to the Donate page is present beneath the donate to us section in How You Can Help page
  * The navbar has a link to the Donate page and is present at the top of all pages

### Returning user goals:
* Access information and resources easily
  * Pages are named to make it clear what their content is and allow the website to be navigated easily
  * Information is readily available on The Facts and What We're Doing pages as well as some general information on the Home page
  * Resources are present at the bottom of the What We're Doing and How You Can Help page
  
* Find contact information and volunteer information to get in contact
  * Contact information is present in the footer across the website
  * An additional contact button is present in the education section of What We're Doing page
  
* Get quick access to 'tips and tricks'
  * This section can be accessed in How You Can Help and has a button with an external link

### Frequent user goals:
* Educators and businesses can easily find the website and its resources
  * Contact button present in What We're Doing page to make available options clear

* Finding contact information easily to discuss use of resources or to organise an event
  * Contact information is present in the footer across the website
  * An additional contact button is present in the education section of What We're Doing page
  
### Across Devices
* On mobile devices Home page does not have the images associated with the two sections, on desktop view the images appear alongside the text
* On mobile devices What We're Doing page sections appear stacked on top of one another, on desktop view the sections appear side by side 
* On mobile devices How You Can Help page sections appear stacked on top of one another, on desktop view the sections appear side by side 
* Font sizes on the home page are smaller on mobile devices than on desktop devices

### Known Issues
* The hover element given to the background images in The Facts sometimes do not change unless hovered over in a specific area

# Deployment

### GitHub
Project was coded using GitPod and Git:
1. Use git add to move code from the workspace to staging area
1. Use git commit to save files to a local repository with a message to say what has been changed since previous commit
1. Use git push to move the files from a local repsoitory to a remote repository like GitHub

Project was deployed through GitHub:
1. Log into GitHub
1. Select Repository to be deployed
1. Click settings on the right side of the repository action bar
1. Scroll down to GitHub Pages section
1. Select Branch: Master, folder: Root and click save
1. The page will refresh taking you back to the top, scroll down to find your published page link

![Image to show website has been published](https://github.com/RDGrover/ocean-charity/blob/master/assets/images/readme/ocean-publish.png)

# Credits

### Content
* Inspiration for the callout jumbotron came from Bootstrapping Your Next Big Idea mini project, Code Institute Full Stack Developer course


### Media
* All photos used across the website have been sourced from either unsplash or pexels
