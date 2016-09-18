---
layout: post
title: Bloccit
thumbnail-path: "img/bloccit.png"
short-description: A Reddit replica where users can post, comment, and vote on links and content.

---

{:.center}
![]({{ site.baseurl }}/img/bloccit.png)

{:.center}
<a class="button" href="https://vrcooper-bloccit.herokuapp.com/" target="_blank"><i class="fa fa-cloud"> Demo Site</i></a> <a class="button" href="https://github.com/vrcooper/Bloccit" target="_blank"><i class="fa fa-fw fa-github"></i> Source Code</a>

## Summary:
Build a Reddit replica which allows users to create posts and comments and to vote on content.

## Explanation:
This was my first rails app. I had to build a web application from start to finish.  The app has a home page with links for topics, popular posts and user information.  As part of the foundation curriculum we built features such as login/logout, user roles (for example, administrator and moderator amongst others) and uploaded image files. We also enabled email authentication and notification.

## Problem:
1.  Create home, about, topics and user pages
2.  Create posts beneath different topics
3.  Create comments on posts
4   Vote up or down on a post
5.  Favorite a post
6.  User sign-in
7.  Create user roles and authorizations such as (administrator, moderator)
8.  Create public or private posts depending on authorization
9.  Upload avatar for user profile
10. Upload images for posts
11. Create public profile page
12. Create email notifications for favoriting posts

## Solution:
* GitHub for source code
* Heroku to host production version of web application
* Rspec  for test-driven development
* Bootstrap for CSS styling
* SQLite for test, development
* PostgresSQL for production database
* SendGrid for email notifications
* Devise for user authentication
* Pundit for authorization
* Amazon AWS S3 for image file storage
* Will_paginate for pagination
* Redcarpet for markdown syntax

## Results:
A working web application

## Conclusion:
The concepts were very challenging and difficult since this was my introduction to ruby and my first rails app ever. This was also a great introduction to test driven development. I gained basic knowledge of ruby syntax and the rails framework as well as experiencing pair programming.
