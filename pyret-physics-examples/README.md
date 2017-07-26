Here's a sketch of some of these simulations/games.  In each, I give first the
library code that uses reactors and tables, and which contains a solution.
Then I give a link to the starter code a student would see.

Note that in the solution files, I've modeled how I would want students to have
written examples in order to help derive the function body.



First, simple 1-d motion made into a programming game.

![1d motion](http://imgur.com/ZxIKUgX)

Library:

https://code.pyret.org/editor#share=0B32bNEogmncOaDNJQXFJb1B5OEk&v=64c077c

What a students sees:

https://code.pyret.org/editor#share=0B32bNEogmncOTnYyX1ZmN05GblU&v=64c077c

The idea is that a student figures out:

- The initial x position, and expresses it in code
- The change in x, and expresses it in code
- The function from t to x position based on these, and expresses it in code

Then the simulation succeeds if these points are correct.  I'm using simple
circles and targets for all of these, but these could be customised to be a car
and a finish line, a bee and a flower, etc, whatever makes physical sense for
simple linear motion.



Second, 1-d motion with reflection.

![1d reflection](http://imgur.com/cpq840T)

Library:

https://code.pyret.org/editor#share=0B32bNEogmncOUXl2Z082Z0JYdWM&v=64c077c

What the student sees:

https://code.pyret.org/editor#share=0B32bNEogmncOWUdSZ2MzY1pFMlU&v=64c077c


We might use this example to introduce inflection points in time in physics,
modeled by an if expression in the program.  The student again figures out
starting conditions, the x delta, and then the time-based formulation of
reflection (this is actually not trivial at all to write out).


Third, 2-d motion based on time; a natural extension of the first example.

![2d motion](http://imgur.com/EIKuZa3)

Library:

https://code.pyret.org/editor#share=0B32bNEogmncOSTZMeFNSa2xnMG8&v=64c077c

What the student sees:

https://code.pyret.org/editor#share=0B32bNEogmncOUFNVbC1UaDhsZkE&v=64c077c


Here, the programming is basically the same as in the first example, just
replicated twice with two different initial conditions, and functions for
updating.



Fourth, 2-d differential motion to reflect off of walls; I'm not sure how to do
this without doing it differentially.  Note that I change the names of the
functions here from "x-at-t" to "next-x" and so on, to reflect the differential
nature.

![2d bounce](http://imgur.com/3s1YUgc)

Library:

https://code.pyret.org/editor#share=0B32bNEogmncOQkZIVWh4eFMzamc&v=64c077c

What the students see:

https://code.pyret.org/editor#share=0B32bNEogmncOSms0ZW5ic05KN2c&v=64c077c


Fifth, 2-d differention motion to do free-fall, where the game is to avoid
obstacles on the way to a target.

![gravity](http://imgur.com/HaFYbkC)

Library:

https://code.pyret.org/editor#share=0B32bNEogmncOVkxJMXdZRkRuelE&v=64c077c

What the student sees:

https://code.pyret.org/editor#share=0B32bNEogmncOZzF5SzUyUW9qdUk&v=64c077c


A few notes:

I haven't gotten to an example with acceleration terms yet, and I want to get
this out now in order to solicit feedback.

These are far from exhaustive, and are constrained by what I could
realistically build in a few hours this morning (I'm on west coast time).  It's
possible to get lots of different guidance and error conditions into the
simulations themselves, which I started realizing is a pretty cool way to build
up a program.

I also think there are opportunities to personalize the games with images from
the web (or even just colors) that I haven't yet explored.


