Swipebox simplifyed
================================

A touchable jQuery lightbox.

[View project page](http://brutaldesign.github.com/swipebox)

##What is Swipebox ?

Swipebox is a jQuery "lightbox" plugin for desktop, mobile and tablet.

##Features

- Swipe gestures for mobile
- Keyboard Navigation for desktop
- CSS transitions with jQuery fallback
- Retina support for UI icons
- Easy CSS customization

###Compatibility

Chrome, Safari, Firefox, Opera, IE8+, IOS4+, Android, windows phone.

##Usage

###Javascript

Include jquery and the swipebox script in your head tags or right before your body closing tag.

`<script src="lib/jquery-1.9.0.js"></script>`

`<script src="source/jquery.swipebox.min.js"></script>`

###CSS

Include the swipebox CSS style in your head tags.

`<link rel="stylesheet" href="source/swipebox.css">`

###HTML

Use a specific class for your links and use the title attribute as caption.

`<a href="big/image.jpg" class="swipebox" title="My Caption">`

###Fire the plugin

Bind the swipebox behaviour on every link with the "swipebox" class.

`$(".swipebox").swipebox();`


###Need a couple of options?

`useCSS : true, // false will force the use of jQuery for animations`

###Changes compared to the original version <http://brutaldesign.github.io/swipebox/>

- removed auto-hide feature (title and action bar)
- replaced icons (png/svg) by fonts (incl. IE8 support)
- different default style