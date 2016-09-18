---
layout: post
title: Blocitoff
thumbnail-path: "img/blocitoff.png"
short-description: Build a self-destructing to-do list application.

---

{:.center}
![]({{ site.baseurl }}/img/blocitoff.png)

{:.center}
<a class="button" href="https://vrcooper-blocitoff.herokuapp.com/" target="_blank"><i class="fa fa-cloud"> Demo Site</i></a> <a class="button" href="https://github.com/vrcooper/Blocitoff" target="_blank"><i class="fa fa-fw fa-github"></i> Source Code</a>

## Summary:
Build a self-destructing to-do list application.
Explanation:
The developer builds an application which enables users to create their own task list. This list self-destructs after seven days.  This app was built after completion of the foundation lesson which means that I had to build most of this application on my own.  

##Problem:
1. As a user, I want to sign up for a free account by providing a user name, password and email
2. As a user, I want to sign in and out of Blocitoff
3. As a user, I want to see my profile page
4. As a user, I want to create multiple to-do items
5. As a developer, I want to seed the development database automatically with users and to-do items
6. As a user, I want to mark to-do items as complete and have them deleted
7. As a user, I want to see how many days remain before a to-do item is automatically deleted
8. As a user, my to-dos should be automatically deleted seven days after their creation date

## Solution:
The first four items were very similar to the foundation project, bloccit, so I was able to refer back to it.
* User sign up  
* user sign-in / sign-off  
* User profile 
* Seeding data

Used Devise for user authentication 

The new technology used was rake automation to automatically delete tasks.

## Results:
Successfully working web application

## Conclusion:
This was the first project where I had to come up with most of the code, so I learned a lot about researching various solutions to problems on my own with less guidance.