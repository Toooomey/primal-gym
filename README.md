# Primal Gym Portfolio

## User Centric Frontend Development

![Mockup](https://i3.lensdump.com/i/gNcAED.png)

## [Live Webite - Github Pages](https://toooomey.github.io/primal-gym/)

This website is to showcase a fictional local gym based in Llandaff Fields, looking to gain exposure and
attract new members to the club while providing users details of the facilities available.

The main aim is to build an HTML and CSS based website, incorporating the use of Boostrap in certain elements, which is responsive and easy to use. This is for 
the User Centric Frontend Development Project.

---

# Table of contents

- [UX](#ux)
    - [User goals](#user-goals)
        - [New user goals](#new-user-goals)
        - [Returning user goals](#returning-user-goals)
    - [User stories](#user-stories)
    - [Structure of the website](#structure-of-the-website)
    - [Wireframes](#wireframes)
    - [Design](#design)
- [Features](#features)
- [Testing](#testing)
    - [Functionality testing](#functionality-testing)
    - [Compatibility testing](#compatibility-testing)
    - [Code Validation](#code-validation)
    - [User stories testing](#user-stories-testing)
    - [Issues found during site development](#issues-found-during-site-development)
    - [Performance testing](#performance-testing)
- [Deployment](#deployment)
- [Credits](#credits)


# UX

## User goals

### New user goals:
- user is able to find information about facilties offered.
- user is able to find out what classes are available.
- user is able to find out location of gym.
- user is able to find out opening times
- user is able to find out how to contact gym.
- user is able to find the gyms social media links.

### Returning user goals:
- user is able to check class timetables.
- user is able to check any updates on opening hours.
- user is able to contact gym through phone, email or social media.

## User stories

### As a new customer:
* I want to be able to discover what are the opening hours.
* I want to find out what equipment the gym currently has.
* I want to find out what time classes are available.
* I want to be able to easily contact the gym should I need to.

### As a returning customer:

* I want to be able to check class timetables.
* I want to be able to check the opening hours of the gym.
* I would like to be able to view the location of the gym.

## Structure of the website

The Primal Gym website is meant to be a responsive website that displays well and is easy to use across all media screen sizes.
The site consists of a home page, gallery, classes, and contact page. The links are clearly labelled and are direct users to the content
they would like to view.

## Wireframes

To create the site wireframes I used the software Balsamiq.

![Wireframes](https://i1.lensdump.com/i/gNwwz3.png)

## Design

### Colors
* The Main colours used in the project were black, white and red.

### Fonts 

* As a main font I used Sans-serif and for the alternate font for the Headers I used Roboto.

### Images

* I used images from [Unsplash.com](www.unsplash.com) These are given credit in the [credits](#credits) section.


[Back to Table of contents](#table-of-contents)
___
# Features

This website is responsive across all devices. Website displays class information, opening hours, galleries and contact information.
___
# Technologies used

### HTML5
* As a structure language.

### CSS
* As a style language.

### Bootstrap 
* Bootstrap@4.5.3 as a CSS framework to keep responsive, mobile first aproach.

### Font Awesome
* As an icon library for a social links.

### Google fonts
* As a font resource.

### GitHub
* As a software hosting platform to keep project in a remote location.

### Git
* As a version-control system tracking.

### Gitpod
* As a development hosting platform.

### Wireframe.cc
* As a wireframing tool.

### GNU Image Manipulation Program [GIMP]
* As an image editor.


[Back to Table of contents](#table-of-contents)

___
# Testing

## Functionality testing 

 I used Mozilla web developer tools and Chrome developer tools throughout the project for testing and solving problems with responsiveness and style issues.
 
 [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) extension to chrome browser was very helpful.


## Compatibility testing
 Site was tested across multiple virtual mobile devices and browsers. I checked all supported devices in both Mozilla web developer tolls and Chrome developer tools. 
 
 I tested on hardware devices such as: Lenovo ideapad with Ubuntu and Windows OS's, Lenovo smartphone with Android 7, Google pixel 3 with Android 11.


## User stories testing

### As a business owner:

- I would like to present myself and my offer on the website clearly to potential customers.
    > Name, photo of the instructor and top skills are on each page in portfolio section. Career path section at home page provides more details.

- I need to make sure that my current and new customers will find a professional help with their diets, personal or group trainings.
    > Customers can achieve this by contacting through contact form. They can choose interesting topic and describe their needs in a message box.

- I want my customers to be able to learn how to use my website intuitively and easily.
    > Each site has a fixed navigation menu and is accessible at all times. All content is presented with minimalistic approach.

- I would like to build and maintain relationship with potential and current customers.
    > Customers are able to find a links to social channels at the bottom of each page. Alternatively they can contact by email or contact form.


### As a new customer:
- wish to find information about personal trainer and check her/his qualifications.
    > User can see essential description on the home page. More information can be find in about page.

- I would like to contact with a diet coach to change my eating habits and start healthy lifestyle.
    > User can find a contact form in contact page. Alternatively can use an email. Email address if located in a footer the bottom of each page.

- I want to join in a fitness group with professional trainer, to find motivation and spend time actively.
    > Brief class description of fitness group classes can be find on the home page below career path section. Offer site provides more detailed description. Frome there user can click contact us button and send a message to the traier.

### As a returning customer:
- I need to contact my diet coach to reschedule my meeting.
    > User can find a contact form in contact page. Alternatively can use social channels or email.

- I would like to check timetable for current days and times for a group trainings.
    > Each site has time table at the bottom of the page.

- I want to show my friend a location of the fitness studio where we can join for a semi private personal training.
    > Each page contains location information in a footer. Users are able to find a location map in contact page.


---
## Issues found during site development

* #### Horizontal scrolling bar on the bottom of the screen.
![testing_issue_1](testing/testing_issue_1.png)

I used [grid markup](https://getbootstrap.com/docs/4.5/components/card/#header-and-footer)
to create two sepereate collumns. To achieve this I had to use *.row* in first *div* element and *.col-sm-6* in the second *div* element.
After that I found that horizontal scrolling bar appear on the bottom of the screen.
Using mozilla developer tools I noticed that by default class *.row* has *margin-right: -15px;* and *margin-left: -15px;*

To fix this I created new class *.no-row-margin* and set both margins to 0px.

> After I gain more experience with bootstrap I found that I could achive this by [no-gutters](https://getbootstrap.com/docs/4.0/layout/grid/#no-gutters) class.

> I read bootstrap documentation about [Spacing](https://getbootstrap.com/docs/4.0/utilities/spacing/) and I decided to use predefined classes for paddings and margins in the project.
By doing this I think my code looks cleaner and will be easier to understand by other developers.


* #### Ipad screen compatibility

I found a bugs on Ipad screens. I would like to keep years dates just above the stars, but they were shifted.

![testing_issue_2](testing/testing_ipad_screen.png)

I had to create a block element with a class "ipad-screen" and non-breaking space element inside a block element.
In CSS file I had to create @media rule that will show this block element on Ipad displays only.

>}
@media screen and (max-width: 991px) and (min-width: 0px),(min-width:1200px){
    .ipad-screen {
    display: none;
}
}

![bug_solutino1](testing/bug_solution1.png)

![bug_solutino2](testing/bug_solution2.png)

## Performance testing

I run [Lighthouse](https://developers.google.com/web/tools/lighthouse/) tool to check performance of the website.
I had to do couple of changes to improve performance. Screenshots are presented below:

![bug_performance1](testing/performance1.png)
![bug_performance2](testing/performance2.png)

Final results:
![performance_final](testing/performance_final.png)
I noticed that this tests scores vary from time to time and depends on external libraries as well. 



## Code Validation
 At the and of the project I used two websites to validate a code
 
 * [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to validate CSS
 * [Nu Html Checker](https://validator.w3.org/) to test HTML


[Back to Table of contents](#table-of-contents)

___
# Deployment

The project was deployed on GitHub Pages. I used Gitpod as a development environment where I commited all changes to git version control system.
I used push command in Gitpod to save changes into GitHub.

To deploy a project I had to:

* Log in to GitHub and click on repository to deploy ([MP1](https://github.com/marcin-kli/MP1))
* select `Settings` and find GitHub Pages section at the very bottom of the page
* from source select `none` and then `Milestone-Projects` branch.
* click `save` and page was deployed after auto-refresh.
>  Your site is published at https://marcin-kli.github.io/MP1/

To run localy:
* Log in to GitHub and click on repository to download ([MP1](https://github.com/marcin-kli/MP1))
* select `Code` and click Download the ZIP file.
* after download you can extract the file and use it in your local environment 

Alternatively you can [Clone](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
or [Fork](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo)
this repository ([MP1](https://github.com/marcin-kli/MP1)) into your github account.

[Back to Table of contents](#table-of-contents)
___
# Credits


* To complete this project I used Code Institute student template: [gitpod full template](https://github.com/Code-Institute-Org/gitpod-full-template)

* Ideas and knowledge library:

    * [w3schools.com](https://www.w3schools.com)

    * [css-tricks.com](https://css-tricks.com/)

    * [getbootstrap.com/docs](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
        I used code for navbar, jumbotron and card from Bootstrap.

### Code

* Links transition: [CSS transition Property](https://www.w3schools.com/cssref/css3_pr_transition.asp)
* Bootstrap: [Kitchen sink](https://getbootstrap.com/docs/4.0/components/card/#kitchen-sink)
* Bootstrap: [Burger menu](https://getbootstrap.com/docs/4.5/components/navbar/#text)
* Bootstrap: [Jumbotron](https://getbootstrap.com/docs/4.5/components/jumbotron/)
* Bootstrap: [Form](https://getbootstrap.com/docs/4.5/components/forms/)
### Content:
*  General content:  [fitlife.ie](http://fitlife.ie/lessons-its-your-life-your-fit-life/)

### Map location:
* [fitlife.ie](http://fitlife.ie/)

### Map:
* [Google maps](https://www.google.com/maps?ll=52.059441,-9.511501&z=16&t=m&hl=en-US&gl=US&mapclient=embed&cid=7306226195280410511)

### Images:

#### Unsplash.com:
* [annie-spratt--l-eemJU0vE-unsplash.jpg](https://unsplash.com/photos/-l-eemJU0vE)

* [ziphaus-SZ40Lbw1P5o-unsplash.jpg](https://unsplash.com/photos/SZ40Lbw1P5o)

* [bruce-mars-y0SMHt74yqc-unsplash.jpg](https://unsplash.com/photos/y0SMHt74yqc)

* [luis-quintero-EPrjIYQrpkU-unsplash.jpg](https://unsplash.com/photos/EPrjIYQrpkU)

* [sven-scheuermeier-saGbrA6s8g0-unsplash.jpg](https://unsplash.com/photos/saGbrA6s8g0)


[Back to Table of contents](#table-of-contents)
___
