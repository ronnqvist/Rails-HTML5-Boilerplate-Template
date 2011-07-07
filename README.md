Rails 3.1+ Support
===================
Due to the major differences between asset handling introduced in Rails 3.1 I have decided create an entirely new Github project for Rails 3.1 support. A rails 3.1 compatible template can be found here: https://github.com/russfrisch/h5bp-rails

Change Log
===========
6/5/2011 - Updated HTML5 Boilerplate assets to pull from my <b>unmodified</b> fork of Paul Irish's HTML5 Boilerplate repo.<br>
 This was done to prevent immediate breakage of this template when files with version numbers in the filename are updated.<br>
 If you notice that my HTML5 Boilerplate fork has gotten stale before I do, please let me know.

About
======
A Rails application template used to setup a new Rails app using Paul Irish's HTML5 Boilerplate (http://html5boilerplate.com/)<br>
This template was inspired by Logan Leger's Rails 3 JQuery Template (https://github.com/lleger/Rails-3-jQuery)

How to Use
===========
Rails 3:<br> 
`rails new <appname> -m <path/to/rails3.rb>`<br>

Can also be run directly from github:<br>
`rails new <appname> -m https://github.com/russfrisch/Rails-HTML5-Boilerplate-Template/raw/master/rails3.rb`<br>

Can also be applied to an existing project, but will need some integration by hand (and your application.html.erb is pretty much overwritten):
`rake rails:template LOCATION=https://github.com/russfrisch/Rails-HTML5-Boilerplate-Template/raw/master/rails3.rb`<br>

Rails 3
================
This template does the following:

1.  Removes default Prototype/Scriptaculous JavaScripts and Rails driver
2.  Downloads the latest JQuery Rails driver and places into the javascripts folder
3.  Downloads HTML5 Boilerplate assets: JavaScripts, Stylesheets, icons, .htaccess, etc.
4.  Creates an empty application.css and then adds to it an @import to import the scaffold.css.
5.  Replaces the <i>contents</i> of default application.html.erb layout with the contents of HTML5 boilerplate's index.html
6.  Modifies the updated application.html.erb to add back in the appropriate default Rails content 
7.  Updates javascript :defaults expansion to include jquery, plugins, and rails driver.

Rails 3.1+ Support
===================
For Rails 3.1+ support please see this template: https://github.com/russfrisch/h5bp-rails

Push Requests
==============
This is my first template so if there is anything that can be done better or you would like to see tweaked, please send me a push request.
