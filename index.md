## Manoa Eateries


## Overview
Manoa Eateries is a project created for ICS 314 by Brooke Maeda, Andee Gary, Albert D'Sanson, and Eliya Nakamura to provide students with the opportunity to see what is available to eat on campus. Using tools such as Bootstrap, React, HTML, and CSS an application will be made to allow users to view various food options, vendors to add any new items or daily specials. A landing page will show users the ability to see the various food options on campus and filter it out to find what they are looking for.

## Project Goals
- Give users a convenient place to view the menu items of the various food vendors at UHM
- Display menu items based on the specific day and time
- Filter the data based on item type (ethnicity, gluten free, vegetarian, etc.)
- Implement vendor roles that can specify what days and times an establishment is open, and allow for menu changes as needed
- Implement user roles that can specify a person’s dining preferences
- Implement admin roles that can add vendor roles to users and modify any aspect of the system


[Team Contract](https://docs.google.com/document/d/1fNMn6Be5DwtTorRnbEHNBvZuMuU2cnv_35YeOkjgyYU/edit?usp=sharing)
## Developer Guide 
### Installation
First, [install Meteor](https://www.meteor.com/developers/install)

Second, vision the [Manoa Eateries application github page](https://github.com/manoa-eateries/manoa-eateries) and download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer.

Third, cd into the Manoa Eateries app/ directory and install the libraries with: 
```
$ meteor npm install
```
Fourth, run the system with:
```
$ meteor npm run start
```
If all goes well it will appear at [http://localhost:3000/](http://localhost:3000/)

### ESLint
You are also able to invoke the ESLint command from the command line with:
```
meteor npm run lint
```
Here is an example showing that no ESLint errors were detected:
```
$ meteor npm run lint

> manoa-eateries@ lint /Users/johndoe/github/manoea-eateries/app
> eslint --quiet --ext .jsx --ext .js ./imports ./tests

$
```
ESLint should run without generating any errors
## User Guide
- Landing Page
  <br/><br/>![](images/LandingPage.jpg)
  When users first enter the site, they are greeted with the landing page.  This displays the mission of Manoa Eateries and the participating vendors.

## Mockups

- User Home Page
<br/><br/>![](images/UserHomeMockupUpdate.png)


- Vendor Page
<br/><br/>![](images/VendorPageMockupUpdate.png)


- Sign-in Page
<br/><br/>![](images/ManoaEateriesSignInPage.png)


- Sign-Up Page
<br/><br/>![](images/ManoaEateriesSignUpPage.png)


## Projects
[Milestone 1](https://github.com/orgs/manoa-eateries/projects/1/views/1)
[Milestone 2](https://github.com/orgs/manoa-eateries/projects/2/views/2)

## Deployment
[Digital Ocean application](http://143.110.235.49)
