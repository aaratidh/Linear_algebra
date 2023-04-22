# Linear_algebra Day1 

- [# Vector and spcae] 

According to ....  linear algebra deals with the finding the solution of linear equations which heavely involve vector space, matrix, linear transformation and so on.

#Definations
Vectors: Vectors are simply the tuples with numbers or value inside but it has bilinear property and many more

#For any linear equations problem, there are two types of solution one is particular solution and another is homogenous solution
For any particular solution, the scalar multiple of homogenous solution added to the particular solution gives solution that 
will also satisfy the linear equation itself. Combination of particular solutions and some scalr mutltiple of the homogenous 
solution gives the general solutions. 

#General solution for any vector space 

#Vector space:  The collection of all general solutions that satsify the original equation as particular solution does is vector space 

#Vector subspace: A subset of vector space is a subspace if and only if it is closed under the two operations Ax=0 

#Null space: The set of homogenous solutions of the given linear equation is Null space of given Vector space 

#Span of a vector: Set of vectors that can be generated from the linear combination of vectors a1,a2,...an of a vector space.

If any set of vector {v1,v2} span a subspace if all the vectors in vector space S is expressed as a linear combination of the vectors v1,v2.

#Basis of a vector
Basis of a vector is the collection of independent vectors which spans the space. For two vector {v1 ,v2} can be called as a basis if all the vector in vector space S is expressed as a linear combination of the vectors v1,v2 where v1,v2 are linearly independent.

#Rank:
The rank of an n x m matrix is the dimension of the span of its row vectors in Rn. The span of the rows has dimension equal to the number of pivots column in RRE for of matrix of vectors. 

#Linearly dependent or independent: Two vectors are independent if one can be expressed as non zero linear combination of the others.i.e if there is non trival linear combination of two vector exist then they are linearly dependent 


## Day_2 

- [# Optimization]

* [Continous Optimization:] 

 Stochastic Descent: 
  Suppose loss function = summation of Fi (individual loss of the data points)
  formula of Stocastic gradient descent
 ![image](https://user-images.githubusercontent.com/35992124/233795534-37886ecd-38e1-415d-a5a2-24b80ca11a78.png)

Stocastic gradient Descent with momentum 
![image](https://user-images.githubusercontent.com/35992124/233795654-8fa22efd-1048-4955-a2c7-1a147426c090.png)
 
 theta is paramenter 
 delta theta sub i is change in vector
 gamma is step size 
 theta sub i is a surely a vector 
 
 Stochastic gardaient descent can be help ful to find out the global minimum or maximum from local minimum 
 The saaple we choose to find the loss should always be random
 





















