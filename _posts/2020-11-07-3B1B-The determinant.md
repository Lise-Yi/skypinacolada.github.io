title: "3B1B Vectors, what even are they?"	
date: 2020-11-07 12:32:00	
categories: 3B1B LinearAlgebra
---	

<br>
<br>
to measure the factor by which the given region increases or decreases

<h2>This square gives you everything you need. </h2>
If you know how much area of that 1 single unit square changes it can tell you how any possible region in space changes.<br>
As grid lines remain parallel and evenly spaced.<br>
Any shape that is not a grid square can be approximated by grid squares pretty well, if you use small enough grid squares. <br>
<br>
<br>
<h2>The “determinant” of a transformation</h2>
This very special scaling factor is called the determinant of that transformation. <br>
<br>
if the determinant of a given matrix is 0 => the matrix squishes into a smaller dimension. <br>
<br>
<h2>How can you scale area by a negative number?</h2>
The full concept of the determinant allows for negative values. <br>
This has to do with the idea of flipping space. If you were thinking of 2-d space as a sheet of paper, a transformation like that one seems to turn over that sheet onto the other side.<br>
Any transformations that do this are said to “invert the orientation of space. “<br>
<br>
<br>
<h2>to think about it is in terms of i-hat and j-hat</h2>
If j-hat is on the left of i-hat at the start and ends up being right, the orientation of space is inverted. Whenever this happens, the determinant is negative. <br>
The absolute value of the determinant though still tells you the factor by which areas have been scaled. <br>
<br>
<br>
<h2>Why does negative area relate to orientation flipping?</h2>
if we let i-hat get closer and closer to j-hat, all of the areas in space are getting squished more and more meaning the determinant approaches 0. <br>
Once i-hat lines up perfectly with j-hat, the determinant is 0. <br>
Then, if i-hat continues the way it was going, it feels natural for the determinant to keep decreasing into the negative numbers. <br>
<br>
<br>
<h2>What about 3d transformations?</h2>
This time, it tells you how much volumes get scaled. <br>
In 3 dimensions, it helps to focus your attention on the specific 1*1*1 cube whose edges are resting on the basis vectors. i-hat, j-hat, and k-hat.<br> 
<br>
After the transformation, that cube might get warped into some kind of slanty cube, “parallelepiped”.<br>
Since this cube starts out with a volume of 1, You can think of the determinant simply as being the volume of that parallelepiped.<br>
<br>
<br>
<h2>Columns must be linearly dependent</h2>
A determinant of 0 =>  all of space is squished onto something with 0 volume( a flat plane, a line, a single point)<br>
The columns of the matrix are linearly dependent. <br>
<br>
<br>
<h2>What would det(M) < 0 mean?</h2>
The right hand rule describes orientation in 3d<br> 
<ul>
  <li>forefinger  => i-hat</li>
  <li>middle finger => j-hat</li>
  <li>thumb => k-hat</li>
</ul>
<br>
If you can still do that after the transformation;<br>
orientation has not changed<br>
the determinant is positive. <br>
<br>
Otherwise;<br>
orientation has been flipped<br>
the determinant is negative. <br>
<br>
<br>
<h2>How do you compute the determinant?</h2>
For a 2*2 matrix with entries a,b,c,d the formula is (a*d)-(b*c)
det((a,c), (b,d)) = (a+b)(c+d) -ac-db-2bc = ad-bc
<br>
This is all tripply true for 3 dimensional determinants. 
<br>
<br>
<h2>Link</h2>
<a href="https://www.youtube.com/watch?v=Ip3X9LOh2dk&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=6">link</a>
