WPLoremPix
Author: Lee Rickler
Author link: http://rickler.com
Tags: placeholder, pictures, images, wordpress
Requires: WordPress 3+

WPLoremPix WordPress plugin that pulls in random placeholder images based on http://lorempixel.com
Can be used in any page or post as well as sidebar.

== Installation ==

Upload in normal way, to your `/wp-content/plugins/` folder.   

1. Upload `wplorempix` folder to your `/wp-content/plugins/` directory
2, Activate the plugin
3, Add the shortcode and optional attributes to any post, page or text widget to display the placeholder image.

== Shortcodes ==
The most basic shortcode that can be added is `[wplorempix]`
This will display a random abstract image at 800px

= Optional attributes =
Attributes that can be set - with examples:
Width : width=200
Height : height=200
Hue - turns image into greyscale : hue=g
Genre - displays images from particular genre - see below for full list : genre=sports
Dummytext - adds vertical text to the left side - note: no spaces between words : dummytext=mytext 
Picno - adds specific picture number between 1 and 10 : picno=1

To use the full set of attributes you might use something like:
[wplorempix width=200 height=200 hue=g genre=transport dummytext=mytext picno=10]

Genres:
abstract
animals
city
food
nightlife
fashion
people
nature
sports
technics
transport

= v1.0 =
* Premier release