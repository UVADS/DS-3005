# DS 3005: Mathematics for Data Science

Your Mathematics for Data Science Tour Guides:

    * Professor Jon Kropko and Gianluca 
    * Emails: 
    * TA: 
    * Peer Mentors: Brendan Puglisi btp6ht@virginia.edu and Francis Driscoll fpd4fv@virginia.edu
    * Class Location: 

Professor Office Hours:

TA Office Hours 

Course Materials: Mathematics for Data Science Repo

Subject Area and Catalog Number: Data Science, DS 3005

Year, Term and Time: 

Class Title: Mathematics for Data Science

Level: Undergraduate

Credit Type: Grade (A-F) 

<br>

## A Little Bit About the Course
 
Math for Data Science

Course objectives
Broad objectives: To prepare students to become data scientists who actively engage with the math that underlies important methods,
By knowing the mathematical notation, operations, and techniques that are used to construct these methods (INSTRUCT),
By learning how to write code to implement these methods from mathematical first principles without relying on any pre-packaged functions (IMPLEMENT),
Any by making deliberate changes to the underlying mathematics to change these methods in specific ways (INNOVATE).

**Specific objectives**: To train students to be expert in the terminology and use of key concepts in machine learning and mathematics:

* Machine learning:

	* The OLS estimator for simple regression, presented without matrices;

	* The logistic regression log-likelihood function and its maximum likelihood estimator;

	* The matrix formula for multiple linear regression; 

	* Principal components analysis and multiple correspondence analysis;

	* And neural networks 

* Mathematics:

	* Summation notation;
	
	* Single variable derivative calculus and optimization;
	
	* Logarithms;
	
	* Probability functions;
	
	* Integrals and the use of integrals to obtain probabilities;
	
	* Multivariate differentiation and optimization;
	
	* Matrix notation and arithmetic;
	
	* Singularity, eigenmath, and matrix decomposition;
	
	* Infinite power series and Taylor series.

**Module 1: Single variable regression**

* Present scatterplots, line of best fit. Discussion of why this method is so hugely important

* Use a pre-built regression function in python/R to fit against example data

* Introduce the formula for the simple OLS estimator

* Instruct:

	* Summation notation
	
	* Single variable differentiation
	
	* Optimization
	
	* Second derivative test/global vs local discussion
	
	* From this, reconstruct OLS 
	
* Implement:

	* Use R/Python to build their own regression function based on this math. Confirm the results match the pre-built version
	
* Innovate:

	* Think about the formula, change it in some intentional way, describe what the changes are designed to do, and implement the new method

**Module 2: Logistic regression** 

* Use a pre-built logit function in python/R to fit against example data

* Introduce the formula for the maximum likelihood estimator for GLM with logit link and Bernouli family

* Instruct:

	* PDFs/PMFs, parameters
	
	* Joint probability of IID data
	
	* Integration and probability, moments, expected value
	
	* Improper integrals for infinite bounds, limits
	
	* Construction of a GLM
	
	* Logarithms, and why they don’t change the critical point. Logarithmic simplificiation
	
	* Multivariate derivatives: gradient, Hessian
	
	* Multivariate optimization
	
	* Multivariate 2nd derivative test using the Hessian
	
	* Newton’s method and hill climbing, towards gradient descent
	
* Implement:

	* Use R/Python to build their own regression function based on this math. Confirm the results match the pre-built version
	
* Innovate:

	* Think about the formula, change it in some intentional way, describe what the changes are designed to do, and implement the new method

**Module 3: Multiple regression OLS and dimension reduction via PCA and MCA**

* Use a pre-built regress function, PCA, MCA in python/R to fit against example data

* Discussion of what a control variable does in a feature space

* Introduce the matrix formulas for OLS, PCA, and MCA

