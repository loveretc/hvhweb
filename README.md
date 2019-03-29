# HvH webpage
Basic page for HvH sites, enjoy pasting. I don't need credits but it would be awesome. For any issues contact me on discord @revol#8379, not gonna update this since you don't need a super webpage for HvH.

<h2> How to customize it (for noobs) </h2>
 
- First check that the .css files are working, they should be linked automatically since they use ./css/
- Replace the title with
```javascript
var msg = "title"
```
  if you want to adjust the speed
  ```javascript
  var speed = "value"
  ```
- To change the favicon replace
```html
<link rel="icon" type="image/ico" href="FAVICON">
```
- To change the background replace
```html
<img src="LINK/ROUTE" id="selector">
```
- If you want to customize the main text entirely you will have to change `set_1.css` to whatever you want but if not, then change
```html
</svg> TEXT </a>
```
<h3> Audio </h3>
I prefer using audio before videos because new chrome polices will not play the video until there's an action on the page so you will have to add a play button or start the video muted. If you want to use audio just replace

- Audio works best with .mp3
```html
<source src="directory.mp3" type="audio/mpeg">
```
- To adjust audio volume change this variable
```javascript
audio.volume = X; //value should be X <= 1 and X >= 0
```
<h3> Links </h3>
To customize the links or icons you will need font-awesome if you don't know how to use them, just read the Font-Awesome <p><a href="https://origin.fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use" target="_blank">Basic Use</a></p>

<h3> Colors </h3>
Just simply change the colors in `style.css` and choose what suits you best, I recommend using paletton to get a good color scheme, remember the RGB must be converted to HEX values

<h2> End </h2>
Once you are done just upload the files to your hosting file manager or use your FTP credentials and upload them with any FTP client.
%80 of the code is really messy but I wasn't going to release this and I'm too lazy to change it, if you follow the instructions correctly you should be good.
