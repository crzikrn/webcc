# Learning Web Design & Development through Creative Coding - Beginner's Course PART 1

Hello, and welcome to *learning web designing through creative coding*. This course is an introduction to web designing taught in designer perspective. This is NOT a course for DOM handling, but a beginner's course on Web Design. I focus on embedding the concept of computer languages simply doing. Doing in creative coding. Sounds counter-intuitive right?

## Reasons for developing this course

Many times beginners are pushed away from learning web designing for the heavy emphasis in learning HTML & CSS. There is no concrete plausibility in learning the basics first for better understanding web designing. You really start without understanding anything about communications with a computer. There is no *fun* introduction to the conceptual framework of web design. I mean, considering HTML to be a sort of a computer communications tool, most format of teaching communications with computers of any complexity is largely focused in memorizing syntax. No wonder many people are turned off. It's boring and there is no sense of purpose.

So for this class we will simply jump into making things. If you aren't going to understand it anyway, why don't you have fun while at it?

I wanted to move away from the traditional teaching method of web development. Instead of going through the basic essentials and the bare bones building blocks of HTML & CSS, I wanted to start with a hands on approach like when a kid learns to color by just giving them a crayon and a coloring book. And so we start with creative coding, to learn web.

## What is required

Just be you. I'll make the coloring book you just *crayon*. Don't fret it. We will learn by asking questions and simply wanting to do more. Essential be ready to ask questions and wanting to take the next step. All the answers are prepared.

## What you can expect
Hopefully, I get you to understand what it means to communicate with a computer first. Since this is originally an offline class, I'll be present in the classroom to guide the understanding of computer communications. If you want to be technical, we will use already made templates (coloring book) on **codepen.io** and start going wild. Afterwards, I'll do the traditional way of teaching the basics of web designing (the 90s way!)

# Projects

There is basically 3 projects for the first section.
- Creating your own brush stroke
- Making a brush pattern
- Making a brush algorithm

What does all this mean? We're learning to make our own brushes; we will draw with our brush; and finally we will make the computer draw with our brush. Simple as that.

# Template Links
Let's get started! Here are a few methods to get started. All will be explained, just choose one of the many ways.

## Web Editor for p5.js
Best would be to just go HERE! (https://alpha.editor.p5js.org/) And Do our projects here :) It's in alpha version so beware! 

## Codepen.io
If you want to save what you did, you can either make an account at https://codepen.io and fork the empty template for a p5.js, I'll explain everything in class so don't freak out!

## Code Editor
And if you are adventurous enough we can learn the ways to do it on our computers with a code editor. I'll go around and do a 1:1 tutorial for this. However, be ready to already have a code editor. Atom[https://atom.io/], Brackets[http://brackets.io/], Sublime[https://www.sublimetext.com/], to name a few.

# Class Excercies
No matter where you go, there will be always Homework. Oh, the dread! It's the best way to learn though.

## Class 01 - Learning what Coding is... then make a Paint App.
What!? We just learned what "coding" meant, how can we make an app right away? Well, just listen carefully to what I have to say. There's no need to scare off beginners, at all means we have to invite them with open arms. It *IS* super easy to make a functional app, it just ain't perfected yet. So yeah, within 10 minutes of your first lecture you have your own paint app, how amazing is that?

Let's use an *Empty Example* File from codepen.io; Fork it!
- [Empty p5js Example](https://codepen.io/byunk/pen/oWdWNq)

We'll start writing our code inside the :
```javascript
function draw(){
  //We'll write here!
}
```
The first line will be drawing a cricle for a circular brush stroke.

`ellipse(250,250,50,50);`

Ok. Great. Ta-Tan! We can now draw a circle. The first two numbers are the location coordinates for the circle. It simply means to draw at (250,250) in a coordinate system. Where the first number is the x-axis and the second number the y-axis. In a computer screen, the top left corner is the origin (0,0). The x-axis number increases as it goes to the right and for the y-axis the number increases as it goes the bottom. Weird.

So (300,0) is a point at the top that is located more to the right side than that of a point at (50,0);
And (0,300) is a point at the left that is at a lower position than a point at (0,100);

No matter reading these instructions, try it! Change the first two numbers and see the position of the circle change.

`ellipse(300,0,50,50);`

`ellipse(50,0,50,50);`

`ellipse(0,300,50,50);`

`ellipse(0,100,50,50);`

Now what if I told you, we can make a drawing app just by changing two numbers in the two other words!? Write this :

`ellipse(mouseX,mouseY,50,50);`

Notice the CAPS for 'X' and 'Y'. You have to write it exactly as it is. Here's a link to a codepen.io example just incase you weren't able to manage it! Look at the difference of code, not much right?

- [Example of Minimal Basic Drawing app using p5](https://codepen.io/byunk/pen/oWdWNq)

This actually concludes the class. This is it! You have your own drawing app. It's missing a few details, but it is a functional application. Amazing right? Coding isn't difficult, people make it to be, but it's easy as 123. Now try to use other shapes like : `rect(mouseX,mouseY,100,10)` and `triangle(0,0,mouseX,mouseY,500,0)`. Or add more than one shape like so:

```javascript
function draw(){
  rect(mouseX, mouseY,100,10);
  ellipse(mouseX,mouseY,20,50);
}
```

Below is an example of what you can do. I cheated a bit with the colors, but the basic principle is true. 

- [Example of Painting App with a Custom Brushstroke](https://codepen.io/byunk/pen/KmRpdV)

Hope you remember the other material I spoke in class. You can change the color of the shapes, the strokes, its weight, you can add transparencies, and also remember that the background can change colors and size! These are notes from the class itself so any other questions come to class and ask away!

## Class 02 - We can digitally paint, now what? Let's be Media Artists!
Digital tools are awesome because... well we create awesomeness with minimalism. It's like magic. Computer magic. What shamanism is this!? I expect our class to be media artists by the end of class :)

## Class 03 - Humans drawing is old news, let's make the computer do our work.
Have you ever wondered why we made computers? Sometimes, I think we made them just to slack off. So let's be media artists that make the computer do the work! Now we are creative technology artists, we sure are growing fast.

## Class 04 - Now a bit of seriousness. Finally, we get to use our thinking!
Seldom I like to just drift in my thoughts, and that's what we'll do. Think. Anyways, our creative coding class is coming to an end :(, and I will start explaining the connections of computer communcations and web designing. A bit of history and my personal thoughts on why we humans go nuts for making webpages.

## Class 05 - Goodbye Coding and Hello Web Design.
We are going to watch a video from 1968 called the "Mother of All Demos" if you want to go check it out beforehand be my guest! [MOTHER OF ALL DEMOS LINK](https://www.youtube.com/watch?v=yJDv-zdhzMY)

# Resources
A resources section when you get lost and only want the links.

## Code Editors
- [Atom](https://atom.io/)
- [Brackets](http://brackets.io/)
- [Sublime](https://www.sublimetext.com)

## p5.js Web Editor
[p5 Web Editor](https://alpha.editor.p5js.org/)

## Codepen.io p5.js empty example template
Go to this link and you are set. [Link to Empty Example](https://codepen.io/byunk/pen/VbXEEJ)
