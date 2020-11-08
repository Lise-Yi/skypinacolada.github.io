title: "3B1B Vectors, what even are they?"	
date: 2020-11-07 12:32:00	
categories: 3B1B LinearAlgebra
---	

<br>
<br>
to measure the factor by which the given region increases or decreases

<h2>This square gives you everything you need. </h2>
The change in the area of that 1 single unit square tells you how any possible region in space changes.<br>
As grid lines remain parallel and evenly spaced.  <br>
Any shape can be approximated by grid squares pretty well, if you use small enough grid squares. <br>
<br>
<br>
<h2>The “determinant” of a transformation</h2>
This very special scaling factor is called the determinant of that transformation. <br>
<br>
if the determinant of a given matrix is 0 => the matrix squishes into a smaller dimension. <br>
<br>
<br>
<h2>How can you scale area by a negative number?</h2>
The determinant allows for negative values. <br>
; flipping space, invert the orientation of space <br>
 If you were thinking of 2-d space as a sheet of paper, that one seems to turn over that sheet onto the other side.<br>
<br>
<br>
<h2>to think about it is in terms of i-hat and j-hat</h2>
If j-hat is on the left of i-hat at the start and ends up being right<br>
<ul>
  <li> the orientation of space => inverted </li>
  <li> the determinant => negative</li>
  <li> the absolute value => the factor by which areas have been scaled</li>
</ul>
<br>
<br>
<h2>Why does negative area relate to orientation flipping?</h2>
<ul>
  <li> i-hat get closer and closer to j-hat =>  all of the areas in space are getting squished more and more <br>
    ;  the determinant approaches 0 </li>
  <li> Once i-hat lines up perfectly with j-hat <br>
    ; the determinant is 0 </li>
  <li> if i-hat continues the way it was going <br>
    ; the determinant to keep decreasing into the negative numbers. </li>
</ul>
<br>
<br>
<h2>What about 3d transformations?</h2>
This time, it tells you how much volumes get scaled. 
<ul>
  <li> 1*1*1 cube (whose edges are resting on i-hat, j-hat, and k-hat)   => “parallelepiped” (slanty cube) </li>
  <li> the determinant => the volume of that parallelepiped</li>
</ul>
<br>
<br>
<h2>Columns must be linearly dependent</h2>
<ul>
  <li> A determinant of 0 =>  all of space is squished onto 0 volume( a flat plane, a line, a single point)</li>
  <li> The columns of the matrix  => linearly dependent. </li>
</ul>
<br>
<br>
<h2>What would det(M) < 0 mean?</h2>
The right hand rule describes orientation in 3d.
<ul>
  <li> forefinger  => i-hat </li>
  <li>middle finger => j-hat</li>
  <li>thumb => k-hat</li>
</ul> 
<h3>after the transformation</h3>
  <h4>Can</h4>
  <ul>
    <li>; orientation => not changed </li>
    <li>; the determinant => positive</li>
  </ul>
  <h4>Can't</h4>
  <ul>
    <li>; orientation => flipped </li>
    <li>;the determinant => negative </li>
  </ul>
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
