# Context Free

##  Who is this programming language for?
This language is for people who want to generate fractals 

## What is easy to do in this language? Why is it easy?
Drawing simple shapes in all sorts of combinations is easy because there are
built in to the language. Even drawing fractals with simple shapes is easy
because nesting rules is so easy.


## What is hard to do in this language? Why is it hard?
It's hard to do free drawings because to do that, you'd have to break them up
into squares and circles and then "smear" them over the areas you want drawn
recursively. It's also hard to draw shapes that are alike in some ways but
have suble differences. (In my case, I wanted to be able to specify the position
of the hands on the clocks.) In version 3 of Context Free, however, it appears
this becomes easier because parameters can be passed to shapes.


## How did you learn how to program in this language?
I learned through the documentation, the example programs, and trial and error.
The documentation was helpful, but since it was for the wrong verison, there
were some things (parameters to rules) that I couldn't figure out.


## What is the underlying _computational model_ for this programming language? 
First, it tries to draw the startshape. If it doesn't know how to draw that
shape, it looks for a rule for that shape and draws each shape in that rule one
at a time.


## What do you think is interesting about the ContextFree program you wrote?
It's a fractal! With clocks!
