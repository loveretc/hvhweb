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
audio.volume = 0.3;
```

