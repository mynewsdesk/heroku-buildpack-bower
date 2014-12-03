heroku-buildpack-bower
======================

Installs and caches bower.json dependencies.

Was created for usage in a rails app where we wanted to use straight up bower
instead of asset gems as described in this blog post:

http://joelencioni.com/blog/2014/01/03/integrating-bower-with-rails/

## Prerequisites

Expects to have a bower executable installed via the nodejs buildpack.

## Usage

Use with the multi buildpack:
https://github.com/heroku/heroku-buildpack-multi.git

Link this repo in your .buildpacks after you have installed nodejs + bower.

## Inspiration

Some ideas taken from:

https://bitbucket.org/samcday/heroku-buildpack-bower

https://github.com/ejholmes/heroku-buildpack-bower
