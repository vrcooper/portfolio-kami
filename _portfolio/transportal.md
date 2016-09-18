---
layout: post
title: Transportal
thumbnail-path: "img/transportal.png"
short-description: Transportal allows useres to create profiles and projects.

---

{:.center}
![]({{ site.baseurl }}/img/transportal.png)

{:.center}
<a class="button" href="https://transportal.herokuapp.com/" target="_blank"><i class="fa fa-cloud"> Demo Site</i></a> <a class="button" href="https://github.com/vrcooper/Transportal" target="_blank"><i class="fa fa-fw fa-github"></i> Source Code</a>

## Summary:
Transportal  is a web application which allows users to sign in and create user profiles, create projects and upload and download files.

## Explanation:
This is the capstone for the backend portion of the full stack web development curriculum using RoR. The initial concept was to build a web app which serves as a translator's resource for project collaboration.  The main features were the creation of a translator profile, a terminology forum which allows users to post and comment on terminology topics and the creation of translation wikis . Due to time constraints the project is only partially completed and users are currently only able to create profiles and projects and upload and download files.

## Problem:
1. As a user, I want to sign up for a free account by providing a user name, password and email
2. As a user, I want to sign in and out of Transportal
3. As a user, I want to create projects
4. As a user, I want to upload and download files

## Solution:
* Devise for user authentication
* Created projects, documents and users  models , controllers and views
* Use CarrierWave to upload and store images
* Use MiniMagic to manipulate images

## Results:
A working web application

## Conclusion:
I was able to reinforce some of the basic concepts which were acquired in the previous projects. This was very challenging since I had to build from scratch based on my own concept for this project. One of the greatest lessons learned on this project was that I had more ideas than I had time, so I had to reduce my concepts down to the essentials. 