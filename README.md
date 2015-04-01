# twemojify-awesome
twemojify-awesome is a fork of emojify that can run twemoji-awesome by default

Credits:
=============================================================================================================
*twemojify-awesome http://ellekasai.github.io/twemoji-awesome/
*emojify http://hassankhan.me/emojify.js/

Use
=============================================================================================================
Add the required lines to the <head> part of your HTML code:

<script src="emojify.js"></script>

Now type in an emoji keyword in your HTML, for example :smile:, and run emojify using twemojify.run()

You can optionally pass an element to twemojify.run() to restrict the emojifying to that object only:

twemojify.run(document.getElementById('my-element'))

Config
=============================================================================================================

twemojify.setConfig({
  size : 'twa-lg'           // You can change emoji sizes via twa-lg, twa-2x, twa-3x, twa-4x and twa-5x.
});
