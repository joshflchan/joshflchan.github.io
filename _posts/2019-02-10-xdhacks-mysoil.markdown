---
title: ":seedling: MySoil"
layout: post
date: 2018-09-20 21:10
tag:
- hackathon
- agriculture
- reactjs
- mental health
image: https://joshflchan.github.io/assets/images/mysoil.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "24-hour hackathon project that brings communities together and encourages healthy living through gardening"
category: project
author: joshflchan
externalLink: false
---

![Screenshot](https://raw.githubusercontent.com/joshflchan/joshflchan.github.io/master/assets/images/mysoil.png)

MySoil is a 24-hour hackathon project developed as an integrated community garden management web application and soil health monitoring system. - [Demo](http://mysoil.space).

---

#### What is "MySoil"?
MySoil is a web application that encourages and helps manage community gardening through Reactjs, as well as a soil health monitoring system powered by an arduino and soil moisture/environmental sensors. Users are able to find and join local community gardens based on location data and are assigned/reminded of weekly tasks. The project was created at XdHacks 2019 for the
food and global resources path.

*Note: Unfortunately, we were unable to get a group photo this time and missed out on capturing some special moments of the project in action :disappointed:. Here's a picture of the web app instead!*

![Screenshot](https://raw.githubusercontent.com/joshflchan/joshflchan.github.io/master/assets/images/mysoil-screen.PNG)

#### How it works
As a minimal viable product, my team and I managed to create a functioning soil moisture/environmental sensor and programmed the arduino to track the data (soil moisture, humidity, and temperature) on a time-specified basis. The data is then encoded to a JSON file, passed to Firebase, and then processed and displayed visually on the front-end of the web application. Users are also able to log in via Google, Facebook, Twitter, or Github through Firebase's Authentication feature. Based on the soil health and weather status, the web application would also notify users of their weekly assigned tasks. I personally worked on aspects of the web application, actively learning Reactjs throughout the hackathon.

#### What's next?
Owing to time constraints and lack of resources, we were unable to weather-proof and attach a Wi-Fi shield to the arduino the have the JSON data passed directly to Firebase. Moreover, the weather application on the website is not very accurate, which causes some miscalculations for task reminders. We also had plans of implementing a chat feature and recommending crops based on soil health and region, then recommending healthy recipes based on these crops.

Learning Reactjs within 24-hours was definitely the most challenging part of the project, but was also very rewarding! Challenging myself to work with hardware at a hackathon for the first time was also an interesting experience. I look forward to utilzing these newfound skills in the near future :smile:.

---

Check out the [demo version](https://mysoil.space) here.

Meet the Team:
- [Jon](https://www.linkedin.com/in/jonkim99/)
- [Ian](https://www.linkedin.com/in/ianmah/)
- [Nicholas](https://www.linkedin.com/in/nicholaszkwan/)
- [Vandy](https://www.linkedin.com/in/vandy-liu/)
