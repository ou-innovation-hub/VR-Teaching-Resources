Using calcflow, you can show the relationship between an integral on a 3-D object or a 2-D shape.
For a **3-D object** you can draw it's 2-D form by flattening it out from either the x, y, or z axis. . 
Example. Say we want to find the 2-D representation of a sphere, we flatten it out from top to bottom ( the z-axis), we would get a circle.
No matter what direction we flatten our sphere from we will always end up with a circle. 
For a **2-D object**, you can break it up into individual lines whether they are curved or straight. For example, we break a square into 4 
individual lines connected at the vertices. A circle is just one long, curved line that connects to itself. 

How can we relate this to taking a double integral let alone a triple integral? 

**Easy** But first, let's talk about how a single integral works. I'll save you the trouble of the formal definition and give you a brief
definition which is much easier to understand. An integral takes the area under the curve between one set of points to another. 
Example. Say you want to find the area under the curve from [0, 1] on the x-axis for the function f(x) = 1. Let's break this down into 
different parts namely, a. Visualizing the graph and b. the actual integral itself. 
a. The graph of f(x) = 1 is the a straight line going through the value 1 on the y-axis infinitely (in both directions) on the x-axis. 
So no matter what value for x you plug into the function, you will always end up with the value on the y-axis. Visually, the area under 
function f(x) between [0,1] is the region between [0, 1] on the y-axis or we can simply say this the region under the highest value of y, 1,
to the lowest point 0. Since we going from [0, 1] on the x-axis we are only concerned with region between 0 to 1 on the x-axis or the least 
value on the x-axis, 0, to the greatest vlaue on the x-axis, 1. 
b. To compute the actual integral, you need to have at least 2 semesters of calculus to know how to use the function but even if you don't 
I can tell you how to structure it. 
The fundamentals of the integral is your bounds and which axis you want to integrate. You would set your bounds on the integral symbol 
starting with the lowest bound at the bottom of the integral and the upper bound at the top of the integral. To define which axis you would 
like to integrate with you use the notation d[] and depending on what axis you want to integrate is what goes in the box. So say you want
to integrate along the x-axis, you would use dx and same goes for the y and z axes respectively. Now to actually compute the integral you 
would take the antiderivative of your function and you can find a list of many integrals on google. Once you compute the integral you then 
plug in the values of the upper and lower bounds into the function and subtract them. So for f(x) = 1, the integral is x and since the upper
bound is 1 and the lowest bound is 0, you would plug in 1 into x and subtract from 0 once you plug it into x. Whatever value you come up 
with is the area under the function f(x) = 1. 

So how does this work with a double integral? 

Since we know how to work with a single integral we can use this to our advantage. 
Let me go ahead and make a bold claim and say that a double integral is just doing a integral twice but with 2 sets of bounds. If you do not
believe me, allow me to convince you. Let's take our function f(x) = 1 again for example. We already know how to set up a single integral so
we do not need to worry about making that again. Now, to create a double integral, let's go ahead and slap on another integral in there 
but this integral will have its own bounds and will go along a different axis than the other integral. 
Our first integral will be the same as the integral we created in the single integral example. Now, what do we put as our second integral?
Well lets take a look again at our function on the graph. We already used the x-axis so now lets use the y-axis. We can see on the graph 
that the region between the interval [0,1] lies underneath the curve so we only need to worry about this region. Does it matter the 
order of which you compute the integral? In some instances no but I would recommend avoiding it. Computation for this is a bit tricky 
but it's fairly easy. 
To compute a double integral it works the same as the single integral but with some minor differences. So lets say we want to integrate with respect to y. We integrate any thing with a y the same way as normal but this time, anything that does not have a y you treat as a constant. So say we want to double integrate f(x) = x. To integrate x with respect to y we treat x as a constant and compute it like normal so x integrated with respect to y will be xy. 

Now for the real tricky part. The triple Integral.

The triple integral works like this, since we are working 3 dimensions, we want to conceal our object into a box. Once our object is in the box, we want to define our boundary of the object that is within the space and set the boundary as our bounds for the integrals. Triple Integrals can look intimidating but they are not that bad. 
Once again, let's visualize our object. Side note, my method of explaining how to visualize may confuse you but I will clarify what I mean into seperate paragraphs. This method will help you understand how to look visualize other objects when you are taking an integral. 
So let's take our function f(x) = . What does this look like when it is graphed? Well, when we were using just x-axis, it was a line. When we were using both the x and y axes, it was a square. Can you guess what it will be this time? Yes, it will be a cube. I know what you are probably thinking, yeah it's a cube bit whoop why would I care? It doesn't matter that it is a cube it matters what happens to the cube once you starting integrating it. 
So we know how to compute a double integral and to no one's surprise, it works the exact same way, just with another variable. We have already used x and y so let's go ahead and slap on z in there. Instead of visualizing and computing seperately, let's do them both at the same time. So arrange your triple integral so you integrate z first, then y, then x. Now that you have it setup, let's begin. 
So to visualize what it looks like when we integrate with respect to z first let's look at our cube. We want to focus on the z part of the cube, in other words, the part of the cube that makes it pop out of the graph (the thing that differentiates the cube from a square). This is the region we are finding the area for when we integrate. Once we compute the integral we can completely ignore this region so the remaining region we will need to focus on is just the x and y region which is the square. 


**Different Applications** 

The way we have been doing it above is using functinos that give a simple curve and won't necessarily become a ball, or a sphere. If we want to generate an object such as a regular ball or an abnormal ball, we want to use something called polar coordinates. Polar coordinates are useful for these sorts of situations as well as giving you a big headache, no I'm kidding, they are used as kind of a substition for normal variables. A very common example of using parametric equations is using the equations x = Cos(:theta:) and 
y = sin(:theta:). Where do these come from? These come from the identity of cos^2(theta) + sin^2(theta) = 1. This equation comes from the pythagorean trigonemetric identity that used quite often in trigonometry and calculus. Which makes the correaltino of polar coordinates and calculus and round shapes make a lot of sense! To 
