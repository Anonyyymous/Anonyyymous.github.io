+++
title = "Society Website"
description = "A node and react based front/back end to manage users, classes, and logging, for a society"
[extra]
status = "Prototyping"
languages = "JS"
technologies = "Nodejs, React"
image_url = "images/wpaa-site.png"
image_alt = "wpaa-site-alt"
link = "https://wpaa-site.containers.uwcs.co.uk"
+++

This is a replacement website for a society I am active in. The society has frequent lessons, and to attend you must sign up on the SU website. As a student, you can only see the number of people signed up so far, the title of the class, and max capacity, and description.

Next, I (the secretary) have to copy the rough attendants of each class onto a google sheet for each class, the day before it happens, and preferably a bit before it starts, since teachers can't see the signups on the SU website. Then, I have to check if anyone missed some classes they signed up for and didnt cancel with enough notice.
It's a bit long.


Hence, the goal of this website is to allow _everything_ to happen in one place - exec members of the society can make a class, teachers can sign up to teach a class before or even while the class is publically viewable for normal students, and students can not only see the teachers, but also fellow students to each class. Registers can be taken, and missing students can be automatically flagged, while class information will be stored in a database, even with the ability to convert it to a spreadsheet for backwards compatability/extra comfort.

Furthermore, using an API for the SU, we can still ensure that people going to classes are society members, avoiding issues from past years where many people got fake memberships, losing the society money, as there is a small society entrance fee.
