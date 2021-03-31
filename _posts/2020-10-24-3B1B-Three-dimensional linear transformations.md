---
title: "Three-dimensional linear transformations"
date: 2020-10-24 08:11:00	
categories: 3B1B_LinearAlgebra
---	


<h2>linear transformation with 3-dimensional vectors</h2>
<ul>
  <li>every point of space => a proxy for a vector who has its tip at that point</li>
  <li>inputs *moving over* to outputs => described by where the basis vectors go</li>
</ul>
<em>Just as with 2 dimensions.</em>
<br>
<h3>3 standard basis vectors </h3>
<ul>
  <li>x ; i-hat</li>
  <li>y ; j-hat</li>
  <li>z ; k-hat</li>
</ul>
<br>
3B1B thinks it’s easier to follow only those basis vectors
<br>
<br>
<h2>Record 3 vectors a 3*3 matrix</h2>
ex) rotate 90 degrees around the y-axis
<ul>
  <li>i-hat  => [0,0,-1]</li>
  <li>j-hat => [0,1,0] (stays)</li>
  <li>k-hat => [1,0,0]</li>
</ul>
<br>
Those 3 sets become the columns of a matrix 
<br>
<br>
<h2>Reasoning where vector lands</h2>
almost identical to 2 dimensions <br>
each of coordinates => instructions for how to scale each basis vector so that they add together
<br>
Scaling and Adding process works both before and after the transformation. 
<br>
<br>
<h2>Multiplying two 3*3 matrices</h2>
similar with 2*2 
<ol>
  <li>applying the transformation encoded by the right one</li>
  <li>applying the transformation encoded by the left one.</li>
</ol>
<br>
3d matrix multiplication ; important for computer graphics and robotics <br>
break them down as the composition of separate matrix => easier to wrap your mind around
<br>
<br>
<h2>Perform matrix multiplication numerically</h2>
<em>similar to the 2-dimension</em>
<br>
Try to reason through what specifically this matrix multiplication should look like,<br>
thinking closely about how it relates to the idea of applying 2 successive transformations
<br>
<br>
<h2>Link</h2>
<a href="https://www.youtube.com/watch?v=rHLEWRxRGiM">Link<a>


