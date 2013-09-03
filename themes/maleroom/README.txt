----------------------------
CONTENT OF THIS FILE
----------------------------

 * Theme Info
 * Pages Provided
 * Key Features
 * Customisation
 * Credits
 * Issues & bug reporting


----------------------------
THEME INFO
----------------------------

Name: Flexor
Version 1.0
Released: March 2013
Creator: http://themelize.me
Bootstrap version: 2.3.1


----------------------------
PAGES PROVIDED (15)
----------------------------
* Index (index.htm)
* Services (services.htm)
* Showcase (showcase.htm)
* Showcase item (showcase-item.htm)
* About (about.htm)
* Team (team.htm)
* Contact (contact.htm)
* Blog (blog.htm)
* Blog post (blog-post.htm)
* Login (login.htm)
* Register (register.htm)
* Pricing (pricing.htm)
* Starter (starter.htm)
* Variations (variations.htm)
* Elements (elements.htm)

--------------------------
KEY FEATURES
--------------------------

* Built on Bootstrap 2.3.1
* Font Awesome icons
* Bootstrap JavaScript implemented: dropdowns, tabs, modals, accordion
* Fully responsive (wide, normal, narrow, mobile)
* Mega Menus
* Modal login box
* Easy to customise
* Starter template snippets (starter.htm)
* Starter CSS files
* jQuery Quicksand plugin
* jQuery Flexslider plugin
* Stellar.js parallax backgrounds
* Simple & clean design
* Valid HTML5
* 4 preset colour skins
* 5 different backgrounds
* Google font (Roboto)


--------------------------
CUSTOMISATION
--------------------------

1. Overriding Colour Skin
--------------------------
The theme offers 4 colour schemes (Orange is default):
Orange: light: #FF5821, dark: #E34619
Blue: light: #00a8cc, dark: #0188a6
Green: light: #00bb5c, dark: #009748
Lavender: light: #ad4dd3, dark: #8c3daa


Each additional colour scheme has a separate .css file within the /css directory (NOTE: Orange is default so rolled into the theme-style.css file):
1. colour-blue.css
2. colour-green.css
2. colour-lavender.css

These files can be used as an example of how to implement your own colour schemes.

Example - Add the following to your <head> tags below the "<!--Your custom colour override-->": <link href="css/colour-blue.css" id="colour-scheme" rel="stylesheet">

NOTE: 
You will need to do this on all pages to implement site wide.
The "colour-scheme" ID tag is only required if you want the jQuery colour switcher to be functionality.
Quickest way to hide the colour switcher is to add .colour-switcher { display: none; } to your CSS.


2. Overriding Other Styles
--------------------------
Similarly to colour overriding the theme also offers and automatically loads a skeleton file called "custom-style.css" which can be used to override the theme structure & media queries.
This file is found within the /css directory and is well commented to provide instruction.


3. Adding New Pages
--------------------------
The theme comes with a starter template of snippets (starter.htm) which can be copy & pasted to start new pages.
We also recommend using http://bootsnipp.com.


--------------------------
CREDITS
--------------------------

* Team photos: http://www.flickr.com/photos/vectorportal/sets/72157622868867274/
* Blog photos: http://www.flickr.com/photos/xjrlokix/ (Ben Fredericson)
* Showcase images by http://www.isabelarodrigues.org (DO NOT REPRODUCE)
* Background images: http://photodune.net/user/alexwendpap/portfolio


--------------------------
ISSUES & BUG REPORTING
--------------------------

If you run into issues or find a bug which is not related to Bootstrap itself then please report the bug to us at info@themelize.me