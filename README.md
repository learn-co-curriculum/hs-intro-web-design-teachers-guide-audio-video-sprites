###SWBATS
***Students will be able to use audio, video, and sprites to enhance their websites***
+ HTML - understand how to use HTML5 audio and video tags
+ CSS - How to create their own image sprites and render different versions based on hover state.
+ 
CSS - Understand what a sprite it

### Motivation
Videos, audio, and sprites are a huge part of the web. How many people in the room have watched YouTube videos?

###Lesson Plan
+ HTML5 makes it super easy to embed video and audio into your website with these tags:
+ Audio:
  ```html
    <audio>
        <source src="audio.mp3" type="audio/mp3">
        <source src="audio.ogg" type="audio/ogg”> 
        <!-– fallback content here -->
    </audio>
  ```
+ Video
  ```html
    <video>
        <source src="movie.mp4" type="video/mp4">
        <source src="movie.ogv" type="video/ogg">
        <source src="movie.webm" type="video/webm”>
        <!-– fall back content here -->
      </video>
  ```
+ The fallback content is important because there are still old browsers out there that are not good at handling HTML5 audio and video elements.
+ Check out this great [resource](http://caniuse.com/) for checking out HTML5 compatibility
+ *Try adding an audio or video to your personal website.*

+ Another way to spice up  your website is with sprite rollovers.
+ The most common place that you’ll see this is with buttons or links that will change when you hover over them.
+ The best way to do this is to upload one file with multiple images. This jpeg will by default be positioned as a background image then you can add a pseudo class like a:hover that changes the position of the image to display the other sprite. 
+ Here is some sample code:
  ```css
  a {
    display: block;
    width: 30px;
    height: 30px;
    background: url(sprite.png) no-repeat;
  }
   a:hover {
    background-position: 0 -30px;
   }
  ```
+ Give it a shot with the sprite lab on Learn.co.

### Conclusion/ So What?
Audio, video, and sprites provide more interactive content for your website to make your topic come alive.

### Hints/Hurdles
