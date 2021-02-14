
# [Effie Manyos Personal Website](https://ruszkipista.github.io/cims01-lkc/)

Static website to promote my services and increase my digital presence. This project is the first milestone in obtaining a [Full Stack Web Development](https://codeinstitute.net/full-stack-software-development-diploma/) diploma from [Code Institute](https://codeinstitute.net/).

![the webpage on different devices](./assets/images/about-img.svg "the webpage on different size devices")

## Contents
- [1. UX design](#1-ux-design "1. UX design")
  - [1.1 Strategy Plane](#11-strategy-plane "1.1 Strategy Plane")
  - [1.2 Scope plane](#12-scope-plane "1.2 Scope plane")
  - [1.3 User Stories](#13-user-stories "1.3 User Stories")
  - [1.4 Structure plane](#14-structure-plane "1.4 Structure plane")
  - [1.5 Skeleton plane](#15-skeleton-plane "1.5 Skeleton plane")
  - [1.6 Surface plane](#16-surface-plane "1.6 Surface plane")
- [2. Features Left to Implement](#2-features-left-to-implement "2. Features Left to Implement")
- [3. Technologies and Tools Used](#3-technologies-and-tools-used "3. Technologies and Tools Used")
- [4. Issues solved during development](#4-issues-solved-during-development "4. Issues solved during development")
  - [4.1 Top-Fixed navbar and anchors](#41-top-fixed-navbar-and-anchors "4.1 Top-Fixed navbar and anchors")
  - [4.2 Trouble with opacity layer on hero image](#42-trouble-with-opacity-layer-on-hero-image "4.2 Trouble with opacity layer on hero image")
  - [4.3 Style list item decorators](#43-style-list-item-decorators "4.3 Style list item decorators")
  - [4.4 Content hinting on mobile device](#44-content-hinting-on-mobile-device "4.4 Content hinting on mobile device")
- [5. Testing](#5-testing "5. Testing")
- [6. Deployment](#6-deployment "6. Deployment")
- [7. Credits](#7-credits "7. Credits")

## 1. UX design
### 1.1 Strategy Plane
Stakeholders of the website:
- visitor - a person visiting the website, not a club member
- member - club member, who actively trains or trained with the club
- officer - affiliated with the club who executes or organises club matters though official capacity
- AIKLF - sport organization which the club is associated with

#### 1.1.1 Stakeholders Goals & Objectives
|G#|User|Goals, Needs, Objectives|
|--|----|------------------------|
|G1|Solopreneur|XXX|
|G2|Small Business Owner|XXX|
|G3|Recent Graduate|XXX|
|G4|Startup|XXX|

### 1.2 Scope Plane
It has been decided to create a static website. In light of that decision we do not go forward with
- G5: this goal would be for presence on a social network site, not for a homepage,
- G10: the calendar functionality would require database and programming, therefore out of scope for now,
- G17: at the moment could not obtain these training plans

The following table lists the **planned features**, each feature referenced with original goal(s):

|F#|Goal|Feature|
|--|----|-------|
|F1|G4|XXX|
|F2|G4|XXX|
|F3|G4|XXX|
|F4|G4|XXX|
|F5|G4|XXX|
|F6|G4|XXX|
|F7|G4|XXX|
|F8|G4|XXX|

### 1.3 User Stories
* As a club coach I want to make available all information that I think needs to be known before a new joiner enters the gym, so I can spare time on explaining things on the first occasion or in emails.
* As a club coach I want to make available a Fitness Self Assessment form to receive it filled from the joiner, so I can train the new joiner more on the first occasion.
* As a website visitor with intent of starting training, I want to access all relevant information on one website about kettlebell training with the club so I could join training without raising any further questions.

### 1.4 Structure plane
The structure of the website to be built consist of
- **Home Page** Sections: Navigation Bar, Header, Who Am I (Short Bio), How Can I help (Services Types), What I Do (Services Fields), Testimonials, Get in Touch, Footer. 
- **About Page** Sections: Navigation Bar, Header, 
- **Services Page** 
- **Training Page**
- **Resources Page** 
- **Contact Page** 

Structure Image Here

### 1.5 Skeleton plane
Feature list in page/section structure with content hinting and navigation links. The following table is a sample, describes the page **TryOut**. Check out the whole list [here](./assets/doc/ci-ms1-features.pdf) in PDF format.

|Page / *section*|Feature#|Feature / Content description|Link or Action|
|--------------|--------|-----------------------------|--------------|
|**TryOut**|F4|come to your first free training||
|*navbar*|F2|*same as on Home*||
||F4|all you need t

### 1.6 Surface plane
Used the website coolors.co to come up with base colors for styling:
![base colors](./assets/doc/color-palette.gif "Base colors")
Also decided th

## 2. Features Left to Implement
- **Gallery** page - Show images/videos about trainings, competitions and meet-ups
- **SignUp** page - Let visitors sign up with email address for newsletter
- **News** page

## 3. Technologies and Tools Used

- The project's product (the website) was written in HTML and CSS, utilising [Bootstrap 5.0 Beta](https://getbootstrap.com/docs/5.0/) framework (which itself uses CSS and JavaScript). Bootstrap is used for its responsive utilities. There is a petite JavaScript in `index.html` to solve a specific issue.
- The images were manipulated with program [Paint.NET](https://www.getpaint.net/). Mainly used for cropping, resizing, background removal and format conversion.
- Created wireframes with program from [balsamiq](https://balsamiq.com/wireframes/)
- Written study notes and collected textual content on [Google Docs](https://docs.google.com/)
- The code was edited with [Visual Studio Code](https://code.visualstudio.com/), the preview was provided via [Live Server](https://github.com/ritwickdey/vscode-live-server) VS Code extension.
- The code versions were managed with [Git](https://git-scm.com/downloads)
- The code and project deliverables are stored on cloud service [Github](https://github.com/) repository with versions.
- The website is deployed on [GitHub Pages](https://pages.github.com/)
- The development machine runs [Windows 7](https://www.microsoft.com/en-us/software-download/windows7) operating system.
- The website was tested on desktop on [Chrome](https://www.google.com/intl/en_ie/chrome/) and [Firefox](https://www.mozilla.org/en-US/firefox/) web browsers, also on a [OnePlus2](https://www.oneplus.com/ie/support/spec/oneplus-2) mobile phone running [Android](https://www.android.com/) and mobile [Chrome](https://play.google.com/store/apps/details?id=com.android.chrome&hl=en) browser.
- Generated favicons with [Favicon & App Icon Generator](https://www.favicon-generator.org/)
- Generated one image (on top of this Readme) of how the website looks on different size devices with [Am I Responsive](http://ami.responsivedesign.is/)
- Played with colors on [coolors](https://coolors.co/), chose the base colors with it
- Chose font using [Google Fonts](https://fonts.google.com/)
- run CSS code through [Autoprefixer CSS online](https://autoprefixer.github.io/) to supplement suggested vendor prefixes
- Searched the internet to find content, documentation and solution for issues using [Google](www.google.com)'s search service.
- connected to the internet using [Vodafone](https://n.vodafone.ie/shop/broadband.html)'s broadband service.

## 4. Issues solved during development
### 4.1 Top-Fixed navbar and anchors
At late stage added the top-fixed navbar to all pages. Before it was only on **Home**. After the change realised, that when jumping from Home to About to a specific section, e.g. `who`, the title of that section is not visible, because the target section get scrolled to the top of the page and the navbar obscures the top of the section.
Found solution

















