Link to Deployed website: https://slider137.netlify.app/
(if doesn't work properly try refreshing your browser)

Approach:
i first tried to tackle how a slider actually work.(it was not as easy as it seems, it was a bit tricky.)

few problems i faced were:
1. How sliding animation going to work on loop.
2. How the progress Bar going to work.
3. How many number of card should visible on screen according to screen size and according to that number how the progress bar is going to resize itself.

with that said i started making a basic template for the slider container with two navigation handles on both sides.

Firstly, I implemented the functionality for side-to-side navigation in the script.js file. Next, I created a function to calculate the progress bar and integrated the same slider scrolling functionality for the progress bar. To handle the resizing of the progress bar, I utilized a throttle function from the internet. This allowed me to efficiently recalculate the calculateProgressBar function in script.js, enabling the progress bar to resize correctly. Beyond that, I focused on CSS for transitions and ensured keyboard navigation by enabling tab key functionality to move between cards.

How to run on your device: 
Just clone this repo and its good to go.
I also deployed this project on netlify as asked, Link for that is on the top.