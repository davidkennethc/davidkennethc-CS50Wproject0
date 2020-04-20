# Project 0

Web Programming with Python and JavaScript

## Introduction:

My homepage project is a space to share some info about MOOCs, including MOOCs which I have completed and a general Q&A section about MOOCs. The Q&As have been taken from https://www.mooc-list.com/ and https://www.classcentral.com/.

I have also included a page which includes relaxing pictures of mountain scenery.

## General:

Each page/file contains a bootstrap navbar which sticks to the top of the page.
The navbar is mobile responsive - on smaller screen sizes the navigations items are condensed into a "burger" menu, revealing the nav links to all other pages once you click on the burger menu.
I have crated a media query so that the navbar text changes on smaller screens.
An additional media query changes the left and right padding, so that the paragraphs look nicer on smaller screens.

My fonts and styling are inspired by the following user guide: https://www.freecodecamp.org/news/how-to-make-your-front-end-projects/.

## Files:

### index.html

This is the landing page with an introduction to the website and links to the other pages.

### moocs.html

This page contains a table with an overview of some of the MOOCs I've completed and am currently working on. The table data includes MOOC platform (EDX or Coursera) and the status of the course (In Progress or Complete).

A description of each course is contained further down the page.

The data in the 'course' column is clickable and scrolls you to the course description, each of which is tagged with an ID selector.

### faqs.html

This ia a general FAQ qage about MOOCs. The questions and answers were taken from www.mooc-list.com and www.classcentral.com.

It contains a list of question at the top, each of which is clickable and scrolls you down to the answer. Each anser has a 'back to top' button below it, allowing you to easily get back to the list of questions at the top of the page.

### mountains.html

This page contains a gallery of photos with mountain scenery. This makes use of the bootstrp grid system.
Additional media query change the left and right padding so that the phtographs are presented in 2 columns on larger screens.
