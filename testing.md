---
layout: page
title: Testing
header: Testing MD
group: navigation
---
**DLSign

DLSign is a digital signage framework that takes advantage of Databoard (See: [https://github.com/jblyberg/databoard](https://github.com/jblyberg/databoard)).  Databoard allows you to grab data from virtually anything on your network and present it programatically.  DLSign is intended to allow you to rapidly develop and deploy dynamic, data-driven digital signage.

DLSign takes advantage of Twitter Bootstrap ([https://github.com/twitter/bootstrap](https://github.com/twitter/bootstrap)) to provide you with a large array of attractive design elements to use in your signage.  By leveraging Twitter Bootstrap, DLSign lets you focus more on deploying signs and less on designing them.

[![image](http://farm8.staticflickr.com/7062/6884553189_8d99426f25_m.jpg)](http://www.flickr.com/photos/jblyberg/6884553189/in/photostream) [![image](http://farm8.staticflickr.com/7052/6884553505_ef25349809_m.jpg)](http://www.flickr.com/photos/jblyberg/6884553505/in/photostream) [![image](http://farm8.staticflickr.com/7057/6884553587_c79e3daa2f_m.jpg)](http://www.flickr.com/photos/jblyberg/6884553587/in/photostream)

([Additional DLSign screenshots](http://www.flickr.com/photos/jblyberg/sets/72157629338788147/))

**Usage

First, you'll probably want to check out Databoard, and play around with that a bit: get some viable data sources up and running, etc.

Then edit `include/databoard_auth.php`, substituting your Databoard username and password that you set up when you implemented Databoard (highly recommended).

Look at the examples provided in the `signs/` folder.  They're not going to work out of the box for you, obviously, but you can get a good sense of ho to go about creating your own sign.  You can use the `_template.php` file as a template.

**To Do

Lots more, but I get so many questions about our digital signage at the library that I wanted to get something released that was somewhat usable by other libraries.

Enjoy!