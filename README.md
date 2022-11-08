# Django_Blog_Project
This is simple blog project that emulates all the main functionalities of the real blog site. I applied relatively minimalistic design to enable it to by highly customizable 
as I'd like for it to be used in the future projects of similar kind.

# Overview
A Simple Blog, as I named it, has implemented all the CRUD functionalities. It allows users to:
<ul>
<li>create posts (which at first are saved as Drafts; to be visible for all users, author needs to Publish it),</li>
<li>display post's details such as full text, date of creation and author,</li>
<li>edit post's content,</li>
<li>delete posts and drafts that are no longer necessary.</li>
</ul>
This project is built with Class Based Views for the views themselves but also implements functions with decorators to e.g. prevent posting unwanted comments.

# Technology
This site was made using only Python (with Django framework), HTML and CSS. The only JS library used here is the Medium Library which is utilized while typing. It provides 
nifty tool for text editing (including making it <strong>bold</strong>, <em>italic</em> or turning it to a header of choice).

# Purpose
This project was made as a practice to get used to working with Django on a bigger project. I do not intend to monetize it. Although it may be used as a base for future 
projects.
