title: "3B1B Vectors, Linear combinations, span, and basis vectors?"	
date: 2020-09-06 10:05:10	
categories: 3B1B LinearAlgebra
---	

<h1>basis vectors</h1>
<ul>
 <li>i-hat: the unit vector(length 1) in the x direction</li>
 <li>j-hat: the unit vector(length 1) in the y direction</li>
</ul>


<h1>linear combination </h1>

[3,-2]

Think each coordinate, such as 3, -2, as a scalar
In this sense, the vectors that these coordinates describe is the sum of 2 scaled vectors. 

(3)i + (-2)j 


<h2>What if we chose different basis vectors?</h2>

describe vectors numerically 
; an implicit choice of what basis vectors we’re using. 

different basis vectors, => a completely reasonable, new coordinate system. 
alter the choices of scalar => reach every possible 2-dimensional vector 


av + bw


<h2>Where does this word ‘linear’ come from? </h2>

One way to think 
<ol>
 <li>Fix one of those scalars</li>
 <li>Let the other one change its value freely</li>
 <li>The tip of the resulting vector draws a straight line. </li>
</ol>

<h2>If both scalars range freely</h2>
<ul>
<li> Most pairs of vectors that are not lined up or not are zero <li>
 the tip of the resulting vector will be able to reach every possible point in the plane ; every 2 dimensional vector is within your grasp. 
 <li>2 original vectors happen to line up </li>
 => this single line passing through the origin
 <li>both your vectors could be zero </li>
 => be stuck at the origin. 
</ul>


<h1>span :</h1>

The set of all possible vectors that you can reach with a linear combination of a given pair of vectors

The span of 2 vectors is basically a way of asking “What are all the possible vectors you can reach using only these 2 fundamental operations, vector addition and scalar multiplication?”



<h1>Vectors vs. Points</h1>

A whole collection of vectors sitting on a line => really crowded
All 2 dimensional vectors all at once, filling up the plane. => still more crowded

<ul>
 <li>To represent each vector with just a point in space. </li>
=> the line itself. 

 <li>All possible 2-dimensional vectors all at once </li>
;conceptualize each one as the point where its tip sits. 
=> the infinite, flat sheet of 2-dimensional space itself
<ul>


individual vectors ;  arrows
sets of vectors ; points

 
<h2>What does the span of two 3d vectors look like?</h2>

The span of  2 vectors in 3d space(pointing different direction)?

the tip of the added vector will trace out => flat sheet, cutting through the origin of the 3-dimensional space
the span of your 2 vectors  : the set of all possible vectors whose tips sit on the flat sheet


<h2>If we add a third vector and consider the span of all 3 of those guys?</h2>

A linear combination of 3 vectors 
<ol>
 <li> Choose the 3 different scalar </li>
 <li> Scale each of those vectors </li>
 <li> Add them all together. </li>
</ol>

And again, the span of these vectors is the set of all possible linear combinations. 

Linear combination of v, w, and u:

av + bw + cu
For span, let constants(a,b,c) vary. 


2 different things can happen here. 
<ul>
 <li>the third vector sits on the span of the first two </li>
=> the span doesn’t change. 
 <li>the third vector does not sit on the span of the first two </li>
=> unlocks access to every possible 3- dimensional vector 
</ul>


<h1>Linearly dependent/Indepednt</h1>

linearly dependent: when at least one of the vectors is redundant - not adding anything to our span

u = av + bw

Linearly independent : if each vector really does add another dimension to the span



<h1>Technical definition of basis : </h1>
The basis of a vector space is a set of linearly independent vectors that span the full space


<h1>link</h1>
https://www.youtube.com/watch?v=k7RM-ot2NWY&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=3&t=111s


