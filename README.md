Sounds.js
=========

Small library for playing sounds in games (like those written in 3D Game Programming for Kids!)

Support several sounds:

````javascript
Sound.bubble.play();
Sound.buzz.play();
Sound.click.play();
Sound.donk.play();
Sound.drip.play();
Sound.guitar.play();
Sound.knock.play();
Sound.scratch.play();
Sound.snick.play();
Sound.spring.play();
Sound.swish.play();
````

In addition to `play()`, each sound can be repeated (and stopped):

````javascript
Sounds.click.repeat();
setTimeout(function() {Sounds.click.stop();}, 1000);
````

Can be imported from the gamingjs.com site with:

````html
<script src="http://gamingjs.com/Sounds.js"></script>
````
