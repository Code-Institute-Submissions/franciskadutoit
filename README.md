# Franciska Du Toit Personal Website & Portfolio

A personal website to showcase the resume and portfolio of Franciska Du Toit based in Ireland. The purpose of the website is to give future employers a better look into the personality, achievements and projects of the individual. It is important in the technology field that people can see what a designer and developer can do, what their process is and what they can show for it at the end of the project. Therefore a personal profile and portfolio website is vital to connect with the user and also have a central place of information about Franciska Du Toit.  

The main goals of this site? 
* To promote the brand of Franciska Du Toit
* To attract attention from recruiters
* To inspire other people 
* To showcase portfolio of work
* A way to contact Franciska Du Toit

## UX
### User Persona
This website is for users interested in information about Franciska Du Toit including employers and recruiters to get more insights to what skills the individual has, examples of those skills and also to understand who the individual is as a person. 

### Who are we building it for?
* Recruiters
* Potential employers
* Potential followers/observers

### What are the goals & needs of the user?
* Easily find information on the individual
* Get a full picture of the individual and the types of projects they are / want to be involved in
* To see a body of work done by the individual

### What are the goals & needs of the designer & developer?
* Showcase process and quality of projects 
* Building brand awareness 
* Attract attention from prospective employers, recruiters or entities to work with

### User Stories

* As a recruiter, I want to see some background information of Franciska Du Toit, so that I can understand if she will be a good fit with an organisation.
* As a recruiter, I want to see Franciska Du Toit’s portfolio of projects, so that I can see and understand her process when taking on a project.
* As a recruiter, I want to see Franciska Du Toit’s CV, so that I can view her previous experience and qualifications
* As a new visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.
* As a new visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.
* As a new visitor to the website, I want learn more about Franciska Du Toit, so I can feel that I understand her purpose and what she stands for
* As an interested follower and observer, I want to follow Franciska Du Toit on social media, so I can keep up with her latest news.

### Wireframe mockups: 
- [Home](assets/wireframes/Home_Page_Wireframe.png)
- [Portfolio](assets/wireframes/Portfolio_Page_Wireframe.png)
- [About](assets/wireframes/About_Page_Wireframe.png)
- [Contact](assets/wireframes/Contact_Page_Wireframe.png)

## Features

Each page features a responsive **navigation bar** at the top with conventional placing of **logo** (top left)
* There is a mobile-first focus and therefore I wanted to keep in mind first what will work on mobile. 
* For Mobile - Hamburger menu so that the screen does not look to crowded. The menu would collaps when tapped.
* For Tablet - I decided to have the full menu navigation bar at the top of the screen as there is more space on a tablet 
* For Desktop - Full navigation menu at the top of the main menu items: Home, Portfolio, About and Contact
Each page has a **footer** with **social media icons** linking to 4 Franciska Du Toit’s social media pages.
Each page features a hero image. On mobile and tablet devices the static hero image is at the top with the text at the bottom. On desktops the static hero image moves to the left and takes up 50% of the page. The content takes up 50% on the other side of the screen.

### Home
There is a **call to action button** to take the user directly to the **About page**.
There are 4 **list items** to give a short overview of who Franciska Du Toit is.

### Portfolio
The Portfolio page has 4 **sub-menu items** laid out in **columns**, 2 columns wide for all devices.
Each item is square which is animated by using a hover effect that will sweep down when the user’s mouse hover over them. 
Each item can be clicked to take the user to the respective submenu item pages.

### About
The About page includes copy about the Franciska Du Toit.
The page also has a list with 5 **project list items** which if clicked will reveal more information on the project. 
There is also a **call to action button** to guide the user to see all the projects by Franciska Du Toit
There is also a feature on Franciska Du Toit’s qualifications which has 2 sections for In Progress which only has 1 list item and Completed which has 4 list items.
Lastly, there is also a download icon to indicate to the user that they can download a pdf version of her CV. There is then a link to the pdf document for the user to make it more convenient to read or print.

### Contact
The Contact page features a **contact form**, which requests client name and email, subject line, and a box for the main message. 
The bottom of the form contains a **Send Button**
At the bottom of the form, clients can click on the button to send a **message via LinkedIn**.

 
### Existing Features
#### Header
- Logo - Features on all the pages and allows the user to easily recognise the brand of Franciska Du Toit. If the user clicks on the logo, it will return the users to the home page as they would expect.
- Navigation Bar - Features on all the pages and allows the user to easily navigate the website's pages and find what they are looking for with ease and speed.

#### Footer 
- Social Icons - Features on all the pages and allows the user to access the social platforms that Franciska Du Toit uses.

#### Specific Pages
- [Home Page](index.html) - Allows the user to see a quick snapshot of who is Franciska Du Toit
- [Portfolio Page](portfolio.html) - Allows the user to see a high level page to navigate them to specific projects in her portfolio
- [About Page](about.html) - Allows the user to connect with Franciska Du Toit by providing a snapshot of information of her CV but also providing the option to download a more detailed pdf version.
- [Contact Form](contact.html) - Allows the user to get in contact or ask questions in two ways: by entering the form or connecting to LinkedIn.

### Features Left to Implement
- A blog/ Articles - Allows the user to see some articles written by the Franciska Du Toit establishing her as a thought leader. - she currently doesn't have time to write a blog


## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- This project uses HTML and CSS programming languages
- BootstrapCDN
--The project uses Bootstrap4 to simplify the structure of the website and make the website responsive easily.
--The project also uses BootstrapCDN to provide icons from FontAwesome

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for this website was created by Franciska Du Toit

### Media
- All the photos used in this site were obtained from Franciska Du Toit

### Code
- HTML originally taken from ...
- CSS originally taken from...

### Acknowledgements

- I received inspiration for this project from X
I received inspiration for this project from my own experience of building and maintaining a WordPress website for my personal website for the past few years.