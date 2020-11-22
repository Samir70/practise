# Practise for progress
I aim to do two things: learn new skills and remember them!

I think there is benefit to redoing past projects, perhaps in a different format. (My first version of lights out was with React, then I used Vue. Now I have added GSAP to the Vue version. This saves having to think of new ideas, you just focus on learning the new tech.

Also: I sometimes find that I am forgetting as much as I learn. So the things I think are important to remember need to be revised. The projects I put on here are intended to be small enough to redo completely in a short space of time. Ideally: one or two files. The aim is to copy the outcome not the implementation. 

## Projects
### lights out
Uses Vue and GSAP, with animations to catch the eyes at the start and indicate clearly which lights are changing state when one is clicked. There is also a little animation at the end. 

The first gsap.from() fires when the page is loaded. I did worry that Vue may not have put in place all the buttons by the time gsap fired, but it all went well. The other gsap commands are called within the Vue methods to react to user input or the puzzle being solved.

[Click here](https://samir70.github.io/practise/lights-out.html) to play.
