---
layout: post
title:  "Compendium"
description: A Dungeons&Dragons WebApp connected to a database with capacity to keep track of your characters spellbooks and spells knowledge. Made with Ruby, Sinatra and PSQL.
date: 2018-04-06 17:00:30 +0100
category: portfolio
cover_url: /assets/img/portfolio/compendium.jpg
---
## Backstory

Compendium was born during my fifth week on [Codeclan](https://codeclan.com) intensive course. It was made with two ideas on mind:
* It needed to be simple enough to be made on the five days I only had to create the whole WebApp
* I wanted to create something it could be used by me or friends

It was actually though because, adding to the time constraint, the tech we could use it was limited to what they taught us in the previous weeks:
* No JavaScript
* No ActiveRecord for controlling the database
* Ruby, CSS and HTML for the front-end
* Sinatra for the server

<sub>1</sub>. DMing: Dungeon Mastering, the act of direct and manage a [Dungeon&Dragons](http://dnd.wizards.com/) game
{:.side-note}

So, after some thoughts, and because I was *DMing*<sub>1</sub> with some of my colleagues from the course, I decided to create an app that could be use for managing the spells and spellbooks of my players.

I discovered I really liked working in the back-end part. Writing the server, the routes, handling error through redirections... that part was really fun. **CSS**? That was really a pain in the arse. But, hey! I really learnt about [*Flexbox*](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) and [*Bootstrap*](https://getbootstrap.com/) that week, and now it is really useful, so... lesson learnt!

## Compendium

**Compendium** is a Spellbook tracker that creates, tracks and organizes *Dungeons and Dragons* spells on units called Spellbooks, owned by Characters. Is a **Sinatra** [*RESTful*](https://en.wikipedia.org/wiki/Representational_state_transfer) WebApp written following the [*MVC*](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) development model. It uses:

<sub>2.</sub> Create,
Read,<br>
Update,
Delete.<br>
{:.side-note}

* Ruby for the *Models*
* HTML, CSS and Embedded Ruby *(.erb)* for the *Views*
* [Sinatra Framework](http://sinatrarb.com/) controls the server and routes
* Database and *CRUD*<sub>2</sub> actions handled by [PostgreSQL](https://www.postgresql.org/)

## Links

* You can find [here](http://compendium.devazul.co.uk/) a live demo, deployed using [HerokuApp](https://www.heroku.com/)
* You can look through the ugly code by visiting the [Github repo](https://www.github.com/DetectiveAzul/compendium)
