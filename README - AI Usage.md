Midterm 1: Testimonial
AI Usage Documentation and Explanation

Here is a list of some of the prompts that I used and how I implemented them or adapted them:


1. The width of the screenshot I sent is 1440px, can you approximate the dimensions of all the people's testimonial boxes in pixels please?
(*included the screenshot of the design)
ChatGPT gave me its estimation on the sizing for each box, taking into account the 1440px width of the entire grid.  I ended up having to adjust the width and height many times and I also
watched a Youtube video on how to implement a CSS grid to organize the boxes better.

3. How can I move divs in scss/html to align sections?
ChatGPT told me that I could use a flexbox or a grid to place divs into “grid items” and then assign rows and columns to them, including a basic structure as an example. I then researched
further and watched a YouTube video on how to use a CSS grid. ChatGPT also included advice on when to use a flexbox (for rows or vertical alignment), a grid (for complex multi-row layouts),
and position, which should only be used for overlapping or very specific placement.

5. How do I place an image in a div and place it where I want it?
The answer included multiple options, such as using background-image: url(path to image) or <img> inside of the <div> but laying it using z-index. That is how I found out that z-index is an
attribute that I could give to an element, paired with position: relative (or absolute) to adjust which element I wanted covering the other. My quotations image kept covering the headline of
the testimonial box so I assigned the quotations image position: absolute and z-index: 0 and then assigned the headline with position: relative and z-index: 1 and that fixed my problem.
