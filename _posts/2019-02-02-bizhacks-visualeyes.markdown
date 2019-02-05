---
title: ":sunglasses: VisualEyes: Visualize. Realize."
layout: post
date: 2019-02-02 20:17
tag: 
- hackathon
- augemented reality
- marketing
- microsoft azure
image: https://joshflchan.github.io/assets/images/visualeyes.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "Eye-tracking and cognitive face analysis to improve marketing"
category: project
author: joshflchan
externalLink: false

---
![Screenshot](https://raw.githubusercontent.com/joshflchan/joshflchan.github.io/master/assets/images/visualeyes.png)

VisualEyes is a 24-hour hackathon project that integrates business and technology to offer an innovative solution to
one of Best Buy's current operational obstacles. 

---

#### What is "VisualEyes"?
VisualEyes is a tool that offers a unique solution to today's varying and obsolote marketing strategies by recording 
consumer focus and predicting demographics and emotions when viewing marketing content. The project utilizes
Swift (for iOS development), Microsoft Azure Cognitive Services API (for emotional facial analysis), ARKit 2 (for predictive eye-tracking), and Firebase (for storing data), and placed 1st at BizHacks 2019, winning Best Buy's Best Hack Award. 

*Note: This project is intended for internal testing only and not meant to be used to access public hardware*

![Screenshot](https://raw.githubusercontent.com/joshflchan/joshflchan.github.io/master/assets/images/bizhacks_group.jpg)

#### How it works
The front-end tracks and projects the consumer's eye movements to calculate the coordinates of the points in which they are 
staring. In addition, every 5 seconds the recording captures a screenshot and the image is processed through Azure's Cognitive 
Services API to predict the consumer's age, sex, and emotion during the period. All the user data generated with the app are stored and uploaded to Firebase for future analysis and data visualizatio processing.

[![Visual Eyes](https://img.youtube.com/vi/dHPioO0KVxE/0.jpg)](https://www.youtube.com/watch?v=dHPioO0KVxE)

Click the image above to watch a video demo :point_up:

#### What's next?

As a proof of concept at BizHacks, my team and I managed to create a working prototpye as described above aside from the 
data visualization features. Within the coming weeks, we are on track to refactoring and implementing the heatmap visualization (with heatmap.js) and additional visuals. I personally plan on developing the Android compatible version with Android SDK and Google's ARCore. 

The project will also be presented to Best Buy executives within the coming weeks as well. 

**Huge shoutout to my man [Alex](https://github.com/superzzp) for being such a helpful teammate during the learning process 
of using Swift**

---
Check out the [demo version](https://github.com/joshflchan/Visual-Eye-BizHacks) here.
Meet the Team: 
- [Alex](https://www.linkedin.com/in/alex-zhang-bucs/)
- [Cris](https://www.linkedin.com/in/cristianmihailescu/)
- [George](https://www.linkedin.com/in/georgexu-/)
- [Jacques](https://www.linkedin.com/in/jacqueschen1/)


