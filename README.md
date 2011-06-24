# Free Your Self

Free Your Self is a simple static website that FLOSS developers can customize
and use to receive donations for their work. It supports many different
ways to receive donations. Currently these methods are supported:

* Bitcoin
* Dwolla
* PayPal

Methods which are currently being worked on:

* Amazon Payments
* Google Checkout
* Flattr

The more possible methods of easily and conveniently donating, the higher the
chance of getting a donation.

If you have another way in which you would like to receive donations, please
let us know! Github pull requests are preferred, but patches sent to
duke@leto.net are fine too.

# Why?

There many thousands, and possibly millions of FLOSS developers that hack on
code for the benefit of everyone, but most FLOSS developers are not great at
telling the world what they do and how people can support their work.

Free Your Self aims to fix this problem by providing a dead-simple, easy-to-customize
website, which can be hosted for *free* (as in beer), that makes it easy to tell
the world what you do.


# How To Deploy Free Your Self

Free Your Self is designed to be extremely simple to deploy to Github. To deploy
your Free Your Self instance:

* Create a Github account if you don't already have one
* Fork Free Your Self on github
* Modify the _config.yml file and put in your information. Only donation methods
that you configure will show up on your Free Your Self website.
* Modify the HTML/Javascript/etc in index.html to tell the world what you do and how to donate.
* Commit your changes and push the new commit to your fork.
* Your new Free Your Self website will show up at https://USER.github.com/freeyourself .
It will take about 10 minutes for it to show up the first time, but after that the website
will be updated within a few seconds after each push.

# How To Use Free Your Self

Basically, just tell people about it! But here are some ideas to get your creative juices
flowing:

* Add a link to the documentation of your project
* Occasionally send an update to your favorite microblogging service describing how people
can send you donations
* Create a QR code which is a link to your donation page. Then you can print it out, make
stickers, tshirts, the sky is the limit!

# Inspiration

Free Your Self was inspired by Ingy's website http://free.ingy.net . I
immediately realized that many, many people could benefit from something like
that, but I wanted to make it dead-simple to receive donations as well as
being easily configurable.
