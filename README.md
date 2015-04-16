#portfolio
summary of various projects and the technologies used in each.

##Group Projects
#####[ForgeHealth Innovation Challange](https://github.com/innovation-health/inno-be)
This was a hackathon at the Decatur, GA Veterans Hospital that took place April 10th - 12th 2015. The competition had technologists teaming up with medical professionals (and anyone else who wanted to participate) to hack at issues presented by hospital staff. Our group incorporated a Rasberry-pi and RFID reader to create a bedside application for patients. It involved tracking which medical professionals came in and out of the room, patient questions sorted by department (gastro, surgeon, etc.), and staff notes. The app was supose to be a representation of the patients day to prevent duplicate questions and concerns by the patient and/or their family members.

<strong>Technologies used:</strong>Ruby, Rails, postgres, devise, jbuilder, faker, twilio, heroku<br>
<strong>Concepts explored:</strong> working with hardware and incorporating RFID readers into a web/mobile application. text message alert system through twilio, STI for efficieny due to hackathon time limits, working with non technical parties to come up with a solution to a problem in their field.


#####[Zen Accounting](http://development.bholben-zen.divshot.io/)
This project is held under a private repository in collaboration with [Bob Holben](https://github.com/bholben). We worked over a three week period toward of goal desiging an accounting applicaiton that redefined the typical user experience. This is an ongoing project which will eventually have the ability to upload csv files mapped from Quickbooks, a time keeping mobile app that track hours of vendors and employees, integration to download bank transactions via Yodlee, along with other features. The below technologies are already implemented on the back end.

<strong>Technologies used:</strong>Ruby, Rails, postgres, devise, jbuilder, faker, api based devise invitable, forked Plutus (double entry accounting system), cancan, suckerpunch/ActiveJob, mandrill, AWS S3, paperclip<br>
<strong>Concepts explored:</strong> API token authentication via devise, building json based API infrastructure, documenting a json based API, forking Plutus and implementing multitenant double accounting system, allowing company admins to invite users (employees/cpas/etc.), user authorization via cancan, file uploads via S3 and paperclip, background job processing via suckerpunch for emails, ActiveJob for replacing suckerpunch with redis/sidekiq when file uploads are implemented on the front end.


#####[Jobber](http://development.bholben-jobber.divshot.io/#/signin)
The RoR repository can be found here: [PrePostInterviewGroup](https://github.com/PrePostInterviewGroup/PrePostInterviewGroup) This project took place over a 44 hour hackathon in which we were given several requirments to develope a tool to assist users in their search for a job by keeping track of where a user is in the interview process and sending reminders for scheudled events as well as pre and post follow up items.

<strong>Technologies used:</strong>Ruby, Rails, postgres, devise, jbuilder, faker<br>
<strong>Concepts explored:</strong> API token authentication via devise, building json request/response platform for mobile and web applications, documenting a json based API. 


#####[Ninja Checkers](https://github.com/brossetti1/Checkers_RB)
This was a group project with an objective of building a checkers game via a backend API that serviced a web application and mobile iOS application. 

<strong>Technologies used:</strong>Ruby, Rails, postgres, devise, jbuilder, warden<br>
<strong>Concepts explored:</strong> warden overides to track online users, API token authentication via devise, game logic, building json request/response platform for mobile and web application, documenting a json based API.


#####[spotify_me](https://github.com/brossetti1/spotify_me)
Spotify_me is a project that tracks user requested songs every week, and compiles the songs with the most votes into a playlist that the user can than add to their spotify account. User's have a limited number of votes and 1 veto which can be used to remove any weekly song from the list. This was a collaboration with [Andrew Mercer](https://github.com/chubeesah).

<strong>Technologies used:</strong>Ruby, Rails, postgres, devise, rspotify, httparty, twitter bootswatch, faker, dotenv<br>
<strong>Concepts explored:</strong> oauth implementation - this was unfinished by the end of the project, but the experience was invaluable, implementing a voting system, time based application, integration with the spotify API

#####[connect4](https://github.com/brossetti1?tab=repositories)
This project was an implementation of a connect4 game using devise for user competition. This was a collaboration between myself and [Viedika Birla](https://github.com/birla22v).

<strong>Technologies used:</strong>Ruby, Rails, postgres, devise, bootstrap<br>
<strong>Concepts explored:</strong>join tables, full rails application, connect 4 game and win logic, has_many through assocaitions, html, css, gameification of user stats


#####[tweethouse](https://github.com/brossetti1/tweethouse)
tweethouse is a twitteresq clone that implements shouts and the ability to follow users. This was a collaboration between myself and [Viedika Birla](https://github.com/birla22v).

<strong>Technologies used:</strong>Ruby, Rails, postgres, devise, bootstrap, will_paginate<br>
<strong>Concepts explored:</strong> user interactions, user view helpers (devise), full MVC rails application, pagination, html, and css



##Solo Projects

#####[Bluestone Residuals](https://github.com/brossetti1/BluestoneResiduals)
This is a business application that is in developement which will be used in a live environemnt to parse vendor reports, generate sales data, and pay sales agents commissions. Currently, the database is built out and there are about 7 reports being parsed and imported in developement. This tool will eventually expand to 15+ ancillary reports, but the next step is to incorporate all the logic for generating sales data and commissions.

<strong>Technologies used:</strong>Ruby, Rails, bootswatch, fonta-awesome, less, kaminari, simple form, money-rails, sucker punch<br>
<strong>Concepts explored:</strong>so far, this project is heavy with CSV parsing and storing data post processing. This project also utilizes unique identifiers. STI for certain fee types, more to come as this project progresses. 


#####[todo_javascript](https://github.com/brossetti1/todo_javascript)
This was a project focused around developing a single page app through the use of unobtrusive javascript, jQuery, and ajax. The content consisted of a Todo app that could be shared between users.

<strong>Technologies used:</strong>Ruby, Rails, postgres, acts-as-taggable gem, devise, simple-form, haml, bootswatch, fontawesome<br>
<strong>Concepts explored:</strong>simple jQuery functions and actions, html, CSS, CRUD operations via Rails


#####[CheepCreep](https://github.com/brossetti1/CheepCreep)
building of a github client for grabbing users, followers, and following data. 

<strong>Technologies used:</strong>Ruby, httparty, activerecord, sqlite3 <br>
<strong>Concepts explored:</strong>sending API calls, parsing JSON, manipulating live data, passing params


#####[etsy_searcher](https://github.com/brossetti1/etsy_searcher)
This project involved replicating the etsy search page by incorporating html and css techniques we learned during the time period that this app took place. the scope also called for an integration into the etsy API for returning search results. This project was largely CSS and HTML


<strong>Technologies used:</strong>Ruby, etsy gem, bootstrap, <br>
<strong>Concepts explored:</strong>integrating an API, Environmnet Variables, google chrome developer tools, block vs inline positioning


#####[notepasser](https://github.com/brossetti1/notepasser)
this app allowed users to create unauthenticated accounts and pass notes back and forth to each other. it utilized Models and Controllers via camping and a github client that we roled ourselves. I implemented BCrypt salts and camping session in an attempt to role my own authentication system.

<strong>Technologies used:</strong>Ruby, httparty, camping, BCrypt, github API <br>
<strong>Concepts explored:</strong>API clients, model/controller architecture, validations, authentication, Environmnet Variables


#####[toodoo](https://github.com/brossetti1/toodoo)
in this project, we completed the initiatory todo app for all ruby programers. This was another command line todo list.


<strong>Technologies used:</strong>Ruby, activerecord, sqlite3, highline <br>
<strong>Concepts explored:</strong>basic associations, command line CRUD


#####[blarg](https://github.com/brossetti1/blarg)
blarg is another camping project which allowed us to import and view blog posts in the command line.

<strong>Technologies used:</strong>Ruby, camping micro-framework, sqlite3 <br>
<strong>Concepts explored:</strong>user input, importing and storing posts, viewing posts.


#####[guessr](https://github.com/brossetti1/guessr)
Guessr is a camping based hangman game. This was our introduction to a simple ruby web framework. 

<strong>Technologies used:</strong>Ruby, camping micro-framework <br>
<strong>Concepts explored:</strong>controllers, schema setup, modules, and models


#####[ResidualReports](https://github.com/brossetti1/ResidualReports)
Residual Reports is an unfinished project that involves parsing monthly vendor csv's to generate reports used at Bluestone Payments. This project will eventually translate to a rails project in the future.

<strong>Technologies used:</strong>Ruby, spreadsheet gem <br>
<strong>Concepts explored:</strong>parsing csv's, manipulating rows and columns, exporting data in spreadsheet form.


#####[PinPads](https://github.com/brossetti1/PinPads)
First project in Ruby, this is a simple program that can analyze card processing fees based on volume and transaction count. 

<strong>Technologies used:</strong>Ruby <br>
<strong>Concepts explored:</strong>message passing, Duck Types, data manipulation.


##Exercises (labs folder)

#####[NumberGame](https://github.com/brossetti1/labs/tree/master/01-05/complete)
This was the first assignment we did at the Iron Yard. It is a random number guessing game run on the command line.

<strong>Technologies used:</strong>Ruby <br>
<strong>Concepts explored:</strong>regex validators, loop conditionals


#####[ROT13](https://github.com/brossetti1/labs/tree/master/01-06)
This exercise contains a NATO alphabet with encode and decode functions

<strong>Technologies used:</strong>Ruby <br>
<strong>Concepts explored:</strong>Constants, regex, encoders, decoders


#####[hangman](https://github.com/brossetti1/labs/tree/master/01-07)
We built a simple hangman game in a functional style that runs on the command line.

<strong>Technologies used:</strong>Ruby <br>
<strong>Concepts explored:</strong>functional programs, conditionals, validations, loop conditionals, gsub regex


#####[tic-tac-toe](https://github.com/brossetti1/labs/tree/master/01-08)
A command line Tic Tac Toe game that allows you to play human vs huamn, human vs bot, or bot vs bot.

<strong>Technologies used:</strong>Ruby <br>
<strong>Concepts explored:</strong>functional program, user prompts and menus, bot opponents, search algorithms for win checks


#####[hangman_class](https://github.com/brossetti1/labs/tree/master/01-13)
This exercise involved remaking the command line hangman game using classes.

<strong>Technologies used:</strong>Ruby <br>
<strong>Concepts explored:</strong>classes, instance variables, class properties


#####[tic-tac-toe_classes](https://github.com/brossetti1/labs/tree/master/01-15)
an implementation of the command line based tic-tac-toe game using classes instad of a functional style. 

<strong>Technologies used:</strong>Ruby <br>
<strong>Concepts explored:</strong>user input, class messages, implementing bot difficulty levels up to hard mode, OOD.