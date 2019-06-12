---
layout: post
title:      "A Mountain High Enough"
date:       2019-06-12 18:33:55 +0000
permalink:  a_mountain_high_enough
---


I had so much fun creating my first Sinatra web app. This summer, I'm trying to climb the Six Pack of Peaks in Southern California, and it's made me search for easier ways to connect with other people over mountain climbing, as well as track and plan my climbs. 

![Not a mountain that I will be climbing](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Wonder_Lake_and_Denali.jpg/800px-Wonder_Lake_and_Denali.jpg)

Enter A Mountain High Enough, my first Sinatra app. I have big dreams for this app- that I could scrape data about all the mountains in the world and classic hiking trails, that users could view each other's trips, plan trips together, and upload photos and trail notes. 

To start with, I created a Mountain class, Trail class, User class, and Trip class. The relationships are as follows: 
* Trails belong_to a Mountain, and a Mountain has_many trails. 
* Trips belong_to a Trail, and a Trail has_many trips. 
* Trails belong_to a User, and a User has_many trips. 

I created the homepage of the app, where users can log in or sign up. That directs to a user homepage, where Users can create new trips, view a trip feed, or log out. 

The trip feed is a list of everyone's trips. Eventually, I'd like to add ways to collaborate on the same trip, but for now each trip belongs to a specific User. It's so inspiring to hear about other Users' trips. 

Users can view each others' trips, but can only edit or delete their own trips. Also, Users cannot view the login or signup page if they are already logged in. 

I can't wait to extend this app and create more mountain climbing functionality in the future! 
