UtilityBelt
===========

Projects/libraries I currently use as the need arises 

Web Developement
================
Language preference: 
small, static: html5/css/js/jquery
large, dynamic: Coffeescript/Jade/Stylus

Javascript
==========

DOM Selection and Manipulation
==============================
jquery

DOM Events
==========
jquery
waypoints - though it's triggered differently on different devices!
fittext - but there's a gist that's smaller based on it at https://gist.github.com/3194893

DOM animations
==============
jquery - for show/hide and fadeIn/fadeOut
jqueryui - for more transition effects

General Utilities
=================
underscore - templating, things javascript should have naturally, all around awesomeness
url - easy parsing of a url
q - awesome promises/D implementation
require.js - when dependencies start having dependencies, use this amd loader

JS testing
==========
mocha/chai - awesome testing, though I don't have this automated yet like I should
jstestdriver - for tests that need to scale

Webserver
=========
heroku app skeleton gist: https://gist.github.com/3194901
Express
 - To scale up, use redis for sessions
 - Don't forget to use crsf connect module for safety

Websockets/live connections/collaborative apps
===========================
socket.io - but I'm looking for another that scales easier
racer.js - looks extremely promising, but haven't gone to prod with it yet.

Webserver utils
===============
rss - pretty simple rss xml generation

DBs
===
mongodb - great nonrelational document database
redis - fast scalable keystore IPC or session data use
memcached - super fast non scalable keystore
postgresql - best relational db

MVC
===
unsure of a good one for node as of yet

Platforms
=========
heroku - awesome, but doesn't yet support websockets sadly
aws - great, but a pain to setup the first time

Misc
====
Tangle - for simple interdependency stuff on client side