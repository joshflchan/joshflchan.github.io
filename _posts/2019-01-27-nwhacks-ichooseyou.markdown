---
title: ":video_game: I Choose You!
layout: post
date: 2019-01-27 18:30
tag: 
- hackathon
- augemented reality
- voice-to-text
- stdlib
image: https://joshflchan.github.io/assets/images/ichooseyou.jpg
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "Battle with your Pokémon cards in augmented reality with voice commands!"
category: project
author: joshflchan
externalLink: false
---

![Screenshot](https://raw.githubusercontent.com/joshflchan/joshflchan.github.io/master/assets/images/ichooseyou.jpg)

I Choose You! is a 24-hour hackathon project that allows Pokémon fans to live their childhood dreams of battling with
their trading cards and shouting attack commands - [Quick demo recorded by Keith from Standard Library](https://twitter.com/keithwhor/status/1089681530044207104) .

---

#### Architecture

Inspired by the popular video game Pokémon GO, I Choose You! is an immersive augmented reality mobile game that utilizes
numerous technologies to bring forward its unique experience. Created at nwHacks 2019, the project was developed with
the Unity Engine (for game engine, android packaging and models/textures), Vuforia AR engine (for augmented reality and image tracking),
IBM Watson's voice-to-text API (for speech recognition), and custom Stdlib REST APIs (to calculate battle logic). The project
won the award: "Best/Most Creative Use of Standard Library," presented by the sponsor Standard Library.

![Screenshot](https://raw.githubusercontent.com/joshflchan/joshflchan.github.io/master/assets/images/nwhacks-group.jpg)

#### How it works

When the app is opened, audio is constantly being streamed to IBM Watson and processed, in which a call is then made to
IBM Watson's API. Given the voice commands recognized to text, scripts within Unity's engine are run and call two custom REST APIs
that we created and are hosted on Standard Library - one API for the "attacking" player and one for the "waiting" player." These 
APIs allow us to calculate the battle logic based on attack types and move attack damage. Once processed, Unity's game engine
is triggered to display the attack animations of the respective Pokémon.  

I personally handled the integration of Vuforia's AR engine and image targetting features with Unity, programming the attack
animation scripts in C#, and modeling the battle animations. 

#### What's next?

I am continuing I Choose You! in collaboration with members of my [hackathon](https://adinkwok.com/) [team](http://ianmah.com/).
We are currently heavily refactoring the code from the hackathon to allow for dynamic calls and are in the works of implementing
multiplayer functionality with Google Firebase, remodeling the animations with new textures, and adding additional Pokémon
with Vuforia's cloud SDK. 

---

Check out the [demo version](https://devpost.com/software/i-choose-ndouble-you) here. 
Stdlib APIs [here](https://stdlib.com/@huangsa/lib/waitingplayer-calc/#-) and [here](https://stdlib.com/@huangsa/lib/activeplayer-calc/#-).
Presentation Website [here](http://ichoosenw.com/)
