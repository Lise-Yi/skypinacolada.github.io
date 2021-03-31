---
title: "Inverse matrices, column space and null space"	
date: 2020-11-22 17:45:00	
categories: 3B1B_LinearAlgebra
---	
<br>
<br>

<h3>Search Keyword for the actual computation</h3>
<br>
Gaussian elimination <br>
Row echelon form
<br>
<br>
<h2>linear system of equations </h2>
<ul>
  <li> the only thing happening to each variable => scaled by some constant </li>
  <li> the only thing happening to each of those scaled variables => added to each other</li> 
</ul>
<br>
ex)<br> 
2x + 5y + 3z = -3 <br>
4x + 0y + 8z = 0 <br>
1x + 3y + 0z = 2 <br>
<br>
<ol>
  <li>throw all the variables on the left (2x + 5y + 3z)</li>
  <li>put any lingering constants on the right (-3). </li>
  <li>vertically line up the common variables (throw in some zero coefficients if needed)</li>
</ol>
<br>
looks a lot like matrix vector multiplication. 
<br>
<br>
<h3> geometric interpretation </h3>
Ax = v : after applying the transformation, a vector x lands on v. 
<br>
<br>
<h2>det(A) != 0</h2>
<ul>
  <li> by far the most likely</li>
  <li> space does not get squished into a zero area region</li>
  <li> there will always be one and only one vector that lands on v, and you can find it playing the transformation in reverse</li>
</ul>
<br>
inverse of A : playing the transformation in reverse <br> 
identity transformation : the transformation that does nothing <br>
<br>
solve your equation by multiplying this inverse matrix by v. <br>
<h3> geometric interpretation </h3>
you’re playing the transformation in reverse, and following v. <br>
A, and some vector v, and you’re looking for the vector x that lands on v.
<br>
<br>
<h2>det(A) = 0</h2>
<ul>
  <li>the transformation associated with this system of equations squishes space into a smaller dimension </li>
  <li>NO inverse (You cannot un-squish a line to turn it into a plane. A function can't do such things) </li>
  <li>The solution can exists even when there is no inverse. You have to be lucky enough that the vector v lives somewhere on that  squishes space </li>
</ul>
<br>
<br>
<h2>Rank</h2>
rank : the number of dimensions in the column space. the number of dimensions in the output of a transformation. <br>
column space : set of all possible outputs for our matrix. the span of the columns of your matrix.  lets us understand when a solution even exists <br>
full rank :  rank is as high as it can be. It equals the number of columns 
<br>
<br>
<h2>Null space / Kernel</h2> 
null space / kernel : set of vectors that lands on the origin (become null). <br>
By Null space, we can understand what the set of all possible solutions can look like<br>
<br>
The zero vector is always included in the column space, since linear transformations must keep the origin fixed in place<br>
<ul>
  <li> Full rank transformation  => the zero vector itself is the only vector that lands at the origin </li>
  <li> Not Full rank => a whole bunch of vectors can land on zero </li>
</ul>
v happens to be the zero vector => the null space gives you all of the possible solutions to the equation <br>
You can use the inverse (if exist) to solve your system
<br>
<br>
<h2>Link</h2>
https://www.youtube.com/watch?v=uQhTuRlWMxw&list=LL&index=13&t=228s
