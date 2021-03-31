---
title: "Dot products and duality"	
date: 2020-12-27 19:25:00	
categories: 3B1B LinearAlgebra
---	
<br>
<br>
<br>
<br>
<h2>Taking the dot product of 2 vectors of the same dimension</h2>
<ol>
<li>pair up all of the coordinates</li>
<li>multiply those pairs together</li>
<li>add the result</li>
</ol>
<br>
ex) the vector [1,2] dotted with [3,4] would be 1*3 + 2*4 <br>
<br>
<br>

<h2>geometric interpretation of the dot product between vector v & w</h2>
<ol>
<li>project w onto the line that passes through the origin and the tip of v </li>
<li>Multiply the length of this projection by the length of v </li>
</ol>
<br>
<ul>
<li>v.w > 0</li>
same direction<br>
<li>v.w = 0</li>
perpendicular<br>
<li>v.w < 0</li>
opposite direction<br>
</ul>
the order doesn’t matter. You could instead project v onto w and get the same result. <br>
<br>
<br>

<h2>why doesn’t an order matter? </h2> 
If v and w have the same length => <b>symmetry</b><br>
projecting w onto v, then multiplying the length of that projection by the length of v & projecting v onto w,  then multiplying the length of that projection by the length of w <br>
=> complete <b>mirror image</b><br>
<br>
<br>

<h3>“scale” one of them by some constant </h3>
ex) 2<br>
the dot product (2v.w) & (v.2w) will be exactly twice the dot product v.w<br>
So the overall effect is still to just double the dot product. <br>
<br>
So even though symmetry is broken, the effect of this “scaling” is the same under both interpretations. <br>
=> Duality<br>
<br>
<br>

<h2>linear transformations from multiple dimensions to 1 dimension</h2>
1 Dimension is just a number line. <br>
This time, each one of those i-hat and j-hat just lands on a number. <br>
=> 1*2 matrix (as we record where those basis vectors land as the columns of a matrix ) <br>
<br>
<br>

<h2>consequence of linearity</h2>
a line of evenly spaced dots will stay evenly spaced after the linear transformation. <br>
ex) <br>
a vector  [4,3] ends up after the linear transformation “ i-hat to 1 & j-hat to 2. “<br>
4*i + 3*j <br>
4*(where i-hat lands(1)) + 3*(where j-hat lands(-2)) = -2<br>
<br>
geometric view: <br>
connection between linear transformations that take vectors to numbers & vectors themselves. <br>
<br>
<br>

<h2>clarify the significance & “happens to also” answer the dot product puzzle</h2>
place the number line diagonally with the number 0 sitting at the origin. <br>
<br>
u-hat : the 2-dimensional unit vector whose tips sit where the number 1 on the diagonal number line<br>
just situated in such a way that overlaps with the embedding of the number line. <br>
<br>
project 2d vectors straight onto this diagonal number line : a linear function that takes 2d vectors to numbers, that takes into coordinates and outputs a single coordinate<br>
=> able to find some kind of 1*2 matrix that describes that transformation. <br>
<br>
<br>

<h3>To find that 1*2 matrix, think about where i-hat and j-hat each land</h3>
projecting i-hat onto the line passing through u-hat & projecting u-hat onto the x-axis  => <b>symmetric</b> <br>
<br>
But projecting u-hat onto the x-axis just means taking the x-coordinate of u-hat. <br>
the number where i-hat lands when it’s projected onto that diagonal number line : x coordinate of u-hat<br>
<br>
The reasoning is almost identical for the j-hat case. 
<br>
the entries of the 1*2 matrix describing the projection transformation = coordinates of u-hat
computing this projection transformation for arbitrary vectors in space, which requires multiplying that matrix by those vectors = taking a dot product with u-hat
<br>
This is why taking the dot product with a unit vector, can be interpreted as projecting a vector onto the span of that unit vector and taking the length. <br>
<br>
<br>

<h3>What about non-unit vectors?</h3>
ex) “scale” u-hat up by a factor of 3<br> 
the new matrix can be interpreted as <br>
<ol>
<li>projecting any vector onto the number line copy </li>
<li>multiplying where it lands by 3</li>
</ol>
This is why the dot product with a non-unit vector can be interpreted as first projecting onto that vector then scaling up the length of that projection by the length of the vector. <br>
<br>
a linear transformation from 2d space to the number line, which was just defined by projecting space onto a diagonal copy of the number line<br>
=> the linear transformation was necessarily described by some 1*2 matrix.<br>
<br>
multiplying a 1*2 matrix by a 2d vector = turning that matrix on its side and taking a dot product<br>
=> this transformation was related to some 2d vector<br>
<br>
Matrix vector product & Dot product. 
<br>
linear transformations whose output space is the number line <br>
=> there’s going to be some unique vector v, corresponding to that transformation<br>
applying the transformation is the same thing as taking a dot product with that vector. <br>
<br>
<br>

<h2>Duality</h2> 
: Natural-but-surprising correspondence. <br>
“Duality” shows up in many different ways and forms throughout math.<br>
<br>
<br>

<h3>duals of linear algebra</h3>
vector : linear transformation that it encodes <br>
linear transformation from space to one dimension :  a certain vector in that space<br>
<br>
Again, numerically, It’s just 2 computations that happen to look similar. <br>
<br>
<br>

<h2>the dot product</h2>
<ul>
<li>understand projections </li>
<li>test whether or not vectors tend to point in the same direction</li>
</ul>
Dotting 2 vectors together is a way to translate one of them into the world of transformations. <br>
<br>
vector ->  the physical embodiment of a linear transformation <br>
It’s as if the vector is really just a conceptual shorthand for certain transformation. <br>
<br>
<br>
<h2>Link</h2>
<a href="https://www.youtube.com/watch?v=LyGKycYT2v0&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=9">link</a>

