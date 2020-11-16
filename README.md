Heroku buildpack: MongoDB Tools
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) containing the [MongoDB](http://www.mongodb.org/) tools.

Usage
-----

Example usage:

    $ heroku create --stack cedar --buildpack http://github.com/freightview/heroku-buildpack-mongodb.git

    $ git push heroku master

    $ heroku run mongo --nodb
