---
layout: post
title:      "Sinatra Project: The Bow Tracker"
date:       2020-12-10 21:35:18 -0500
permalink:  sinatra_portfolia_project_-_the_bow_tracker
---


The biggest challenge when I get to a bigger project is always the beginning. Coming up with an idea is not easy, because I want what I make to be something that people could (potentially) use. I ultimately fall back to something that I know. For this project, I went with musical instruments.

I'm a musician, and for the last ten years or so I have been a bowmaker (think violins, not archery - I get those phone calls all the time). I decided to make an application that could either work for musicians to keep track of their personal bow collection, or for violin shops to keep track of their inventory. In terms of practicality, it could be a very useful app for a shop to track its inventory, both for the shop itself, and for customers to be able to look through a catalogue of what the shop has to offer.

To the coding!

I used a gem called Corneal to set up my basic MVC directory. That was extremely helpful. I referenced a few earlier labs to make sure I had the config.ru and environment set up correctly, along with gemfile, rakefile, etc... Then it was just step-by-step plugging away.

i started with the database, building my models and setting up the tables and their associations. A User has many Bows. A Bow belongs to a User and a Maker. A Maker has many Bows. A User has many Makers through Bows...

Once that was set up, it was just a matter of building out the views and controller actions. I started from the home page, and as I built each route, I would build the view that went along with it until I had the full functionality I was looking for. One hiccup was adding in ActiveRecord validations, but after watching a tutorial by one of the Flatiron instructors it was no problem. The tutorial also included flash error messages, which definitely help the app by giving more direction to the User when something doesn't work.

I'm pretty happy with the finished product. I may make a few more tweaks - CSS is not my strong point. But I'm happy with the functionality!

On to the next lesson!
