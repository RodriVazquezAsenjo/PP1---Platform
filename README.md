Overview
Platform is  a website produced as a deliverable for the Code Institute Full Stack Development Software Diploma course. It presents a mentoring services company and highlights knowledge on HTML5, CSS and UI/UX design. 
The company offers a mentoring course with a number of different mentors to adjust to the mentees requirements. Users will come to this website and view a modern and clean aesthetic which aims to represent an avant-garde philosophy by the mentoring company.


Table of Contents.


User Experience
1. Strategy Plane
Purpose
At this level in the strategy plane, the objectives and the users serving those goals are identified. 
Product Objective: To create a platform where potential users will be attracted to sign up to the mentorship program. 
User Needs: 
Client: To transmit in a clear and concise idea the company image, and to provide a way for the potential mentees to sign up to the program. 
Customer: To be able to find all the information required to make an informed decision on signing up to the mentorship.
Business Objectives: To attract customers, and increase uptake of customers. 
User Stories:
Client Story #1: To create a modern website which displays the identity and values of the company. 
Acceptance: The website will be dynamic and modern in aesthetics, it’ll include values and collaborators to provide a sense of identity and magnitude.
Client Story #2: To quickly direct viewers to signing up for the course.
Acceptance: The website will have numerous links to the sign up section, including a link on the landing page. 
Customer Story #1: I want to be able to quickly view the course program so that I can see if I’m interested in signing up for the course.
Acceptance: The website will include a link on the landing page to view the course program. 
Customer Story #2: I want to view the different mentors I can apply including their area of expertise, a profile picture and a short bio. 
Acceptance: The website will include a section only on the mentors. 

2. Scope Plane
Once the strategy is set and the abstract objectives have been defined, we can contextualize this in the Scope Plane. The objectives will be reviewed into clear goals, which will be fulfilled by a list of features the website will need to follow. 
Features
The website will have three different pages which will be accessible at any point from any of the pages, you’ll land on the home page which will include course information and a link to the sign up form. It will also include partners the company regularly interacts with and values which they stand for. The second page will be solely on the information regarding the different mentors available, while the third page will have the sign up form, and the contact information. 

3. Structure Plane
On the structure plane, the ways in which the user navigates the website are defined, where will the user land, what will be his options from where he lands and further on. 

As the user accesses the website, he’ll be landing on the home page, where he will be greeted by a hero video clearly portraying a sense of professional development. Here, he’ll notice the navigation bar at the top, present in all pages, which will be able to take him to a mentor page and a signup page, and just below the video he’ll find two buttons supported by a slogan which will give him the option to download the course program and to sign up.

If the user decides to scroll down the website, he’ll view the values the company stands by and the companies that [platform] is involved with. At the bottom of the website, there will be a footer with important information replicating in every page. This footer will include the address where the company can be found, any social media links and further navigation tools. 

If the user decides to instead click on either of the links at the top of the website, he’ll be redirected to the mentors or sign up form. 
The mentors webpage will have display in a minimalistic view the different mentors available together with a short description and their name. The sign up page will have a form requesting contact information from the user together with a text box where the applicant can state what his intentions are with the course to be best matched with a mentor. This site will also have contact information. 

4. Skeleton Plane
Layout
Wireframes: can this be done in iOS Notes?


5. Surface Plane
The surface plane is concerned with the visual aspects of the specific features of the site. Below is each one listed with the design principles alongside. 
Font used: Comfortaa.
Color scheme used:
Main Color:
Supplementary Color:
Secondary Color:
Highlights Color:
Shadows Color:

Feature #1: Navigation Bar
The navigation bar will be present in every page. It will show the logo at the top left and the navigation options on the top right. All of these features will be animated when hovered over in a similar fashion, scaling up and changing color to the highlights color. Additionally, the selected website will be enlarged and have an underline. 
It is worth noting that in resolutions smaller than 768px, the navigation bar links will be collapsed into a burger menu. 

Feature #2: Hero Video
The landing video is displayed across the entire width, on autoplay, looped and muted. 

