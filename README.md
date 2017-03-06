# feeder
Super simple RSS reader.  Given a file of RSS or Atom feeds, sends an email with links to new articles.

This is a modified version of [Dr. Drang's RSS aggregator](http://www.leancrew.com/all-this/2013/06/my-rss-failure/).  It might have been
a failure for him, but the rough idea worked for me.  To fit my reading style, I changed it to send a single email with links to all of the new articles found, rather than an individual email for each article.  Instead of running the script frequently, I have it scheduled for twice a day.

## Installation

`pip install feedparser pytz pyyaml pystache`

Edit config.yml to have the values match your email account and feeds.  You can also
edit the inlined Mustache template to change the format of the email.

This script only sends HTML email.  Sorry, elm users.

## Usage
`python feeder.py config.yml`

## TODO
Nothing, it works fine for me.
