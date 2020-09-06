title: "3B1B Vectors, what even are they?"	
date: 2020-08-30 17:17:00	
categories: 3B1B LinearAlgebra
---	


<h1>3 distinctive but related perspectives about vectors</h1>

<ol>
  <li>Physics</li>
  : Arrows pointing in space, defined by 
  <ul>
  <li>length</li>
  <li>direction</li> 	
  </ul>
  As long as those 2 facts are the same, you you can move it all around and it's still the same vector. 	
  Vectors can freely sit anywhere they want in space. 	


  <li>Computer Science </li>
  : Ordered lists of numbers.	
  The order matters here. 	
  If the length of the list is 2, it's two-dimensional.	


  <li>Mathematics </li>
  : Anything where there's a sensible notion of adding 2 vectors, and multiplying a vector by a number	
  Seeks to generalise both of prior views	
</ol>


<h2>The way we will think in this lecture: </h2>
an arrow inside coordinate system(tail sitting at the origin, almost always)  -> list of numbers



<h1>The coordinates of a vector</h1> 
: a pair of numbers that give instructions for how to get from the tail of that vector - at the origin- to its tip. 
[x
y
z]


The convention is to write this pair of numbers vertically with square brackets tTo distinguish vectors from points)
<br>
<br>
Every list of numbers -> ONE AND ONLY ONE vector<br>
Every vector is a- > ONE AND ONLY ONE list of numbers



<h1>Addition</h1>

  Move the 2nd vector's tail to the tip of the 1st one.<br>
  then draw a new vector from the tail of the 1st vetor to the moved tip of the 2nd vector.<br>
  The new vector is their sum.<br>
  This is pretty much the only time in linear algebra when we let vectors detach from the origin. 
  


<h1>Multiplication & Scala</h1>
   <ul>
   <li>multiply 2  </li>
    : stretch out that vector so that it's 2 times of the original length
  
   <li>multiply 1/3 </li>
    : squish it down so that it's 1/3 of the original length. 
  
   <li>multiply -1.8  </li>
    1) flipped around 
    2) stretched out by that factor of 1.8
    </ul>
    
   These processes are called 'scaling', <br>
   and the factors are called 'scalar'. 
   
    

<h1> The usefulness of linear algebra</h1> 
  : ability to translate back and forth between aroows or lists. 
  <ul>
  <li> To data analysts </li>
  -> conceptualise many lists of numbers in a visual way, which can clarify patterns in data, and give a global view of what certain operations do. 	
  <li>To physicists and computer graphics programmers </li>
  -> a language to describe space and the manipulation for space using numbers which a computer can crunch and run through
</ul>

<h1>Link</h1>
<a href="https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=2&t=277s">link</a>