Feature #3: Propaganda section buttons and slogan. 
The website maintains a consistent presentation across the pages, enveloping the headers into a off-white rounded boxes. Boxes will have rounded edges, and be animated on hovering and on selecting. This will be done by scaling up and changing the color distribution. 

On the values section, there will be a number of cards which pull down on hovering which reveal the description for each of the values. 

On the partners section, a scrolling gallery has been added, showing with more dynamicity and interest the logos of the companies [platform] is involved with.
The footer section shows the address of the company, the social media links and a further navigation link option. Each of the elements will be scaled and change color when hovered over. 

The mentors section shows clearly profile images of each of the mentors, on a dimmed grayscale. When hovered over, the images will turn into color and a bio including the relevant industry will pull down from each of the cards. 



On the last page, the user will find the sign up form where the form will require First Name, Surname, Email address, Password and an application box where applicants can send out a brief on why they want to join the mentorship program. Each of the items is animated differently on hovering and on selecting. The submit button is also animated.  


The contact information is found adjacently to an interactive map of the address of the institute. The user will be able to access the map when clicked in, and will found the address and phone number and email address. 


The logo will be found
(Color Schemes, principles of design, typography, 

Technologies Used
This project has been completed using the following:
Languages:
HTML5
CSS
Resource Libraries:
GitHub
GitPod
Google Fonts
Pexels
Font Awesome
(Balsamiq)?
(Beautify.io)?
(iOS Notes)?
(Should I put any reference code I’ve checked out?)

Testing
Testing of this website has been done as follows:
Validators:
Google Lighthouse: Measures the performance, accessibility, best practices and SEO.
HTML Validator: Checks for any errors in the HTML code.
CSS Validator: Checks for any errors in the CSS code. 

Browser compatibility:

Chrome: Pass
Safari / Edge: One animation bugging
Firefox: ??? 

Functionality
Test ID
Test Label
Test Action
Expected Outcome
Test Outcome
T01
Nav bar hovering
Hovering over the nav bar links, and the logo.
The logo and the links should scale up and turn orange when hovered over. The bottom border should turn orange when the header is hovered over.
Pass
T02
Nav bar links
Clicking the logo and the navigation menu items
The platform logo on the top left should direct the user to the home page, the home item should direct the user to the home page, the mentor item should direct the user to the mentor page, the contact us item should direct the user to the sign up and contact page.
Pass
T03
Responsive nav bar
Reducing the width of the viewport to test the responsiveness of the website.
Below 768px the nav bar will collapse into a burger menu logo which drops down the menu items when checked. Pass 768px the nav bar will display all its items horizontally along the top of the page in a fixed position
Pass
T04
Hero Video
Opening up the website
The video should autoplay, muted and looped infinitely
Fail - Safari devices don’t autoplay the video. A play button is shown instead. 
T05
Propaganda buttons
Clicking on the buttons
The “download course content” button scales up and changes the color scheme when hovered over. It changes color scheme one further time when actioned. Once clicked, a pdf should download. 

The “sign-up” button scales up and changes the color scheme when hovered over. It changes one further time when clicked and actioned. Once clicked, the button should direct you to the sign up form in the Contact page
Pass
T06
Propaganda buttons responsiveness
Adjusting the width of the device. 
The buttons will stay central in all widths, adjusting the height of the box.
Pass
T07
Values cards animations
Hovering over the values cards
The values card will one by one pull down an extra height of the box which will include a short description of its title. 
Pass
T08
Values cards responsiveness
Adjusting the width of the device.
As the width narrows the cards will retain the same item width and occupy the most available horizontal space, wrapping below when there is not enough.
Pass
T09
Gallery autoscrolling
Observe gallery
The gallery will automatically scroll in a carousel infinitely.
Pass
T10 
Footer animations
Hover over the footer items
The footer items will scale up and change to orange as they’re hovered over in all pages. 
Pass
T11
Footer links
Click the different items of the footer
The address div will take you to the sign up form and address when clicked on.

Each of the social media logos will take you to their respective social media when clicked.

The nav links at the bottom right will take you to its respective pages.
Pass
T12
Footer responsiveness
Adjust the width of the viewport.
Each of the divs (address, social media, navigation) will respond to the width available occupying the maximum available horizontal width, when this is not available they will wrap below.
Pass
T13
Mentor Cards animations
Hover over the mentor cards.
The mentor cards will change from grayscale to color when hovered over, the border will change colors, the card will scale up and a description will pull down. 
Pass
T14
Mentor cards responsiveness
Adjust the width of the viewport.
The mentor cards will respond to the width available occupying the maximum available horizontal width, when this is not available they will wrap below.
Pass
T15
Sign-up form animations
Hover over the sign up form and click each of the items. 
When hovered over the sign up form will scale up and change to a lighter blue.

When hovered over, the outline of the text inputs and their labels will turn orange. When clicked in, the background color of the input box will change to white, and the box and the label will scale up. 

The button will also scale up when hovered over, and will change color scheme. It will further change its color scheme when pressed. 
Pass
T16
Sign up form button link
Press the button
When pressed, apart from the change in color scheme, a form will be sent to the following link: https://formdump.codeinstitute.net/.

The fields of first_name, surname, email, password and coverletter will be filled.
Pass
T17
Sign up form required fields
Press the button without filling up the fields
The form will not be sent until all the fields have been appropriately filled, including the email which will require a @ and a . and th password will not show the characters when the field is unselected. 
Pass
T18
Interactive map animation
Hover over the map
The map will scale up when hovered over. 
Pass
T19
Email in the address section of the contact us page
Click the email
The email should redirect you to gmail when pressed on. 
Pass. 







Responsiveness

Deployment
Deployment of this website has been done through the repository found in GitHub. (https://github.com/RodriVazquezAsenjo/PP1---Platform)
Once in this link, click on the settings tab on the top navigation bar.
After, click on the pages tab on the left-hand menu under the code and automation section.
Here, under the “Build and Deployment” on the “Source” drop-down menu, select “Deploy from a branch”.
Next, select “Main” on the “Branch” drop-down menu, and ensure the folder is set to /(root) and save.
This will automatically deploy your site, for confirmation, ensure that a new section on the pages section shows up which states that the site is live.  
Git Clone
Cloning will be linked to your repo and any pushes they make will come to you for approval. 
Git cloning is essentially creating a copy of an existing code from a remote repository to your local repository. It is a key tool that allows collaboration between developers when producing a code and also allows for individuals to use an existing code as a baseline. When cloning a code, the associated files, commit history, branches and tags when downloaded to your local machine. 
To clone a code you’ll need to follow these steps:
Download the chrome extension for GitPod which can be found here and more information can be found here.
 Restart your browser. 
Navigate to your desired Project Repository. 
On the top right corner a GitPod button should be seen. If pressed, it will take you to the GitPod workspace and open up a copy of the project repository you wish. 
It is worth noting that any pushes intended to be done to the original code will request approval from the author of the original code. 
Forking will be in a new repo belonging to them. If you make changes to your repo, they’ll be informed and have the option to pull from yours.
Git Fork
An alternative to cloning, which maintains a relationship to the original repository, is forking. With forking you create a copy of a repository to your own account on Github. This means that the two repositories (original and forked) are now independent and the user is free to make any changes to the repository.
To create a fork, follow these steps:
Navigate to your desired repository.
Click on the fork button on the top-right corner, above the GitPod button.
Once forked, click on the GitPod Button.
Note:
Any changes pushed to the main branch will automatically show up to the main site. 

Credits
Content:
ChatGPT4.0 has been used to create the downloadable course content .pdf and the bios for the mentor cards. Any other content has been written by the developer. 
Imagery:
Images have been obtained from pexels.
Video have been obtained from Canva.
Code:
Pull down animations have been based on example code from Codepen, link here. Created by Tuan, August 28th 2021. 
Scrolling gallery has been inspired by youtube content by Online Tutorials, in the video “Infinite Scrolling Animation | CSS Only Text and Image Carousel” uploaded here on the 17th October 2023.


Acknowledgements
Many thanks to my mentor Brian Macharia whose advice in coding has been instrumental to the development of this website. 
Contact Information
Lead Designer: Rodrigo Vázquez Asenjo
Thank you for contributing to [platform]!

