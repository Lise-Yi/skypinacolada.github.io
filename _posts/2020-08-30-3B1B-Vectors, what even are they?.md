title: "3B1B Vectors, what even are they?"	
date: 2020-08-30 17:17:00	
categories: 3B1B LinearAlgebra
---	


<h1>3 distinctive but related perspectives about vectors</h1>

<h2>1. Physics </h2>
  : Arrows pointing in space, defined by 	
    1) length	
    2) direction 	
  As long as those 2 facts are the same, you you can move it all around and it's still the same vector. 	
  Vectors can freely sit anywhere they want in space. 	


<h2>2. Computer Science	</h2>
  : Ordered lists of numbers.	
  The order matters here. 	
  If the length of the list is 2, it's two-dimensional.	


<h2>3. Mathematics	</h2>
  : Anything where there's a sensible notion of adding 2 vectors, and multiplying a vector by a number	
  Seeks to generalise both of prior views	


<h2>The way we will think in this lecture: </h2>
an arrow inside coordinate system(tail sitting at the origin, almost always)  -> list of numbers



<h1>The coordinates of a vector</h1> 
: a pair of numbers that give instructions for how to get from the tail of that vector - at the origin- to its tip. 
[x
y
z]


The convention is to write this pair of numbers vertically with square brackets tTo distinguish vectors from points)

Every list of numbers -> ONE AND ONLY ONE vector
Every vector is a- > ONE AND ONLY ONE list of numbers



<h1>Addition</h1>

  Move the 2nd vector's tail to the tip of the 1st one.
  then draw a new vector from the tail of the 1st vetor to the moved tip of the 2nd vector.
  The new vector is their sum.
  This is pretty much the only time in linear algebra when we let vectors detach from the origin. 
  


<h1>Multiplication & Scala</h1>
   
   <h2>1. multiply 2  </h2>
    : stretch out that vector so that it's 2 times of the original length
  
  
   <h2>2. multiply 1/3 </h2>
    : squish it down so that it's 1/3 of the original length. 
  
  
   <h2>3. multiply -1.8  </h2>
    1) flipped around 
    2) stretched out by that factor of 1.8
    
    
   These processes are called 'scaling', 
   and the factors are called 'scalar'. 
   
    

<h1> The usefulness of linear algebra</h1> 
  : ability to translate back and forth between aroows or lists.  	
<h2> To data analysts </h2>
  -> conceptualise many lists of numbers in a visual way, which can clarify patterns in data, and give a global view of what certain operations do. 	
<h2>To physicists and computer graphics programmers </h2>
  -> a language to describe space and the manipulation for space using numbers which a computer can crunch and run through



https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=2&t=277s	
