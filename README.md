# _Anaconda_ Martial Arts Academy

_Anaconda_ Martial Arts Academy is a local school of martial arts located in Dublin 15, that teaches a combination of disciplines necessary to become a Mixed Martial Artist.
The goal of the academy however is not to train competition ready athletes but to help their members to get active and fit and receive all benefits of martial arts training, including building self-esteem and confidence.
The classes tought in the academy are: Brazilian Jiu Jitsu, Kickboxing and Boxing and also MMA for the more advanced students.
Members can practice one chosen discipline or get involved with the whole MMA suite of disciplines.
The school accepts new members across all ages (in BJJ classes, kids can start as early as the age of 4) and various skill levels from Beginners to Advanced.
As 'Anaconda' academy is growing in members, they want to redesign their existing website and bring it up to todays standards in terms of look, responsiveness, user experience and SEO.

<img src="assets/images_readme/ms1-readme-overview.png" alt="Anaconda MAA website overview">

# Link to live project - [CLICK HERE](https://lukaszpasich.github.io/Anaconda-MAA-MS1/index.html) 

#### Contents
1. [UX](#UX)
	- [User Goals (Strategy)](#user-goals)
	- [Stakeholder Goals (Strategy)](#stakeholder-goals)
	- [User Stories (Strategy)](#user-stories)
	- [Project Scope (Scope)](#project-scope)
	- [Information Architecture and Interaction Design (Structure)](#information-architecture-and-interaction-design)
	- [Wireframes (low fidelity wireframes) (Skeleton)](#wireframes-(low-fidelity))
	- [Prototype (high fidelity wireframes) (Skeleton)](#prototype-(high-fidelity))
	- [Design (Surface)](#design)
2. [Features](#features)
	- [Navigation Bar](#navigation-bar)
	- [Footer](#footer)
	- ['Join Academy' call to action button](#join-academy-call-to-action-button)
	- [Home Page](#home-page)
	- [About Page](#about-page)
	- [Classes Page](#classes-page)
	- [Times & Prices Page](#times-&-prices-page)
	- [Coaches Page](#coaches-page)
	- [Contact Page](#contact-page)
	- [Contact Form](#contact-form)
	- [Google Maps Location Map](#google-maps-location-map)
	- [Favicon](#favicon)
	- [Features to implement in the future...](#features-to-implement-in-the-future)
3. [Technologies](#technologies)
	- [Tools](#tools)
	- [Libraries](#libraries)
	- [Languages](#languages)
4. [Testing](#testing)
	- [Automated Testing](#automated-testing)
	- [UX Testing](#ux-testing)
	- [Manual Testing](#manual-testing)
	- [Bugs](#bugs)
5. [Deployment](#deployment)
6. [Credits](#credits)
	- [Content](#content)
	- [Media](#images)
	- [Code](#code)
    - [Resorces](#resources)
	- [Acknowledgements](#acknowledgements)


---


## UX

### User Goals
- Find out information about the academy and it's procedures.
- Find out information on classes provided and instructors providing the classes.
- Find out information about age groups and skill levels that classes are divided into. 
- Find out timetable of classes.
- Get an idea of membership prices. 
- Find information on how to get in touch with the school and start the training.
- Get the feel for the academy - is this academy for me / for my child?
- Get the feel for the academy - is it friendly and open to all members of the public or more of an elitist school for people 'in the know'? 

### Stakeholder Goals
- Attracting new members to join the academy.
- Retaining existing members.
- Providing comprehensive information about the academy to answer all the initial questions vistors may have.
- Increasing an online presence as a tool of advertising and promotion.
- Processing membership payments on the website would be a plus.

### User Stories

1. As a user of the website I want the information to be laid out clearly, visually structured in a way that makes sense, so that I am not confused by it and put off from using the website.
2. As a user of the website I want it to be easy to navigate, so that I can find what I'm looking for easily. 
3. As a novice to martial arts, I would like to find out what skill levels the school caters for, so that I'm encouraged to start the training and won't feel intimidated.
4. As someone with previous experience in martial arts, I want to make sure that the school provides training in the full suit of Mixed Martial Art disciplines
and that instructors are experienced and at a high level of competency, so that I could potentially get to the competing level in the Mixed Martial Arts.
5. As a parent of a primary school age child, I want to find out if the school provides classes for different age groups, to make sure that my child could train with the peers at the similar level of development.
6. As a busy working adult who would like to start the training, I expect to find a time table of classes, to make sure first of all that it's is possible for me to attend the classes time-wise before I get in touch and start the process of becoming a member.
7. As a person who needs to budget carefully, I would like to know upfront the membership prices, so that I can make a decision based on that piece of information first, before I engage with the academy and start the process of becoming a member.
8. As a user accessing this site from a mobile phone or tablet, I want the site to be responsive, so that it is easy to navigate and use on smaller devices.
9. As a potential member trying to get in touch with the academy, I expect some sort of feedback or acknowledgement of my online query, so that I know it has been received by the school and I can expect it is being processed.
10. As a returning visitor, I expect to be able to check if the times of the classes have changed, look up information about the new instructors and be able to find the social media links to check for new posts, images and videos published bt the school.

### Project Scope
 Creating the website for _Anaconda_ Martial Arts Academy with the goal of attracting new members to the academy.
 The website should consist of 3-6 pages, making sure that it is clean looking, easy to navigate and responsive.
 An invitation to a introductory, free and no commitment session should be a prominent and (reasonably) frequently repeated element of the website.
 The following information must be included: some information about the school, information about the classes, classes timetable and membership prices.
 The culmination of the interaction with the website is the _Contact_ page, where users (potential new members) need to be able to find enough information,
 so that they could get in touch with the school through various channels (physical address, email address, telephone, social media channels, contact form).

### Information Architecture and Interaction Design

#### Site Map
The website is simple enough that I chose a hierarchical tree structure for it.
It is a standard structure with reduced complexity and any down sides this type of structure might have for mobile phone use are mitigated by the fact that each branch in this case is only one page long.
<img src="assets/images_readme/ms1-readme-ux-sitemap.jpg" alt="Anaconda MAA website site map">

#### User Flow
The flow has been designed with visitors landing at the _Home_ page first in mind.
There is a possibility of visitors arriving to different pages first from social media links (through 'meet the new coach' or 'see our new times for kickboxing classes' types of posts) but navigating the website in those cases should still be simple enough.

__Navbar links__ connect all pages apart from _Home_ page.
To simplify the interaction I decided not to link _Home_ page there as it only acts as a nice landing, introduction page but it doesn't have any more information that visitors wouldn't find on other pages.
_Home page_ is still accessible by clicking on the logo or the link in the footer for visitors who are resolved to see it again. 

__Internal links__ connect some pages to create simple and logical user flow mini routes:
- User mini route 1 - About Martial Arts discipline:
	- _Home_ page -> read more about chosen martial art (takes visitor to _About_ page)
	- _About_ page: details about the martial art -> read about instructors (takes visitor to _Coaches_ page)
	- _Coaches_ page: details about instructors (a back-link to read about disciplines on _About_ page is here)

- User mini route 2 - About Classes:
	-  _Classes_ page: details about classes' age groups and skill levels -> find out times for the class you'd like to take (takes visitor to _Times & Prices_ page)
	- _Times & Prices_ page: details a about the class times
	
__'Join our academy' call to action button__ creates direct link to _Contact_ page for visitors who are decided to go to the next step towards becoming a member.

<img src="assets/images_readme/ms1-readme-ux-userflow.jpg" alt="Anaconda MAA website user flow">

### Wireframes (low fidelity)
Wireframes created for 4 screen/ device sizes: desktop, tablet-landscape, tablet-portrait and phone.
- [Wireframes for all pages AVAILABLE HERE](https://indd.adobe.com/view/9dbb137a-4682-4b70-ab66-76e4a1d67484)

### Prototype (high fidelity)
Translating wireframes into the high fidelity prototype was an excellent exercise.
I got to see what worked in wireframes and what had to be tweaked. It was also good for deciding on, creating and populating all content and for solidifying the visual side.

After completing the prototype I had all my content, interaction and design decided on and finished.
At this point I was ready to move to pure code writing. 
- [Prototype - desktop version of the website AVAILABLE HERE](https://xd.adobe.com/view/b863cf46-772b-46b9-bb51-34d61b939cae-ed30/)
- [Prototype - mobile version of the website AVAILABLE HERE](https://xd.adobe.com/view/0e7b1086-38de-4079-a98a-e7318462fcea-5b28/)

### Design

#### The Name

Why Anaconda?


The martial art of Brazilian Jiu-Jitsu - one of the staples of the academy - is in essence the skill of grappling, holding and taking down the opponent to then force them into submission via joint lock or chokehold.
This very much resembles the actions of a constrictor snake and one of the submissions in BJJ is even called an _Anaconda Choke_. As grappling has become one of the key weapons in Mixed Martial Artist's arsenal, Brazilian Jiu-Jitsu became near synonymous with MMA and that's why I thought it was a good name for the Martial Arts Academy.

#### Logo
With the logo I was trying to emulate the classic idea of the Martial Arts Club badge which seems to have always evolved around some related image or an Asian symbol enclosed in a circle (or lately popular octagon), with the club name and all the necessary text wrapped around that circle.

Reference images:
<img src="assets/images_readme/ms1-readme-ux-logoref.jpg" alt="Anaconda MAA website logo reference">

Anaconda MAA final logo:
<img src="assets/images_readme/ms1-readme-ux-logo.jpg" alt="Anaconda MAA logo">

#### Colours
Principally white, red and black colour palette - these three colors are the first colors humans see as important.
With black and white representing the concept of dualism, describing how seemingly opposite or contrary forces may actually be complementary, interconnected, and interdependent in the natural world, and the red colour being universally seen as a sign of both life and aggression - 
the 3 colours have always been used in martial arts themes.

In my research of the competitor's websites, I discovered that these were the prevalent colours on all of those websites and the similar colour theme would also be possibly expected by the website user/ visitor, adding credibility to the brand, company and the website. 


<img src="assets/images_readme/ms1-readme-ux-colours.jpg" alt="Anaconda MAA website colours">

#### Typography
- Raleway: Semi-Bold, Bold and Extra Bold - for headlines and sub-headlines.

_Raleway_ because it is a nice and clean display typeface and also geometric sans-serif fonts (as _Raleway_ being geometric inspired) tend to have more neutral feel about them.
As Anaconda MAA aims at attracting a diverse audience, I didn't want to use font with too strong personality, because I wanted to convey an 'everybody is welcome' academy's approach to attracting it's new members.

- Roboto Slab: Regular - for body text.

_Roboto Slab_ has forms that are largely geometric, but at the same time, the font features friendly and open curves - it is an excellent body text font and a good compliment to Raleway.
Allowing letters to be settled into their natural width and with slab-serifs clearly defining the text baseline _Roboto_ creates an easy and more natural reading rhythm.


Both fonts and also their combination has been tried and is well established and widely popular on the web.


#### Images

Why black and white photography?

Black and white photography removes any distraction of color and helps the viewer focus on other aspects of the photo, such as the subject, the textures, shapes and patterns, and the composition.
It can convey remarkable purity of emotion and action and therefore works perfect for martial arts.

Black and white images look epic and historical. Using them in my website I wanted visitor to think "everyone in this image looks like a legend" and add on a deeper subconscious level "by joining this academy, I will become a legend too" :)

[Back to top](#contents)

---
