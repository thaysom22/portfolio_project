# Thomas Haysom - Porfolio and Blog Website

A professional and personalized, fully responsive mobile first website:

* including a landing page which displays overview of entire site and a prominent user call to action.
* displaying the owner's (my) resume (work history, education, skills, qualifications).
* presenting and linking to my coding projects on github.com.
* presenting and linking to my blog posts on medium.com.
* providing links to my professional social media accounts.
* displaying a simple contact form with my contact details.
* providing a link to download a pdf copy of my resume.

## Link to live site

[Link to live site](https://thaysom22.github.io/portfolio_project/) hosted by GitHub pages.

## Owner's goals

The owner's (my) goals for the site:

* to present my skills, experience, qualifications and abilities in a clear, convenient, professional format to potential
employers and clients. 
* to provide a clear, positive and satisfying user interface and experience to all users of the site and help establish a positive reputation for myself as
a developer and web designer with front end skills.
* to provide a convenient way for potential employers/clients/collaborators/developers to contact me so that I increase job opportunities, expand my network and  industry connections.
* to present my projects to potential colaborators and other developers so I increase my following and connections and receive more feedback and suggestions.
* to present a selection of my blog posts primarily to other developers with a similar level of skills
and experience to me so that I contribute in a small way to help others learn and grow and I benefit myself 
through comments and interactions.
* to evidence my accomplished communication and design skills so I am more likely to be hired or recommended for projects. 

This site facilitates the realisation of these owner's goals better than alternatives by:

* displaying relevant information to users while simultaneously showcasing my design and front-end development skills.
* collating all aspects of my professional online presence and directing users on clear paths to relevant information through efficient navigation.
* providing a richer, more engaging, more personalized exposition of my professional credentials, interests and personality than 
a proforma resume hosting site or document.

## User goals

The goals of various site users are:

* potential employer/client looking to hire a junior developer - wants to assess my skills and experience
quickly, get an impression of my ability and areas of strength/weakness, find relevant information about 
qualifications, view my projects and contact me easily.
* potential collaborator looking to work with a junior developer with relevant skills and experience to their needs -
wants to assess my skills and experience quickly, view my previous projects and contact me easily.
* coding student/learner/enthusiast looking for blog posts relevant to their experience and knowledge levels - 
wants to choose from and view my blog posts easily.
* other developers who may want to follow me on GitHub or otherwise connect - want to view a summary of my projects
and link to them easily on GitHub: may also want to contact me to connect. 

This site facilitates the realisation of these various user's goals better than alternatives by:

* providing a simple, intuitive user interface that facilatiates easy navigation to desired content.
* separating resume, projects and blog features of site to avoid overloading users with information and 
encapsulating what is relevant to them.
* providing easy to find, clear and standardized contact information.

## UX

### User stories 

* *('As user_type I want to achieve X by doing Y'):*

1. As a potential employer/client/collaborator I want to find out about site owner's qualifications, experience and interests by viewing an online resume.
2. As a potential employer/client/collaborator I want to obtain a copy of site owner's resume by clicking a download link.
3. As a potential employer/client/collaborator I want to view site owner's previous projects and evaluate his skill and experience by linking to relevant GitHub repositories.
4. As a potential employer/client/collaborator I want to contact the site owner, to make a proposal/enquiry about a job/project or ask a general question, by completing a simple online form or finding contact information.
5. As a potential employer/client/collaborator I want to read the site owner's blog, to assess his interets and communciation skills, by selecting from a display of links to posts.
6. As a potential employer/client/collaborator I want to view a specific professional profile of the owner by selecting from links to popular recruitment/bloging/code hosting sites.
7. As a coding student/learner/enthusiast I want to read owner's blog posts, to learn more about topics that interest me and get ideas and inspiration, by browsing a selection of sample links to full posts.
8. As a coding student/learner/enthusiast I want to view owner's projects, to learn and get ideas, by browsing a selection of sample links to GitHub repositories.
9. As a coding student/learner/enthusiast I want to make contact with the owner to discuss ideas, resources or make connections; by completing a simple online form or finding contact information.
10. As a developer/other professional contact I want to quickly find owner's work history and education by navigating to a clear online summary.
11. As a developer/other professional contact I want to easily contact the owner via a simple form or find the owner's contact details by navigating to a contact area of site.
12. As any of the above user types I want to generally find out more about the owner as a developer by being directed to relevant and categorized information about him.

## Links to wireframe mockups

[Wireframes for all pages](portfolio_project_wireframes.pdf) (pdf)

### Changes to (or not noted in) wireframes during implementation

* Added a home button in navbar. 
* Hamburger icon used on small tablet sizes as well as mobile. 
* Replaced menu modal with toggled menu below header
* Retain contact modal trigger next to hamburger icon for better UX on mobile
* Reduced header height to 80px on all device sizes
* Made overlay on hero image to display as text at bottom of image on smaller screens and speech bubble in top left on larger
screens
* Added medium icon for blog to footer links
* Project/blog/resume layout changes to 3 columns only on desktop screens, not tablet
* Added borders around main sections on tablet sizes and above on resume page
* Added image and border to blog post and project links on all display sizes, moved image to top of link with description below.
* Added CTA button link to hero jumbotron (anchor to further down page)
* Added zoom transition to hero image 
* Removed 'top of page' link from footer.
* Removed hero image sections from all pages but homepage
* Added borders around main sections of homepage on larger display sizes
* Added images in single column layout from each section to main sections on desktop view
* Moved cta button in main sections to between title and image
* Added styled hr elements between main sections on homepage
* Blurred visible part of background page (except header) when modal is active
* Added physical address info to bottom of contact form modal
* Header position:fixed on all pages
* Inserted hr divider between projects and blogposts on mobile view
* Added subtle hover grow effect and box shadow focus effect over each blogpost/project link and form submit button
* Provided user feedback for submission of contact form by browser alert 
* Provided user feedback when pressing hamburger icon menu toggler
* Added links for downloadable CV on home and resume pages

## Features

### Site map (navigation overview)

* All pages navigate to all other pages directly through navigation links in fixed header. 
* All pages navigate to external (Medium, GitHub, Linkedin) links via footer. 
* Home and resume pages include link to download resume.pdf file.
* Blog and projects pages contain numerous external links to individual posts and project repositories.

### Features across whole site

* [Header](index.html) - fixed height and fixed to top of viewport over other content on all pages and view sizes. Includes familiar top left site logo which links back to index.html and top right responsive navigation menu. 
Navigation menu includes links to Home, Projects, Blog and Resume pages; and a Contact button that opens a modal containing a contact form (described below).
All navigation links (except logo icon) provide user feedback: a background-color transition hover effect and a boxshadow active effect when pressed/clicked.
Current page (active link) has a bold font to remind the user of their current location on the site.
Navigation links in responsive navbar occupy right half of header area on desktop views, 66% on tablet views and collapse into a familiar top right 'hamburger' menu button with remaining adjacent contact link on mobile device sizes. Link heights scales subtly with viewport width on desktop views.
Hamburger menu drops down at top right of area below header when icon is pressed - dropdown menu contains links to Home, Projects, Blog and Resume pages which are styled consistently and provide consistent user feedback. 
Header provides a familiar and comfortable navigation experience to users and reassuring feedback when using navigation. Header allows user to reach all areas of site very easily for anywhere on the site.

* [Contact modal](index.html) - triggered by clicking/pressing Contact button that is present at top right of header on all view sizes. 
Modal content starts beneath header and all of page content is covered by grayscale overlay, all page content (except header) is blurred.
Modal is scrollable and cannot be closed by clicking outside modal. 
Modal contains a header: with a 'contact me' title and a 'x' icon button (with scale up hover effect) to dismiss and close the modal which returns user to the page from which the modal was opened. 
Modal contains a body: with a form containing 5 input fields (first name, last name, email, phonenumber and message) which are labelled by placeholder text. First name, last name and email are required fields. There is client-side verification of phone number and email format using regex. 
Form has a submit button which triggers pop-ups next to input fields if requirements of form are not met, or if form meets requirements it triggers a browser alert to confirm form was usbmitted successfully and reloads page that modal was opened from. Sumbit button has a scale up hover effect and a box shadow active effect.
Modal has a footer containing location and email contact information for site owner.
Modal has a responsive layout - positioning of short input fields adjusts from single column on mobile to two column on desktop. Width of message input field increases with viewport width. 

* [Footer](index.html) - fixed height on all pages and view sizes. Dark background and smaller white font used to provide contrast and to visually identify 'aside' information.
Footer contains brief summary of location and copyright information at bottom left (serves as an 'about me'). 
Footer contains recognizable icon links to owner's Medium, GitHub and LinkedIn profiles so user can easily view specific parts of owner's online presence. These links have a background-color transition hover effect.

### Home (landing page) 

* [Hero image section](index.html) - engaging large background image with subtle zoom in transition to encourage a positive first visual impression and emotional response.
Image is styled responsively so that the most important central part of the image is always visible and centered, without stretching or loss of quality on all device sizes. 
Hero image has a responsive jumbotron overlay with a brief headline and large call to action link 'Get to know me' which is anchored to main section of the homepage below.
Call to action provides direction for users who are more generally interested in finding out more about the owner, ratehr than looking for a specific thing. 
Call to action button is bold, has high contrast and scales up noticeably on hover to encourage user action. 
Jumbotron box size and font sizes scale change at specific view port width so that content remains prominent on all device sizes. 
Position, background and color of jumbrotron changes when viewport width reaches orginal width of hero image and starts to zoom. 
Jumbotron is positioned at bottom of hero image on smaller below this point (against darker part of image for contrast) and changes to a speech bubble design at top left of image (with dark text and white background) after this point.
User is drawn intially to jumbotron on all display sizes as a result. 

* [About me heading](index.html) - three bold headlines to provide user with high level, easy to digest information about me. Consistent high contrast colors, styling and layout on all device sizes. 

* [Main sections of homepage](index.html) - this section is anchored from the call to action button in jumbotron above. Provides a brief summary of each of the main areas of the site (projects, blog, resume) and a link to each as a button styled with bold effects similar to the jumbotron CTA button.
Resume subsection also includes a [link to download a pdf](index.html) of my resume so this option is easily accessible on the homepage for any users who have this specific goal. 
Layout of this section changes from three full-width subsections in one column on mobile view, to one fixed-width column with a surrounding border on tablet, to a one row layout with relevant images added and a border around each subsection on larger displays. 
This responsive layout design makes good use of available space and ensures each section in always clearly delineated and easy to find.

### Blog

* [Heading](blog.html) - a full width heading box at the top of page with a title containing relevant icon and contrasting colors. Gives clear feedback to user where they are on the site and what the contents of the page will be. 
* [Main section](blog.html) - contains external links to individual blog posts (open in new tab). Each link is a relevant background image, short summary and title. Each link has a scale up hover effect to provide user with a focus on the post they are considering. 
Layout of links to blog posts is responsive: one column full width with spacing horizonal dividers on mobile view; 2 column with a border around each link and space around each link on small tablets, 3 column on large tablets and 4 column on desktop. 
User is able to comfortably browse all blog post topics and select to open those in which thet are interested. 

### Projects

* [Heading](projects.html) - a full width heading box at the top of page with a title containing relevant icon and contrasting colors. Gives clear feedback to user where they are on the site and what the contents of the page will be. 
* [Main section](projects.html) - contains external links to individual project repositories (open in new tab). Each link is a relevant background image, short summary and title. Each link has a scale up hover effect to provide user with a focus on the project they are considering. 
Layout of links to projects is responsive: one column full width with spacing horizonal dividers on mobile view; 2 column with a border around each link and space around each link on small tablets, 3 column on large tablets and 4 column on desktop. 
User is able to comfortably browse all of owner's projects and select to open those in which thet are interested. 

### Resume

* ['Executive summary' heading](resume.html) - three bold headlines to provide user with further high level, easy to digest information about me; since if they have navigated to this page they are interested in my credentials.Consistent high contrast colors, styling and layout on all device sizes. 
* ['Download my resume' link](resume.html) (as on homepage) clearly positioned near top of page and easily accessible for any users who require my resume in this format. 
* [Work history section and qualification sections](resume.html) provide clear and concise dates, employer information and descriptions of roles in a reverse-chronological timeline format so users can easily digest information. 
Each section of page (work history, qualifications, skills, about me) has a full width heading box at the top of page with a title containing relevant icon and consistent, contrasting colors. Gives clear feedback to user to find information on the page.
Information is prioritzed and easy for user to find: educational qualifications are displayed first followed by a summary of owner's skills and knowledge of specific technologies as a software developer and a more casual 'about me' section conatining owner's interests, hobbies and achievements and a consistent avatar image displayed.
Sections have a responsive layout to maximize use of available horizontal space and provide more information on viewport where possible. All sections are full width, single column and stacked vertically on mobile views. The employment and qualification sections change to a two column layout on tablet views (each with a border) while skills and about me sections remain full width (but the arrangment of elements within these sections changes to accommodate extra space).
On desktop views the skills section becomes an extra column adjacent to the employments and qualifications section while the about me section remains full width at the bottom of the page (since it has lowest priority).   

### Styling

All pages

* Color codes

    * F5F5F5 cultured
    * 0e1c36 oxford blue
    * 9f7e69 beaver

* Font pairing

    * Headings: Lato (400,700)
    * Body: Roberto (400, 300)

### Features left to implement in future:

* Internal blog post pages - instead of linking to an external site which hosts blog posts, store each blog post as a .html file within the site directories. 
Not worth doing yet as owner has not begun blogging! 
* Implement backend script and database for storing form responses or add functionality to send an email to the owner via a form on the site. Beyond scope of course - requires greater knowledge of http requests and how to set up a database. 
* Improve user feedback when using submit button on form to change color and content to processing then sent as form is submitted - requires Javascript. 
* Add a icon to go to top of page which appears after scrolling down a certain distance from top - requires JavaScript.


## Technologies Used

* HTML5 and CSS3 languages. JavaScript libraries used.
* [Chrome developer tools](https://developers.google.com/web/tools/chrome-devtools) to manipulate DOM, test code changes and responsivity of site.
* [Gitpod](https://www.gitpod.io/) cloud-based development environment to code website and organise directory structure of project. 
* [Bootstrap](https://getbootstrap.com/) framework used to provide component and utility classes to help code certain features and style certain elements more efficiently.
* [FontAwesome](https://fontawesome.com/) to provide font icons across site
* [BootstapCDN by Stackpath](https://www.bootstrapcdn.com/) used to integrate Bootstrap and FontAwesome into project
* [Google fonts](https://fonts.google.com/) to obtain webfonts used in project
* [AutoPrefixer](https://autoprefixer.github.io/) used to add required prefixed to ensure css code is valid for previous 4 versions of browsers.
* [Coolors - color picker](coolors.co) used to select combination of primary, secondary and tertiary color used across site ensuring good contrast and tasteful style.
* [pixlr -image editing software](https://pixlr.com/) used to resize and crop images used in project
* [W3 HTML validator](https://validator.w3.org/) used to ensure code in HTML files is valid
* [W3 Jigsaw CSS validator](https://jigsaw.w3.org/css-validator/) used to ensure code in style.css file is valid
* [jQuery](https://jquery.com/) JavaScript library used by Bootstrap for opening/closing modal contact form and toggling dropdown navigation menu from header
* [popper.js](https://popper.js.org/) JavaScript library used by Bootstrap for toggling dropdown navigation menu from header.
* [Balsamiq](https://balsamiq.com/) used to create wireframes.
* [HEX/RGB converter tool](https://www.webfx.com/web-design/hex-to-rgb/) used to quickly convert between HEX and RGB color codes.

## Testing

[Link to TESTING.md file]("TESTING.md")

## Deployment

### Deployment to GitHub pages

1. Go to the [GitHub repo](https://github.com/thaysom22/portfolio_project) for this project.
2. Under **Settings** tab, scroll to **GitHub Pages** section.
3. Under **Source** select **master** branch and **/ (root)** from dropdown menus. 
4. Click **Save** - the site will be built and the page will be refreshed.
5. Scroll down to find the [url for live site](https://thaysom22.github.io/portfolio_project/). 

### Local Deployment by cloning from GitHub

1. Go to the [GitHub repo](https://github.com/thaysom22/portfolio_project) for this project.
2. Ensure **master** branch is displayed in top left dropdown menu.
3. Under **Code** dropdown menu, select **HTTPS** and copy the **web URL**. 
4. Open Terminal
5. Change current working directory to the location where location of cloned directory is required.
6. Enter `git clone` followed by pasted **web URL**:

`git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY`

7. Local clone of repository is created.

## Credits and acknowledgements

### Content

* All text content was created by myself, the site owner. 
* Font icons taken from [FontAwesome](https://fontawesome.com/).

### Media

* 'TH DEV' logo in header was created by owner
* All images used on site used were taken from [unsplash.com](https://unsplash.com/)

### Code

**CREDITS also provided in code comments**

* Responsive and collapsable navbar, toggled dropdown navigation menu, modal structure and functionality, responsive layout of sections - code adapted from templates provided in [Bootstrap documentation](https://getbootstrap.com/)
* Regex used for validation in pattern attribute value of form copied and adapted from [regular-expressions.info](https://www.regular-expressions.info/email.html)
* Custom Javascript function written into html to excecute when modal form in submitted and trigger browser alert copied and adapted from [W3schools code snippet](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_ev_onsubmit)
* CSS for hover and focus state transitions and transforms copied from [hover.css repository](https://github.com/IanLunn/Hover) and adapted. 

### Acknowledgements

* StackOverflow - invaluable source of support and ideas when searching for answers to specific implementation questions or problems.
* Slack community - used to ask questions about project.
* Mentor - Kyeza Arnold: suggested and encouraged the initial idea of a personal portoflio website project. He also suggested changing the header positioning to fixed at the top of the viewport and adding an alert when contact form is submitted. 
* Code Institute template for README used as guide to structure this README.
* [appledeveloper.com docs](https://developer.apple.com/library/archive/documentation/DeviceInformation/Reference/iOSDeviceCompatibility/Displays/Displays.html) used to find out display sizes and pixel ratios of common iOS devices.
* [W3schools](https://w3schools.com) used as reference for HTML elements and attributes
* [Bootstrap documentation](https://getbootstrap.com/) used as reference when adding classes defined in bootstrap .css files.
* [CSS Visual reference](https://cssreference.io/) used as reference for css properties and values.
* [GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository) for guidance on how to clone a repository locally using CLI.
* [AJGreaves README](https://github.com/AJGreaves/portrait-artist) used to help structure and guide README.md and TESTING.md contents.