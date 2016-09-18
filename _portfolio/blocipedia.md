---
layout: post
title: Blocipedia
thumbnail-path: "img/blocipedia.png"
short-description: Build a production quality SaaS app that allows users to create their own wikis.

---

{:.center}
![]({{ site.baseurl }}/img/blocipedia.png)

{:.center}
<a class="button" href="https://vrcooper-blocipedia.herokuapp.com" target="_blank"><i class="fa fa-cloud"> Demo Site</i></a> <a class="button" href="https://github.com/vrcooper/Blocipedia" target="_blank"><i class="fa fa-fw fa-github"></i> Source Code</a>

### Summary:
Build a production quality SaaS app that allows users to create their own wikis.

### Explanation:
This was a second project where I had to implement many things which I had already learned in the foundation project, bloccit. I had to implement many of the concepts on my own this time


### Problem:
As a user, I want to sign up for a free account by providing a user name, password and email
As a user, I want to sign in and out of Blocipedia
As a user with a standard account, I want to create, read, update, and delete public wikis
As a developer, I want to offer three user roles: admin, standard, or premium
As a developer, I want to seed the development database automatically with users and wikis
As a user, I want to upgrade my account from a free to a paid plan
As a premium user, I want to create private wikis
As a user, I want to edit wikis using Markdown syntax
As a premium user, I want to add and remove collaborators for my private wikis

### Solution:
Many items were very similar to the foundation project, bloccit, so I was able to refer back to it.
a.) User sign up  
b.) user sign-in / sign-off  
c.) wiki CRUD  
d.) seed database
e.) use Markdown syntax
f.) create user roles

New challenges: 
Create user roles and authorize with Pundit
Upgrade account using Stripe

### Results:
A working web application
Conclusion:
Continued to learn a lot about researching various solutions to problems on my own with less guidance.