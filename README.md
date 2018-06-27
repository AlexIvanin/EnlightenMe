Enlighten Me
================

## Social web course platform

### Key points:
* Ruby 2, Rails 4
* PostgreSQL, Riak, Redis
* Apache Solr search engine
* Node.js and socket.io for websockets and live streaming
* Only clear REST API requests
* Behaviour-Driven Development
* Git-flow for development process

# Project scheme
* Server-side (this repo)
* Client-side static web app (soon ...)
* Client-side mobile native app (more soon ...)

# Client-server architecture
* All hail to JSON
* Use socket.io to websocket and realtime
* Redis is great for pub/sub

# Data scheme
* PostgreSQL - static, almost immutable data (profiles, locations, courses, lessons, reviews,  blogs, books ...)
* Riak - dynamic mutable data need small request time (tasks, messages, comments, questions ...)
* Redis - caching for performance, caching indexes for fast searching, pub/sub

## Behaviour-Driven-Development:
* Write test. Run test. It fail.
* Write code. Run test. Its OK.
* Refactor code.

![BDD](http://twobitlabs.com/wp-content/uploads/2011/04/red_green_refactor-e1302975375893.jpg)

# Development process
* Create service in api
* Implement this service in front-end app
* Implement this service in mobile app
* ?????
* PROFIT!!!  
  
Wut?
Parallelize!  
  
For example:
* Create task service on server
* In the same time create static pages
* Create front-end code for implement this service
* Int the same time realize this in mobile app

Created by Alexey Kuznetsov and Alex Ivanin (c) 2013 - 2014
