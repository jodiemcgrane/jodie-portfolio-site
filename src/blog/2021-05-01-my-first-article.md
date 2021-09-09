---
title: College System
author: Jodie McGrane
date: 2021-04-15
image: /assets/blog/course-home.PNG
imageAlt: Courses Page
description: A Vue.js application that allows a user to view and manipulate data about courses, lecturers and enrolments at a college.
---

This project I worked on was part of a CA I had for one of my 3rd year modules called Web Application Frameworks. This CA in particular focuses on Front-end development and UX/UI. Access to the data of the college was provided by a REST API which was implemented within a Laravel application. This application was then to be extended by building a Vue front-end application that allows a user to login and, once they are logged in, to view, create, edit and delete enrolments, lecturers and courses.

Aswell as building a front-end application for the REST API, there was a focus on the UX/UI part of this project. One of the first things you may notice in the application was handling the UI to show/hide elements depending on the user being logged in or out. If the user successfully logs in with the correct credentials they are brought to their admin homepage in which the main navigation panel appears. It affords the user movement from one set of content to another.

<h2>UI Design Patterns</h2>

Many more UI design patterns were used such as buttons, a vertical side-bar menu, search-boxes, cards, breadcrumbs, pagination, tables with filters and many more. In Vue these are all known as components which were created using Boostrap-Vue. It is a component library based entirely on the Bootstrap front-end CSS framework.

Once this project was completed it was successfully hosted, check it out: <a href="https://college-vue-jodie.web.app/">Visit College System</a>

To login to the college system the username is '<b>sam@bloggs.com</b>' and the password is '<b>secret</b>'. Don't tell anyone!

<h2>College System Video Demonstration</h2>

<video width="720" height="486" controls>
  <source src="/assets/CollegeVueDemo.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>

GitHub repository link: <a href="https://github.com/jodiemcgrane/college-vue">College System GitHub Repository</a>