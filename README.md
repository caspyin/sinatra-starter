Sinatra Starter App
-------------------

A basic template that you can fork to create a Sinatra application.

Usage
-----

There are a couple of options to get started:

* 1. Use Github's download feature to start off with an un-versioned code base.
* 2. Fork this project and run `git archive` when you want to create a new app from this code

    $ mkdir /path/to/new_app
    $ git archive master | tar -x -C /path/to/new_app

Now initialize new_app with git like you would for any other new project.

To run the application you can either do it the default Sinatra way or use Shotgun.

**Sinatra:**

    $ ruby app.rb

Visit http://127.0.0.1:4567/ in your browser.

**Shotgun:**

    $ shotgun app.rb

Visit http://127.0.0.1:9393/ in your browser.

The index page lists some next steps to take but if you're in a hurry just delete the `public/blankslate` folder and add your own content to the views.

----

**TODO**

* Ask for permission to use background image
* Evenly distribute resource links in the footer
* Wire up DataMapper and a nosql ORM
* Set session_secret for shotgun
* Auto load dm migrations to $LOAD_PATH
* Wire up a CSS Framework (create a rake task to give you the choice of which one)
* Create a rake task to archive the repo and initialize a new git repo with your app name
* Add more information on getting started to blank slate
* Add config, before, helper blocks
* Support sass, possibly compass
* Add ability to see debug info in a div on any page while in development