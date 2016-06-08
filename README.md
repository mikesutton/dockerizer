# Dockerizer
A gem to automagically dockerise any local rails app.

**What**

Rails-App-Docker is a gem that sits outside your rails apps. The vision is that you simply run:

`rails-app-docker <rails-app-folder-name>`

And the gem will walk you through a workflow through some preshipped recipes and setup:

1. Containers you need, including:
  - Your database
  - Rails
  - Redis
  - web server/application server
  - anything else

2. Create the image(s) 

3. Start the containers

**Why**

The promise of docker is that you can package up and share you app with little or no ambiguity.

For that promise to be realised, the packaging and sharing has to be simpler than it currently it. With docker and rails right now, if you are asked to setup another person to work on the code base (say a designer for example), you typically disappear into the world of googling for tutorials and emerge 2-7 days later cursing life. 

And you might still not have the docker container that was such a great idea for sharing the app

I curse how many steps I need to do to get something containerised. My time is worth more than that!

If yours is too - you'd love this gem.

