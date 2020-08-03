<h1 align = "center"> Lets Keep Running<h1>

## Milestone 1 Project: User Centric Frontend Development by Martin Johnson

[View the live project here.](https://martinjohnson26.github.io/Milestone1/)

This is a fictious running club designed to attract B2C users to join up and use the training plans on offer.

## User experience (UX)

To create a stand alone website for a fictious running club providing training plans for runners of all abilities for a 
range of different running events.

-   ### User Stories

    -   #### First Time users

        1. Easily navigate around the site to view the content.
        2. Quickly understandstand the purpose of the site.
        3. Read testimonials which support reasons why potential users should join the club.

    -   #### Returning users

        1.  A simple and easy sign up process.
        2.  Easy access to the training plans.
        3.  Access to other supporting running organisations.
        
    -   #### Frequent users

        1.  Check to see if any additional and/or new training plans have been added.
        2.  Add their own testimonials.
        3.  Add their photos to the gallery images.

    ### Strategy

    To create a simple and attractive site for runners of all levels of ability and offer
    an opportunity to join the club and use the training plans provided

    ### Scope

    To provide a brief history of the club , supported by member testimonials. To display a
    selection of training plans, links to associate running clubs and a members gallery.

    ### Structure

    The site is designed to provide an instant opportunity to join the club from the landing
    page. The site is easily navigated from the Navigation menu at the top of the page.

    ### Skelton

    The initial design layout was created using Figma.

    ### Surface

    An image of runners was chosen for the landing page , with a opacity added to
    enable the text to be more visible.

## Design

-   ### Initial Design

    Figma was used fodesign r initial design layout. This can be view by clicking the link below

    (https://github.com/martinjohnson26/Milestone1/blob/master/assets/readmeimages/wireframe-milestone1.pdf)

-   ### Colour scheme

    The predominate colours are Grey and Whitesmoke. The Grey was selected as it was felt that it blended well with the 
    background colours hero image and the whitesmoke background enhanced the grey text.

-   ### Typography

    Roboto was selected as the chosen font for the site as it displays a clear and easily readable text. Sans Serif has been
    selected as the fallback text should the main font fail to import correctly for any reason.

-   ### Images

    The Hero image has been selected to show a mass participation running event with the site call-out overlayed on top .

##  Technologies used

1.  HTML - For the basic site code. (https://en.wikipedia.org/wiki/HTML5)
2.  CSS - For styling. (https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
3.  Bootstrap - For additional styling, responsiveness, layout(grids) and modal function(sign up form).(https://getbootstrap.com/docs/4.4/getting-started/introduction/)
4.  GitPod - For version control and commiting to GitHub.(https://www.gitpod.io/)
5.  GitHub - For the repository to store the pushed code. (https://github.com/)


## Features

**Navigation Bar :** Allows users to navigate to all sections of the site in a simply manner
and return to the Home page from any page.

**Hero Image :** The Hero image shows a running event with a zoom effect , additionally a call to action button invites users
to join the club immediately.

**About and Testimonial sections:** Provides a brief summary about the formation of the club and its running ideologies. The testimonials display positive feedback from members.

**Plans:** This displays the six race type plans avaialable and provides users with a brief summary about the plans.

**Sign Up Modal:** A modal pop up box is triggered when a user clicks on the sign up button to
allow them to enter personal details and sign up to the club.

**Clubs:** Provides working links to running based websites.

**Gallery:** Displays members images. These were sourced from Unsplash , a free useable image site (https://unsplash.com/)

**Footer:** Displays club address and contact number and links to social media sites.

## Future Implimentations

Connect modal pop-up to a live database to capture new user details.

Add a sign in function / button with validation to check whether users are current members.

Add functionality to allow plans to be ordered. (Order Button to be added).

Updates as to when new plans have been added.

Ability to add testimonials.

Ability to add images.

## Testing

W3C Markup Validator and W3C CSS Validator Services have been used to validate all code of the project ensuring
no syntax errors were found.

[W3C Markup Validator](https://github.com/martinjohnson26/Milestone1/blob/master/assets/readmeimages/indexhtml.png) - Result = No errors found. One Warning Message

    The warning relates to a date input type being used that may not be supported in all browsers

[W3C CSS Validator](https://github.com/martinjohnson26/Milestone1/blob/master/assets/readmeimages/stylecss.png) - Result = No errors found.
 
Chrome Dev Tools 
    For testing mobile and tablet views and responsiveness, CSS styling changes before implementing it in the code and 
    Network to assess whether it was picking up Javascript.

 ### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. Easily navigate around the site to view the content.

         Users are presented an easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Text and a "Sign Up" Call to action button.
        The user can easily navigate around the site by using the navigation bar or by scrolling up and down
        
    2. Quickly understandstand the purpose of the site.

        There is a Hero Image with text and a "Sign Up" Call to action button.
        The first section of the site explains the ethos of the club and its ideologies.
        The training plans are clearly presented and catagorised by runner ability.

    3. Read testimonials which support reasons why potential users should join the club.

        The testimonials provide positive feedback from members about the site and the training plans provided
        The sign up button is clearly presented to the user on the Home page.

-   #### Returning Visitor Goals

    1. A simple and easy sign up process.

       The sign up button is clearly presented to the user on the Home page.
       The sign up button quickly displays a pop-up join form.
       The form requests basic information with prompts in the required fields.

    2. Easy to view descriptive summaries of the training plans.

        The plans are easily accessed by clicking on the plans link or scrolling to the page.
        Individual distance/ race type plans are viewed by selecting the tab displaying the corresponding name.
        Each plan gives a brief description of what the plans are about without revealing the full content of each plan.
        This intentional with the aim to entice the user to join the club and get full access to the plans

    3. Access to other supporting running organisations.
       
       Links to support running clubs are easily accessed by clicking on the clubs link or scrolling to the page
       Each link opens on a new page 

-   #### Frequent User Goals

    1. Check to see if any additional and/or new training plans have been added.

        This function has not been added to the site

    2. Add their own testimonials.

        This function has not been added to the site

    3. Add their photos to the gallery images.

        This function has not been added to the site

## Bugs and issues

An issue with the modal pop up effecting the layout on mobile devices was found during the design stage. This appeared to be due to the modal coding being placed inside a code section.
Once the modal coding was placed outside of the screen layout code the issue was resolved.
On mobile devices the Nav Bar pop up menu obscured some headings when the links where selected. This was resolved by reveiwing the Bootstrap 
coding relating to NavBars and add a navbar-collapse class to the appropriate div element.
The project failed its first submission due to the navbar not working correctly and issues with horizontal scrolling.
The navbar issue was attributed to a typo spelling error in a class name which made the NavBar non operational.
The scrolling issue was attributed to some div elements having a class of container and others container-fluid. Both issues have been corrected
The initial submission also had a list of training plans that were selected by radio buttons but gave no information about the plans.
This was subsequently removed and replaced with a tabular format which provides more information to the user.
The user gallery had images that had not been attributed to the provider. This has now been corrected

## Deployment

The site is hosted in a GitHub repository
The URL for the site is https://martinjohnson26.github.io/Milestone1/

The site was developed on GitPod and changes regularly committed to GitHub's repository
using one main master branch

## Credits

**Content:** The inspiration for the site came from my own passion for running and transition from novice runner to a sub 2 hour Half marathoner.
The code has been written by myself with the exception of the Modal function and the Tabbed Menu. The core design and layout were copied from
 https://www.w3schools.com/bootstrap4/tryit.asp?filename=trybs_modal&stacked=h
 https://www.w3schools.com/bootstrap4/tryit.asp?filename=trybs_nav_tabs&stacked=h
and modified by myself to meet the needs of the site.
The Code Institute Love Running and Rosie CV lesson were referenced and used to assist with the layout of the Gallery and the Footer section
Social Media links

**Media**  
 Icons were sourced from FontAwesome  (https://fontawesome.com)

Images were sourced from Unsplash , a free useable image site (https://unsplash.com/)

Fonts were sourced from Google Fonts (https://fonts.google.com/)

**Acknowledgements**

https://www.w3schools.com/bootstrap4/ For use of built in class definitions , examples and Try Me Code snippets

Slack community for support and advice during the construction of the site

Code Institute tutors for support and advice during the construction of the site

Code Institute coursework for reference

Code Institute for sample README file , which was used as a base template for thie README file

Oluwafemi Medale (CI Mentor) For help, support, advice and positive feedback from the initail inception of the site through to completion
