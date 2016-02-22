## EPI890 (Spring, 2016)

**Instructor**: Gustavo de los Campos ( gustavoc@msu.edu )

**Description**. In this independent study we will reivew basic matrix algebra and computational methods with a focus on biostatistical applications. 

**Textbook:** [Matrix Algebra Useful for Statistics by Shayle R. Searle](http://www.amazon.com/Matrix-Algebra-Useful-Statistics-Shayle/dp/0470009616/ref=sr_1_1?s=books&ie=UTF8&qid=1452525779&sr=1-1&keywords=matrix+algebra+useful+for+statistics).

**Content.** We will cover chapters 1-11, 14 and 15 of the textbook, plus a few additional topics.

**Approach.** Students will read one chapter per week and complete 2-3 problems (mostly from the book). We will meet once a week for half an hour to discuss the chapter assigned to the week. Every week one student will lead the discussion, this will include presenting a summary of the chapter, grading the HW and leading the discussion.

**Requirements:**
  (i) Read the chapter assigned.
  (ii) Complete and turn in the HW assigned (usually 2 problems from the chapter).
  (iii) Lead discussions. 
  
**Day/Time**. We will meet every Monday at 3:00-3:30pm in room 637 (Fee Hall, 909 Fee Road, 6th floor, Room 637).

**Evaluation** will we be based on: (i) attendance, (ii) HW, and (iii) discussions lead.

## Content

--------------------------------------------------------------------------------------------------------------------
**Chapter 1 & Chapter to up to page 32 (02/01/2016)**
   - Probelms: Ch.2 problem 3 (solve the problem using R code); Chapter 2 problem 11; chapter 2, problem 6.
   - For discussion: dot notation and colSums/rowSums operators in R; Comprehensions in Julia.
   
--------------------------------------------------------------------------------------------------------------------------------------
**Chapter 2 (pages 32-53, 02/01/2016)**


--------------------------------------------------------------------------------------------------------------------------------------
**Chapter 3 (Special Matrices, pages 60-83)**

Homework
  - show that (AB)'=B'A' 
  - Express colSums, colMeans, rowSums and rowMeans using matrix algebra
  - Express scale(X,center=T,scale=F) using matrix algebra
  - Show that if x'Ax is positive definite, then x'(A+I)x is also positive definite.



--------------------------------------------------------------------------------------------------------------------
**Chapter 4 (Determinants, 2/17/2016)**
  - Additional read: https://en.wikipedia.org/wiki/Determinant
  - HW: list all the properties that you know about determinants (use both the book and the above link).
  - Examples of properties are: 
      - det(AB)=?  if A is diagonal, '
      - det(A)=?, 
      - if A is lower-triangular, det(A)=? 
      - if A is singlular, det(A)=? 
      - if A'A=I, det(A)=?....

--------------------------------------------------------------------------------------------------------------------
**Chapter  5 (Determinants)**

Topics to be discussed:
  (i) Use of inverses (focus on solving systems of linear equations)
  (ii) Definition of inverse
  (iii) Relationship to determinants
  (iv) Properties (page 130)
  (v) inverses of positive definite matrices using cholesky and eigen decompositions.

--------------------------------------------------------------------------------------------------------------------
**Chapter 6 (Rank, 02/29/2016)**


--------------------------------------------------------------------------------------------------------------------
**Chapter  (Person in charge TBA, 03/07/2016)**


--------------------------------------------------------------------------------------------------------------------
**Chapter  (Person in charge TBA, 03/14/2016)**


--------------------------------------------------------------------------------------------------------------------
**Chapter (Person in charge TBA, 03/21/2016)**


--------------------------------------------------------------------------------------------------------------------
**Chapter  (Person in charge TBA, 03/28/2016)**


--------------------------------------------------------------------------------------------------------------------
**Chapter  (Person in charge TBA, 04/04/2016)**

--------------------------------------------------------------------------------------------------------------------
**Special topics: Krnoecker Products (Person in charge TBA, 04/11/2016)**
  
  [Handout](http://www.siam.org/books/textbooks/OT91sample.pdf)

--------------------------------------------------------------------------------------------------------------------
**Special topics: Multivariate Normal Distribution (Person in charge TBA, 04/18/2016)**


```R
 x=rnorm(100)
 y=x+rnorm(100)
 fm=lm(y~x)

```