* Instruct:

	* Definition of a matrix
	
	* Operations: matrix & vector multiplication, transpose, matrix inverse (everything you need for (X’X)^-1X’y
	
	* Singularity and calculating the determinant
	
	* Eigenvectors and eigenvalues
	
	* Eigenvector decomposition of a matrix
	
	* PCA
	
	* Singular value decomposition
	
	* MCA
	
* Implement:

	* Understand basics of numpy
	
	* Use R/Python to build their own regression function based on this math. Confirm the results match the pre-built version
	
* Innovate:

	* Think about the formula, change it in some intentional way, describe what the changes are designed to do, and implement the new method

**Module 4: Neural Networks**

* Introduce: Discuss how this is really just a way to approximate a general, unknown function. Brain talk not allowed

* Implementing simple NN in Python

* Instruct:

	* Infinite series; power series
	
	* Taylor series
	
	* Show how a NN is a multivariate Taylor series of some degree
	
	* Deep dive into the chain rule
	
	* Backpropagation
	
* Implementation:

	* Show how we can use a regression/linear regression to build a NN
	
* Innovate:

	* Try splines instead, kernels and basis functions, activation functions, etc.


## How You’ll Know You Are Learning (Assessments)

## Tech Stack (Course Delivery Tools)

**[Discord Invite Click]()** 

## Materials That Will Aid in Your Learning (Try to use free materials): 

* A. [Weapons of Math Destruction](https://www.amazon.com/Weapons-Math-Destruction-Increases-Inequality/dp/0553418815)
* B. 

## Schedule of Topics 

***NOTE: depending on student interest, the syllabus can be adjusted to accommodate additional topics

| Week 	| Theme 	| Topics 	| Lab 	| Reading/Repo (Prior to Class) 	|
|:---:	|:---:	|:---:	|:---:	|:---:	|
| Week 1 	| 	|  	| 	| 	|
| Week 2 	|  	|   |   | 	|
| Week 3 	|	  | 	|	  |  	|
| Week 4 	|	  |	  |   | 	|
| Week 5  |   |   |   |   | 
| Week 6	| 	|   |   |   |
| Week 7  |   | 	|   |  	|
| Week 8  |   |  	| 	| 	|
| Week 9  |  	|  	|	  | 	|
| Week 10 |  	|  	|	  | 	|
| Week 11 |  	| 	|   |   |
| Week 12 |	  |   |	  | 	|
| Week 13 |   |  	|   |   |
| Week 14 |   |   |   |   |
| Week 15 | 	| 	|   |   |
| Week 16 | 	|  	|  	|  	|

## A few Policies that will Govern the Class

Grading Policies: Courses carrying a Data Science subject area use the following grading system: A, A-; B+, B, B-; C+, C, C-; D+, D, D-; F.  The symbol W is used when a student officially drops a course before its completion or if the student withdraws from an academic program of the University.

Grading Scale: 

 - 93-100 A
 - 90-92 A- 
 - 87-89 B+
 - 83-86 B 
 - 80-82 B- 
 - 77-79 C+ 
 - 73-76 C 
 - 70-72 C- 
 - <70 F

University of Virginia Honor System: All work should be pledged in the spirit of the Honor System at the University of Virginia. The instructor will indicate which assignments and activities are to be done individually and which permit collaboration. The following pledge should be written out at the end of all quizzes, examinations, individual assignments, and papers:  “I pledge that I have neither given nor received help on this examination (quiz, assignment, etc.)”.  The pledge must be signed by the student. For more information, visit www.virginia.edu/honor.


Special Needs:  The University of Virginia accommodates students with disabilities. Any SCPS student with a disability who needs accommodation (e.g., in arrangements for seating, extended time for examinations, or note-taking, etc.), should contact the Student Disability Access Center (SDAC) and provide them with appropriate medical or psychological documentation of his/her condition. Once accommodations are approved, just follow up with me concerning any logistics and implementation of accommodations.  Please try to make accommodations for test-taking at least 14 business days in advance of the date of the test(s). Students with disabilities are encouraged to contact the SDAC: 434-243-5180/Voice, 434-465-6579/Video Phone, 434-243-5188/Fax. Further policies and statements are available at www.virginia.edu/studenthealth/sdac/sdac.html

Technical Support Contacts

    Login/Password: scpshelpdesk@virginia.edu
    UVaCollab: collab-support@virginia.edu
    BbCollaborate Support: http://www.tinyurl.com/uvabbc
