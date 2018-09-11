---
layout: post
title:  "JaJa PubQuiz"
description: FullStack Vanilla JavaScript Game that fetch questions from an API to create a full Trivia Game experience up to 4 players.
date:   2018-06-07 12:30:00 +0100
category: portfolio
cover_url: /assets/img/portfolio/pubquiz.jpg
---
## Backstory

While [Cooding Bootcamp Student Simulator](/portfolio/2018/04/06/compendium.html) was a project who force me to learn all about working alone, proper resting and speaking your problems aloud with your colleagues, **PubQuiz** was all about learning to work as a member of a team. Not just the *'Ey, don't forget to git pull and merge before pushing your changes'* but the whole dynamic of being a valuable member of a group, discovering what to do and what to avoid and trying to get the best of each of us instead of just overloading one of the members with all the responsibilities. That, in fact, was the hardest part.

The experience was really good, though. To avoid people pairing up with their besties/forming really strong groups, the *Instructors* spent **a couple** of weeks deciding all the possible groups in secret, trying to group people in a way that:

* All the groups are balanced (its members, and between the groups)
* Every group has a similar structure
* Every group can have a bit of every level, skills and strengths

Looking at all the groups, and in retrospective, I think they did the best they could, and all the combinations really seemed well-balanced. But, a tiny part of me was a bit piss off because I wanted for 13 weeks to work with very specific people (basically, my group of friends), but, **first lesson learnt**, you do not get always to work with the people you fancy. And I am really happy that It was like that, because at the end, I met new people and I enjoyed working with them. And *I learnt* how to approach team work with people I do not know.

I could go really long with this topic, so I guess it is better to reserve it to write a blog post about *the positives and differences between Mob Programming, Pair Programming and Solo Programming*.

But If there is something I need to bring out, it is the importance of daily stand-ups (we set up a *Agile-ish* way of working, with *kanbans*, *scrum masters* and *stand-up*), because if it wasn't for these, we will have probably totally failed. All the problems we had as a team were not fixed until we started to speak them out on this morning meetings.

## JaJa PubQuiz

**PubQuiz** is a vanilla *JavaScript Trivia Game* made with a *ExpressJS* server and a *MongoDB* database made by a **team of four** in a project week as part of [Codeclan's](https://codeclan.com) software developer course. It was developed following [Event Driven Development](https://en.wikipedia.org/wiki/Event-driven_programming), with an [MVC](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) pattern, a [RESTful](https://en.wikipedia.org/wiki/Representational_state_transfer) [API](https://en.wikipedia.org/wiki/Application_programming_interface) server for storing highscores.

This game will create a Trivia Quiz for a group of up to 4 teams using the user input form on the app homepage. This form will create a link that will fetch the questions from an external API called [OpenTDB](https://opentdb.com/).

**Tech Stack used:**

* JavaScript, HTML and CSS for the front-end
* [NPM](https://www.npmjs.com/) for managing all the JS packages.
* [Mocha](https://mochajs.org/) for unit testing
* [Webpack](https://webpack.js.org/) to create the JS bundle
* [MongoDB](https://www.mongodb.com/) for the database
* [Express](http://expressjs.com/) for the server-side

## Links

* [You can access here a live demo](http://pubquiz.devazul.co.uk) you can look at and play with. Since it is written on vanilla JavaScript, and was my first JavaScript app, there are some browsers that have problems with it, so I would recommend to use [Google Chrome](https://www.google.com/chrome/).
* You can look through the ugly code by visiting the [Github repo itself](https://github.com/DetectiveAzul/cc-group-project_trivia).
