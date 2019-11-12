---
title: The technical makings of a Front End developer portfolio. 
published: false
description: The technical makings of a modern Front End developer portfolio 
tags:
---

In my last post, I highlighted three tips for a developer's portfolio website. Now, I want to go into the technical aspects that make a frontend in product developers website stand out. For my portfolio, I took a mobile-first approach. Mobile-first means making sure that the mobile version of my website looked good on any mobile device. Or this to happen, it had to be responsive and accessible.

# The Frontend Architecture

### The Design: //design thinking

Like all good little developers, I started my portfolio with pen and paper.

![insert image of my drawing]()

I used **chrome extension** to find the color palette of my favorite character from a cartoon. I plugged in some demo text from [Khaled Ipsum](http://khaledipsum.com/)

I had some pretty bad design ideas like too much whitespace and incorrect portion ratio. I used [Laws of UX](https://lawsofux.com/) as a reference for all of the laws not to break.

#### Header

The background image of my header is dark and uses a white text color over it. My image and title are there.

#### Body

The body of my site has an off white color with black text and equal padding on all sides. I decided to center the text instead of having a left-justified paragraph style.

##### Social Icons

This area is a(playground/display of) ability to play with color in a fun way. Each "button" is a different color, has a different color when hovered or in focus, and has an icon that is accessible in both states.

There's no white space. On the desktop version, the cursor changes when in this content area.

After I had a header and footer that have at least a 4:1 ratio to the background of the body, I pruned some of the coding architecture.

### The Code

It's not always clear what info should be shown first on a webpage. I used **code-tricks** to help me separate the sections of code. 

#### The HTML

* Made clear sections
* Used simple descriptive classes
* Decoupled (meaning that there's no CSS code in my HTML file)

#### The CSS

I used clean CSS and broke repeating elements up into utility classes. Utility classes allow you to assign properties without having to write the same line of code over and over. Instead, just call the CSS in the HTML.

For example, I added 10em of padding to every section on my site. Instead of giving the header padding of 10em, the divs padding of 10em, I just called class="10Padding" in the HTML of each section. 

<add an image of CSS utility class and demo of HTML from Carbon>

### Serverless

* Cloud Image Processing - UploadCare
* Firebase Hosting w free SSH
