# rails-app-docker
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

For that promise to be realised, the packaging and sharing has to be simpler than it currently it.

I curse how many steps I need to do to get something containerised. My time is worth more than that!

If yours is too - you'd love this gem.

