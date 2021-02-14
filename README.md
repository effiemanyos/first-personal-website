
# [Limerick Kettlebell Lifting Club](https://ruszkipista.github.io/cims01-lkc/)

Static website to promote the [Limerick Kettlebell Club](https://www.facebook.com/Limerick-Kettlebell-Club-201978196542853) and [Kettlebell Sport](https://en.wikipedia.org/wiki/Kettlebell_lifting) around Limerick city, Ireland. This project is the first milestone in obtaining a [Full Stack Web Development](https://codeinstitute.net/full-stack-software-development-diploma/) diploma from [Code Institute](https://codeinstitute.net/)

![the webpage on different devices](./assets/doc/responsive-am-i.png "the webpage on different size devices")

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

#### 1.1.1 Stakeholders Goals and Objectives
|G#|User|Goals, Needs, Objectives|
|--|----|------------------------|
|G1|AIKLF|member organizations feature their affiliation with national (AIKLF) and world organization (IUKL) in info materials|
|G2|officer|provide adequate, easy access training facilities with certified instructors at fair price in popular day/week times|
|G3|officer|incre

### 1.2 Scope plane
It has been decided to create a static website. In light of that decision we do not go forward with
- G5: this goal would be for presence on a social network site, not for a homepage,
- G10: the calendar functionality would require database and programming, therefore out of scope for now,
- G17: at the moment could not obtain these training plans

The following table lists the planned features, each feature referenced with original goal(s):

|F#|Goal|Feature|
|--|----|-------|
|F1|G3|build a custom static website with responsive pages for mobile, tablet and desktop|
|F2||have navigation bar on each pages|
|F3|G1, G19|display LKC’s logo and name, display club’s affiliation with AIKLF and IUKL with logo, name and link, provide description about each|
|F4|G16|pr

### 1.3 User Stories
* As a club coach I want to make available all information that I think needs to be known before a new joiner enters the gym, so I can spare time on explaining things on the first occasion or in emails.
* As a club coach I want to make available a Fitness Self Assessment form to receive it filled from the joiner, so I can train the new joiner more on the first occasion.
* As a website visitor with intent of starting training, I want to access all relevant information on one website about kettlebell training with the club so I could join training without raising any further questions.
* As a w

### 1.4 Structure plane
The structure of the website to be built consist of
- a **Home** page with short leads - all pointing to longer descriptions on the About page,
- a long **About** page receiving traffic from the landing page with many sections with bookmark navigation, end of all sections refer back to **Home** with link
- a **SignUp** page to sign up to receive emails
- a picture **Gallery** page about training, meetups, competitions
- a **News** page related to club events
- a **TryOut** page with every important to know for the first training
- a **Safety** (rules) page to govern the behaviours in the gym
- a **Mission** (statement) page
- a **Constitution** page

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





















