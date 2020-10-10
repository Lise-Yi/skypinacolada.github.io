<h1>title: "3B1B Matrix multiplication as composition"</h1>	
date: 2020-10-10 11:47:00	
categories: 3B1B LinearAlgebra
---	

<h2>applying 1 transformation and then another</h2>
  :“composition” of the 2 separate transformations.
 <br>
It can be described with a matrix all of its own, by following i-hat and j-hat. 

<br>
<br>
<h2>One way to think about that new matrix</h2>

<ol>
  <li>multiply it one the left by the rotation matrix</li>
  <li>Take whatever you get and multiply that on the left by the shear matrix.</li>
</ol>

<br>

the “product” of the original 2 matrices has the geometric meaning of applying 1 transformation then another. 

<br>
<br>
<h2>has reading from right to left; </h2>
stems from function notation, since we write functions on the left of variables.
Every time you compose 2 functions, you always have to read it right to left. 

<br>
<br>
<h2>Another example</h2>

<br>
            
M1  = ((1,-2) (1,0))
            
            
<br>
             
M2  = ((0,2) (1,0))
             
             
<br>
M2    M1
The total effect of applying M1 then M2 gives us a new transformation. 

<br>
<br>
<h3>To follow i-hat</h3>

<ol>
  <li>applying M1 => (1,1)</li>
  1st column of M1
  <li>applying M2 => (2,1)</li>
  multiply M2 by (1,1) 
</ol>

<br>
the 1st column of the composition matrix, (2,1)

<br>
<br>
<h3>To follow j-hat</h3>

<br>
<ol>
  <li>applying M1 => (-2,0)</li>
	2nd column of M1
  <li>applying M2 => (0,-2)</li>
	multiply M2 by (-2,0)
</ol>
<br>
the 2nd column of our composition matrix, (0,-2)

<br>
((2,0) (1,-2))


<br>
<br>
<h2>Matrix multiplication represents applying one transformation after another. </h2>
This gives a better conceptual framework that makes the properties of matrix multiplication much easier to understand. 

<br>
((a,c) (b,d)) ((e,g) (f,h))


<br>
<br>
<h3>Where does i go?</h3>
((a,c) (b,d))(e,g) = (ae+bg,ce+dg)


<br>
<br>
<h3>Where does j go?</h3>
((a,c) (b,d))(f,h) = (af+bh, cf+dh)

<br>
<br>
((a,c) (b,d)) ((e,g) (f,h)) = ((ae+bg,ce+dg) (af+bh, cf+dh))


<br>
<br>
<h2>Is M1M2 = M2M1 ?</h2>

<br>
<ul>
  <li> First shear then rotation</li>
<br>
((0,1) (-1,1))

I-hat and j-hat are generally pointing close together. 
  <li>First rotate then do the shear</li>
<br>
((1,1) (-1,0))

I-hat and j-hat are pointing farther apart. 
</ul>

<br>
M1M2 =/= M2M1
Order totally does matter. 

<br>
By visualizing (thinking in terms of transformations), you can do it in your head. 

<br>
<br>
<h2>Associativity: </h2>
Is (AB)C = A(BC) ?
<br>
You’re just applying the same 3 things one after the other all in the same order. 
Good explanation > symbolic proof.

<h2>Link</h2>
<a href="https://www.youtube.com/watch?v=XkY2DOUCWMU&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=4">link</a>
