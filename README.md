###SWBATS
+ HTML - understand how to use HTML5 audio and video tags

### Motivation
Videos and audio are a huge part of the web. How many people in the room have watched YouTube videos?

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

<b>Design Principles - typography</b>
+ What is typography? Typography can simply be described as the art of type. It's everything you can think of – like fonts, sizes, and readability.
+ The basics

<img src="https://s3.amazonaws.com/after-school-assets/css-selector6.png">

+ <b>Sizing</b>
  + The Type Size, also called the Cap Height, is the overall height of capital letters in the formation of words.
  + The Ascender is the upward tail on letters like h, l, t, b, d, and k.
  + The Descender is the downward tail for letters like g, q, and y.
  + The Counter is the white space located inside letters like o and p.
  + The X Height is the height of the letter, and does not include ascenders or descenders.
  + Baselines are the boundary that the lowest part of the letter rests on. Take a look at the y, p, g, p and y letters in the illustration above. The solid line they are resting on is the baseline.
+ <b>Kerning</b>
+ Have you ever seen a paragraph or advertisement that made the letters appear either s p a c e d w a y out or scrunched all up so it was hard to read? The effective use of kerning and leading will fix that problem. Kerning is the space located between individual letters of a word. If you can remember the kernels on an ear of corn, it’s easy. When the kernels of corn line up, it makes a nice neat row.
+ If the kerning is off, so will the appearance of the word or line of text you are working with and it will be harder to read.
<img src ="https://s3.amazonaws.com/after-school-assets/css-selector7.png">
  + Leading is the space between the lines of text. If you look at the illustration above, you will quickly notice the space between line one and two is too close, giving the impression of not enough space. By adjusting the amount of leading between lines, the text becomes much more readable and less pinched.
  + How do you want your text to line up? Is this a standard body of text, a headline or are you in need of a more professional finish? Depending on the type alignment, you may inadvertently create the wrong impact based solely on the placement of your message.
+ <b>Type Alignment</b>
  + Default writing techniques will use left alignment to create easy to read text for the reader. Casual letters, unpublished manuscripts, and basic paragraph styles tend to fall into this category.
  + Center alignment is used to draw attention and is used a majority of the time for Headlines or Titles. Newspaper headers, book titles, and report titles are excellent examples of center alignment.
  + Right Alignment is a clean crisp professional look and is used quite a bit for corporate business letters, return address labels, business cards and a variety of other applications where a formal style of alignment is needed.
  + Justified alignment is usually reserved for newspaper print and body text for textbooks, and is more difficult to work with. This type of alignment creates perfect alignment on both the left and right margins without regard for the actual characters. This can lead to a condition called tracking, or the creation of “rivers” of white space throughout the text body. If this happens, reduce the tracking gradually to correct the illusion.
+ <b>Font</b>
+ Now that we know how to identify the parts, make sure the spacing is correct and we’ve decided on the image we want to portray, selecting what your message will look like is paramount to leaving the gravy off the mashed potatoes at dinner. You’re still going to have a nice dinner, but if you want to get saucy, pick a type category that fits.
  + <b>Serif</b> type has extensions or strokes on the ends of the letters. Times New Roman is a perfect example of this. This type of font is easy to read for longer pieces and tends to be a little more conservative. If you do not deliberately choose another font, most programs default to the Times New Roman style.
  + <b>San-Serif</b> does not have extensions or strokes on the ends of the letters and are used heavily for labeling, headlines and titles. This is also easy to read with a more contemporary feel to it. Children’s books use this because it is more easily identifiable as children are learning the alphabet.
  + <b>Script,</b> symbols and decorative type are all styles of type categories to create a specific image or message. Weddings might lean more toward the fluid motion of a script type while a child’s birthday might be more inclined to like a decorative font from a favorite movie.
+ Whatever font family you choose bears careful consideration in the design of any piece. Here are a few suggestions to get you started:
+ The font you decide on should not dominate the piece. Fonts are like exquisite jewelry to be placed in just the right context to insure maximum results.
+ <b>Tips</b>
  + Use care when mixing fonts. It’s kind of like mixing stripes and plaids. When in doubt, stay with something a little more conservative then add one splash of notice me.
  + Use consistency in your layouts. If you start out using an Arial font for the headers, stay with the same font throughout the piece.
  + Newsletters with columns will look better if you use the Justified Alignment. Make sure you don’t create rivers of white space though.
  + Use an 11 or 12 point font size and a serif type for maximum readability.
  + Use Italics and Bold to point out areas of interest or draw quick reference to information.
  + Use color for emphasis. Remember, reds draw the most attention if used correctly. It is amazing what one spot of red can do for an ordinary ad.
+ Next time while reading your favorite blog or newspaper, observe the fonts, line heights (the distance between each line), line lengths (how many letters per line), and font weights (bold, normal, light). CSS3 gives you great control over fonts and text, so an understanding of the basic rules of typography will come in handy as you design and build websites.
+ <b>Steve Jobs calligraphy story</b>

<b>Sprites and Rollovers</b>

+ Another way to spice up  your website is with sprite rollovers.
+ The most common place that you’ll see this is with buttons or links that will change when you hover over them.
+ The best way to do this is to upload one file with multiple images. This jpeg will by default be positioned as a background image then you can add a pseudo class like a:hover that changes the position of the image to display the other sprite. 
+ Here is some sample code:
  + a {
  + display: block;
  + width: 30px;
  + height: 30px;
  + background: url(sprite.png) no-repeat;
  + }
  + a:hover {
      + background-position: 0 -30px;
  + }
+ Give it a shot with the sprite lab on Learn.co.

### Conclusion/ So What?

### Hints/Hurdles
