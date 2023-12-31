---
layout: project
type: project
image: img/Logo.png
title: "rainbow-gallery"
date: 2023
published: true
labels:
  - JavaScript
  - Bootstrap
  - Meteor
  - CSS
  - React
  - MongoDB
  - GitHub
summary: "This was a project made in ICS 314 as our end-of-the-year project"
---

<img src="https://rainbows-gallery.github.io/Images/M3/landing.png" width="100%"/>

This was our end-of-the-year project for my ICS 314 class. In this class, I was partnered up with three other students in my class. Our main point of contact was through the Discord private channel where we met up every Tuesday and Thursday to catch everyone up on where we were at on our part of the project. We also used this time to assign tasks to each member so that everyone was doing an equal amount of work. Underneath is a contract that we drafted to outline how our group was going to work
 
Source: <a href="https://docs.google.com/document/d/1cbQv4htZbSGHQxj_0gbgDfSVIsTfvkACISIYMw3NIY0/edit?usp=sharing">Contract</a>

## What is the Project

Our group was tasked with creating a platform that would allow art majors of UH Manoa to post works they have created. To create this project we drew inspiration from sites such as Instagram, and other social media platforms. We then determined the features we wanted to have in our application. Underneath is our list of features we implemented in the project

Features

- Users (Sign Up / Sign In / Sign Out)
- Create a Follower system
- Implement a way for users to upload a post
- Create a favorite feature
- Create a search feature for users
- Create a Feed system of posts from users people follow
- Create a landing page
- Create a guide to use the site

From here we then started giving people tasks to complete certain portions of the site. We divided the tasks into three parts or stages to be completed. So some stages require us to create the look of the page and then the next stage could require us to create the functionality that is missing on the page. These tasks per stage were assigned to a person at the beginning of the start of the stage and then they were tasked to complete it by the end of the stage.

## Coding Environment

When coding for this project we used IntelliJ which was created by JetBrains. We then used NVM to change the Node version we were using to Node 16. We had to use Node 16 since that was one of the few versions of Node that worked with Meteor which is the backend framework we used for this project. During this, we also installed the meteor plugin that exists for web browsers to make it easy to debug issues we were having while coding. We also used TestCafe to test out the functionality of a website and check for any errors that populated while interacting with the website.

## Meteor

In this project, we used Meteor as our Backend for the site. The Meteor framework also used React as the front end and used React-Router for routing to certain pages. In this, we created APIs that we were able to interact with by using Meteors Subscriber methods. This allowed us to create all the functionality that was introduced due to our database.

## Database

For our database, Meteor works out of the package with MongoDB. When running the code it spins up a MongoDB instance which stores all our data. In this database, we had over 5 collections (For SQL people that means around 5 tables) one for users, one for posts, one for followers, one for comments, and one for liking posts.

## Testing

For testing, we had to make sure that the code followed all the Es-Lint standards that were defined in the Es-Lint file. On top of that, we were then tasked to test the functionality of our site using TestCafe. TestCafe is a library that makes you define a test file within your project, where you define instructions on how to interact with your site. Once you do that you can run these scripts and it will simulate these interactions on your webpage. If at any point it runs into any errors or issues it will flag and fail the test. Within Github's server actions, we implemented a feature where if the main is updated it would run the action to check if it passes all the tests. We then were able to display a badge on our documentation of whether the code had passed its test or failed it.

## Contributions

For this project, I worked heavily on the functionality of the page. I created the followers/following collection, the posts collection, and the liking of a post collection. From there I implemented the features such as creating the Meteor subscriptions for these schemas. I also created a feature that takes in a user's file that they uploaded for a post and stores it in a service called Cloudinary. I then created the clickable image component that is used on multiple pages to show all the posts. I also implemented a way for users to like a post (starting a post / un-staring a post). I then developed all the testing scenarios that were used to test out the functionality of the site.

## Preview

<img src="https://rainbows-gallery.github.io/Images/M3/your-profile.png" width="50%" style="float:right;"/>
<img src="https://rainbows-gallery.github.io/Images/M3/add-post-filled-in.png" width="50%" style="float:left;"/>
<img src="https://rainbows-gallery.github.io/Images/M3/feed-after-follow.png" width="50%" style="float:right;"/>
<img src="https://rainbows-gallery.github.io/Images/M3/photo-interact-after-like-comment.png" width="50%" style="float:left;"/>

## Documentation

Github Repo: <a href="https://github.com/rainbows-gallery/gallery-app">Repo</a>
Documentation Page: <a href="https://rainbows-gallery.github.io/">Documentation</a>
MileStone Page: <a href="https://github.com/orgs/rainbows-gallery/projects">Mile Stones</a>