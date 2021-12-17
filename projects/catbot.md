---
layout: project
type: project
image: images/landing-page.jpg
title: Catbot
permalink: projects/catbot
# All dates must be YYYY-MM-DD format!
date: 2021-12-16
labels:
  - Javascript
  - HTML
  - CSS
  - Meteor
  - React
  - MongoDB
  - Software Engineering
  - Semantic UI
summary: The final project for ics314 software engineering
---
## HACC 2021
This year I participated in a state-wide competition called the Hawaii Annual Code Challenge (HACC). HACC is a hackathon started by Gov. David Ige to encourage more engagement between the local community and the local technology community. The hackathon lasts for multiple weeks and has a list of challenges for the participating teams to choose from. There are two rounds of competition in the hackathon, the first round is mainly based on the implementation of the application and the final round is mainly based on the team presentation.
For HACC 2021, I was in a team called the CatJam and the challenge we chose was from the Office of Hawaiian Affairs, the OHA Chatbot. The purpose of this chatbot is to reduce the amount of miscommunication and provide fast delivery of the right information to the beneficiaries. 

## The Catbot
The Catbot initially started as a web application for the competition HACC 2021 and was later continued as my final project. This web application is mainly based on a Google API called DialogFlow. DialogFlow allows us quickly create a chatbot that uses many features such as machine learning, easy implementations, and analytics. We then implemented more APIs (Botcopy and Janis) to enhance the DialogFlow bot client on the landing page. We created Catbot with Meteor, React, Semantic UI,  MongoDB, Javascript, and HTML/CSS.  When the user first entered the website, they will be greeted by our landing page which includes all the functionality and information they will need to use this application. The user can access the tutorial page to learn how the website works, or they can leave feedbacks/ratings regarding the chatbot. The website also provides a login page for the admin to log in and access pages that a normal user can’t. The admin will be able to access normal user pages and admin pages. Admin can keep track of any admins activities, add new admin account and manage admin accounts through the admin page. They can also view normal users’ feedback on the view feedback page and check the website statistics on the analytics page. 

## My contributions
My main contribution to this project was being the project lead. I planned out the looks of the final product and the functionality that are going to be added to the website. I was also responsible for the frontend and backend of this project. For the frontend development, I created multiple pages like send feedback, view feedback, admin page, and analytics page. I also implemented functionality such as filtering, pagination, and modal to some of these pages which makes viewing information easier. For the backend development, I created multiple collections that keep track of admin activities, user feedbacks, user ratings, user responses, and user stats. All of these collections provide insightful information to the website admin. 

## What I learned
Throughout this project, I learned many new things about Meteor, MongoDB, and React. I gain a better understanding of how to connect MongoDB to the frontend of the website. For example, loading the user’s data from a JSON file, then using a schema to add the necessary data to the collection database, and outputting all the data as a graph or table. I also learned how to code in a team environment, communicate with other members, and manage a coding project.

This link to the project website can be found [here](catjams.github.io/) and the project repository can be found [here](https://github.com/catjams/catbot).
