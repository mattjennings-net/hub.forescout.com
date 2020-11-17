# hub.forescout.com
- Content Hub at hub.forescout.com per work with Idio/Episerver Vendor

- Repo created by Matt Jennings of Forescout (matt.jennings@forescout.com)

## Build Plan

1. Figure out max width of website. Min width will be 320 pixels.

2. Use Aria landmark tags like in the image at https://www.mattjennings.net/accessibility-for-the-web.

3. Use the same font family as on https://www.forescout.com/.

4. For the <banner></banner> tag, try adding in an SVG for artwork behind gold color. 

5. For the next section ("Feature of the Week") using a <main></main> tag. Also have the image be inside an <img /> tag with a fixed size to ensure the aspect ratio is correct.

6. For the "All | Insights | News..." section add then in a <nav></nav> tag even if there are no links.

7. For the "Insights, News..." sections that show the images with the transparent <div></div> tag colors above them, use z-index without absolute positioning (https://stackoverflow.com/questions/9674988/z-index-without-absolute-position).

Also, have the grayscale images be background images with a background-size: cover property.

