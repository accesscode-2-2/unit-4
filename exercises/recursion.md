# Recursion

*Taken from [CodingBat](http://codingbat.com)*

**Factorial** [source](http://codingbat.com/prob/p154669)   
Given `n` of 1 or more, return the factorial of `n`, which is `n * (n-1) * (n-2) ... 1`. Compute the result recursively (without loops).

**Bunny Ears** [source](http://codingbat.com/prob/p183649)  
We have a number of bunnies and each bunny has two big floppy ears. We want to compute the total number of ears across all the bunnies recursively (without loops or multiplication). 

> *Example:*  
bunnyEars(0) → 0  
bunnyEars(1) → 2  
bunnyEars(2) → 4   

**Bunny Ears 2** [source](http://codingbat.com/prob/p107330)  
We have bunnies standing in a line, numbered 1, 2, ... The odd bunnies (1, 3, ..) have the normal 2 ears. The even bunnies (2, 4, ..) we'll say have 3 ears, because they each have a raised foot. Recursively return the number of "ears" in the bunny line 1, 2, ... n (without loops or multiplication).   

> *Example:*  
bunnyEars2(0) → 0  
bunnyEars2(1) → 2  
bunnyEars2(2) → 5  

**Triangle** [source](http://codingbat.com/prob/p194781)  
We have triangle made of blocks. The topmost row has 1 block, the next row down has 2 blocks, the next row has 3 blocks, and so on. Compute recursively (no loops or multiplication) the total number of blocks in such a triangle with the given number of rows. 

> *Example:*  
triangle(0) → 0  
triangle(1) → 1  
triangle(2) → 3  

**Sum Digits** [source](http://codingbat.com/prob/p163932)   
Given a non-negative int n, return the sum of its digits recursively (no loops). Note that mod (%) by 10 yields the rightmost digit (126 % 10 is 6), while divide (/) by 10 removes the rightmost digit (126 / 10 is 12).    

> *Example:*    
sumDigits(126) → 9  
sumDigits(49) → 13   
sumDigits(12) → 3 

You can click through to the [CodingBat website](http://codingbat.com/java/Recursion-1) for a whole bunch of exercises. These exercises are in Java, but you can do them in any language you want. 
