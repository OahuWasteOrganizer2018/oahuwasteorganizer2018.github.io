# Table of contents

* [About Oahu Waste Organizer 2018](#about)
* [Installation](#installation)
* [Development history](#development-history)
  * [Milestone 1: Mockup development](#milestone-1-mockup-development)
*[User Guide] (#user-guide)

## About
Currently, trash audits across UH campuses have a very primitive way of storing and calculating data. It consists of a single piece of paper and one very hard working individual. One representative is in search of a more streamlined solution of storing the data.

Our solution to this problem is to create a user-friendly web application that utilizes intuitive design to streamline data input and visualization. In other words, make trash data more pretty!

Our final project consists of members Alton Lee, Emily Pang, and Jake Weber. Our project is inspired by our HACC team consisting of Leighton Villanueva, Alton Lee, Emily Pang, Jake Weber, Nicholas Lum, Ethan Chow, Jordan Ooka, Cristian Aspacio, and Ty Uehara.

## Installation
To begin, <a href="https://www.meteor.com/install">install Meteor</a>.

Then, download <a href="https://github.com/oahu-waste-organizer/oahu-waste-organizer">OWO</a>.  You will have to request permission from the author since it is a private repository.

Then cd into the app directory and install the libraries with:
<div class="highlight">
<code>$ meteor npm install
</code>
</div>

After the libraries have been installed, run the app using:
<div class="highlight">
<code>$ meteor npm run start
</code>
</div>

You many also have to install Highcharts.js, run the app using:
<div class="highlight">
<code>$ npm install highcharts-react-official
</code>
</div>

If done correctly, some default users and data will be created. 

You can then open up <a href="http://localhost:3000/#/">http://localhost:3000</a> to view the template application and can log in using the credentials in <a href="https://github.com/ics-software-engineering/meteor-application-template-react/blob/master/config/settings.development.json">settings.development.json</a>.

## Development History
You can view a live deployment here: http://owo.meteorapp.com/

### Milestone 1 Mockup Development

A page idea we could use is a form that simplifies trash input that any logged in user can add. Bags and Categories can be added as needed. Our home page is accessible to the general public and contains information and data of previous years of trash auditing. The home page also links to a heat map of the different campuses and how much trash each building produces on each campus.

![mockup landing page and login](/images/landing-page.jpg)

The input form will imitate the paper excel sheet used at the UH trash audits.

![mockup input form page](/images/input-form.png)

## User Guide

When users first go to the Oahu Waste Organizer website (found at http://owo.meteorapp.com), they are greeted with the home page.

![](images/landing.PNG)

In the events tab, anyone is free scroll through the list of upcoming and previous events, and choose to view the information of each one.

![](images/events-nonuser.PNG)

If a user is a participant of a trash audit, they can log in through the login button at the top right of the navbar and gain access to an additional option on the events page to input data for a particular event.

![](images/events.PNG)

Through the About tab, the user can gain a further insight on what trash audits are about, the overall mission and long-term goals of these projects, and the effects of holding trash audits on various UH campuses.

![](images/about.PNG)
