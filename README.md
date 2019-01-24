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
To compute a double integral 
