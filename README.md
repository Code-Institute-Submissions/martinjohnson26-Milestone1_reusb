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
4.  Figma - For initial design layout. (https://www.figma.com/)
5.  GitPod - For version control and commiting to GitHub.(https://www.gitpod.io/)
6.  GitHub - For the repository to store the pushed code. (https://github.com/)

## Features

**Navigation Bar :** Allows users to navigate to all sections of the site in a simply manner
and return to the Home page from any page.

**Hero Image :** The Hero image shows a running event with a zoom effect , additionally a call to action button invites users
to join the club immediately.

**About and Testimonial sections:** Provides a brief summary about the formation of the club and its running ideologies. The testimonials display positive feedback from members.

**Plans:** This displays another call to action button to invite users to join the site.
and a selection of training plans that are selected via check boxes.

**Sign Up Modal:** A modal pop up box is triggered when a user clicks on either sign up button to
allow them to enter personal details and sign up to the club.

**Clubs:** Provides working links to running based websites.

**Gallery:** Displays members images.

**Footer:** Displays club address and contact number and linkds to social media sites.

## Future Implimentations

Connect modal pop-up to a live database to capture new user details.

Add a sign in function / button with validation to check whether users are current members.

Add functionality to restrict non members from selecting plans.

Add functionality to allow plans to be ordered. (Order Button to be added).

Updates as to when new plans have been added.

Ability to add testimonials.

Ability to add images.

## Testing

W3C Markup Validator and W3C CSS Validator Services have been used to validate all code of the project ensuring
no syntax errors were found.

[W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - Result = No errors found. 

  Warning messages :
   The document is not mappable to XML 1.0 due to two consecutive hyphens in a comments .

[W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - Result = No errors found.
 
  Four warning messages :

   Imported style sheets are not checked in direct input and file upload modes

moz-transition is an unknown vendor extension.

 webkit-transition is an unknown vendor extension

o-transition is an unknown vendor extension

Chrome Dev Tools 

   For testing mobile and tablet views and responsiveness

   CSS styling changes before implementing it in the code
   
   Network to assess whether it was picking up Javascript

 ### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. Easily navigate around the site to view the content.

         Users are presented an easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Text and a "Learn More" Call to action button.
        The user can easily navigate around the site by using the navigation bar or by scrolling up and down
        
    2. Quickly understandstand the purpose of the site.

        There is a Hero Image with text and a "sign up" Call to action button.
        The first section of the site explains the ethos of the club and its ideologies.
        The training plans are clearly presented and catagorised by runner ability.

    3. Read testimonials which support reasons why potential users should join the club.

        The testimonials provide positive feedback from members about the site and the training plans provided
        The sign up button is clearly presented to the user on the Home page.

-   #### Returning Visitor Goals

    1. A simple and easy sign up process.

       The sign up button is clearly presented to the user on the Home page.
       The sign up button quickly displays a pop-up join form
       The form requests basic information with prompts in the required fields

    2. Easy access to the training plans.

        The plans are easily accessed by clicking on the plans link or scrolling to the page
        Individual plans are selected by checking the required box
        There is no restriction on the number of plans that can be ordered

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
The site was initailly slow to load and was improved by moving the Gallery section to a new file (gallery.html).
On mobile devices the Nav Bar pop up menu obscures some headings when the links are selected. further investigation is required but timeframes for project submission have not allowed this

## Deployment

The site is hosted in a GitHub repository
The URL for the site is https://martinjohnson26.github.io/Milestone1/

The site was developed on GitPod and changes regularly committed to GitHub's repository
using one main master branch

## Credits

**Content:** The inspiration for the site came from my own passion for running and transition from novice runner to a sub 2 hour Half marathoner.
The code has been written by myself with the exception of the Modal function. This was copied from https://www.w3schools.com/bootstrap4/tryit.asp?filename=trybs_modal&stacked=h
and modified by myself to meet the needs of the site

**Media**  
 Icons were sourced from FontAwesome  (https://fontawesome.com)

Images were sourced from Unsplash , a free useable image site (https://unsplash.com/)

Fonts were sourced from Google Fonts (https://fonts.google.com/)

**Acknowledgements**

https://www.w3schools.com/bootstrap4/ For use of built in class definitions , examples and Try Me Code snippets

Slack community for support and advice during the construction of the site

Code Institute tutors for support and advice during the construction of the site

Code Institute coursework for reference

Oluwafemi Medale (CI Mentor) For help, support, advice and positive feedback from the initail inception of the site through to completion
