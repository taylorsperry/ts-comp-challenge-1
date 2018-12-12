# Static Comp 1
This is the second project I completed at Turing, during the second and third weeks Mod 1. The goal was to match the style of the provided comp as closely as possible, with some latitude given to the content itself. We could use flexbox, but not grid. We were also asked to incorporate media queries and test for responsiveness on various screen sizes. 

I ran into several challenges with this project:

The first, and I imagine the easiest to solve, was that I couldn't figure out how to size the background images of my cards properly. I tried background-size: cover and background-size: contain in my CSS, and adjusting background: position, but that didn't seem to work. I also tried the overflow property, but nothing I found sized the images down and centered them in their containers. 

I used the display: flex property/value on several parent containers, which allowed me to space children elements in ways that matched the comp. This was especially useful for the header. I ran into problems, though, in the card container. For larger screens, I wanted to keep the cards evenly spaced by using the "space-evenly" value on the "justify-content" property. However, when I wanted to override that property for smaller screens, I couldn't get rid of the awkward space between cards, even when I reset the "justify-content" value to "center." I'm not sure why this is. 

Perhaps relatedly, when I got down to the much smaller screen-sizes (around 350px in width) content started flowing out of the cards, and at 320px I lose the bottom padding on my cards altogether. I'd set 320px as a breakpoint, but I don't see how I lost the padding. At this width, the cards all stack on top of one another, with no space between them. 

## Built With:
1. HTML
2. CSS

### Comps

Here's what I built. (Split into two screenshots.)
<img width="1439" alt="screen shot 2018-12-12 at 12 41 23 am" src="https://user-images.githubusercontent.com/43555476/49854282-eb5ded80-fda6-11e8-961c-70b707b96f5f.png">
<img width="1440" alt="screen shot 2018-12-12 at 12 41 41 am" src="https://user-images.githubusercontent.com/43555476/49854298-f44ebf00-fda6-11e8-945f-769094401d59.png">

And here's the provided comp. 
