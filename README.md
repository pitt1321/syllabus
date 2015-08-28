## Computational Methods in Physics
## Physics 1321, University of Pittsburgh *(Fall 2015)*
## Syllabus

### Course Information

Meeting Time: Mon, Wed, Fri: 10:00-10:50 AM; Thaw Hall, Room 210

### Instructor Information

* Lecturer: Prof. Michael Wood-Vasey    
* Email: wmwv@pitt.edu
* Office: 308 Allen Hall
* Office Hours: Wednesday 3:30-4:30PM, by appointment, and by GitHub Issue

### Textbook

"Effective Computation in Physics"   by Anthony Scopatz and Kathryn D. Huff 

Available through Pitt subscription to SafariBooks Online.

1. Start and log in at
   * http://www.library.pitt.edu/safari-tech-books-online
2. And then search for “Effective Computation in Physics” or go directly to:
   * http://proquest.safaribooksonline.com/book/physics/9781491901564

This textbook is designed as a useful guide to how to use Python, good software pratice, and tools like ```git``` as for effective scientific research.  However, it **does not** present a treatment of numerical details of integration, curve fitting, etc.  We will be relying on additional resources for such material.

### Course Description 

Introductory physics courses are full of simplifications: projectiles fly without air resistance, pendulums swing only at small angles, no more than two particles move at any time, etc. These kinds of simplifications are necessary and appropriate when you’re first trying to understand the basic laws of nature, but the real world is far more complex, and far more interesting. Fortunately, modern electronic computers make it possible to perform extremely lengthy calculations in a negligible amount of time. In this course we will present several computational techniques and apply them to different problems in physics and astronomy.

### Learning Objectives

After completion of course students will be able to:

1. Find approximate solutions of typical nonlinear equations using various numerical techniques.
2. Evaluate derivatives to an expected accuracy using finite difference methods. 
3. Perform numerical integration using various algorithms.
4. Formulate numerical algorithms for the solution of single and multiple variable ordinary linear and non-linear differential equations in physics, such as simple harmonic motion, large angular motion of a pendulum, Van de Pol oscillator etc.
5. Use modern computer languages, version control, and collaborative tools to solve problems in physics. 
5. Write computer programs to implement the formulated numerical algorithms and output the calculated values of selected physical quantities to suitable data files
7. Propose analytic and computational solutions to a physical problem.
8. Read, assess, and critique a solution to a computational problem.

### Course Structure

Lectures will be interspersed with short exercises and in-class group work.  Students are expected to have read the relevant sections of the textbook (listed in the schedule below and on Courseweb) before class.  Daily short quizzes will test whether you have done the reading before the relevant material is covered in lecture.  There will be weekly homework assignments leading up to a final project as the culmination of your semester's learning.

#### Participation:

In this course you will be responsible for both your own and your colleagues's learning.  Participation will thus be assessed based on your contributions to your colleagues' learning through active participation in classroom discussion, code reviews, and discussion boards.

#### Lecture Quizzes:

There will be quizzes to encourage you to read and confront the material before class.  These quizzes will be generally given at the beginning of class.  The intent is to encourage you to be prepared for class and to wrestle with the material in preparation for further class discussion and learning.

### Assignments

Each week you will complete a homework assignment that uses the material for the current week and builds on previous material.

The assignment for each week will be available before the week’s class meetings. You should clone (download) the assignment and read it before the associated class meetings.  There will be time for you to start the assignment in class. You are encouraged to discuss the assignment with other students, but the work you turn in must be your own and you must understand everything you submit.

#### Final Project:

The final part of this course will be the final projects, which will be presented over the last 4 class days.  The grade will be based on a combination of the written material, including code quality, and the presentation quality.  There will be no final exam.

### Grading
Grades will be weighted as:

Percentage | Component
---------- | ---------
       50% | Assignments
       25% | Final project
       15% | Participation 
       10% | Lecture Quizzes

### GitHub

We will be using GitHub as our collaborative platform for the distribution, discussion, and submission of content in this course.  GitHub is a collaborative platform for developing and sharing code using modern tools and version control.  In particular, it uses the distributed version control system ```git```.  While GitHub will probably look complete different in 10 years, the ideas of sharable knowledge, collaboration, and version control are important ideas that will stay with you throughout your career.  There is an introduction to ```git``` in the course textbook, through http://www.github.com, and many additional online tutorials.

#### Calendar

Week of | Planned material
------- | ----------------
08/31 | Introduction to Python
      | Introduction to Python (basic syntax, math, loops, functions)
09/07 | Introduction to ```numpy``` (types, arrays), plotting
      | random numbers, Monte Carlo simulation, random walk
      |  *No class Sep 7 (Labor Day).*  *Add/drop period ends Sep 11*
09/14 | numerical integration: trapezoidal, Simpson's rule, Monte Carlo
09/21 | finite difference, numerical differentiation (first and second derivatives), solving equations, root finding (bisection, Newton-Raphson)
09/28 | introduction to ```numpy/scipy```, matrix methods, files
10/05 | solving ordinary differential equations (ODEs) (Euler’s rule, Runge-Kutta)
10/12 | solving systems of ODEs, two-dimensional motion (projectiles, orbits)
      | Class will be held Tue, Wed, Fri this week due to Fall Break.
10/19 | Fitting models to data
      | Linear, polyfit, curve fitting
10/26 | discrete and continuous nonlinear problems
11/02 | Fourier transforms
11/09 | thermodynamic simulations, Metropolis algorithm
11/16 | Solving partial differential equations (PDEs) (electrostatics, heat flow)
11/23 | PDEs continued (waves)
      | *No class Nov 25, 27 (Thanksgiving)*
11/30 | Final Project presentations
12/07 | Final Project presentations
12/14 | ---  *No final exam* ---

### Disabilities

If you have a disability that requires special testing accommodations or other classroom modifications, you need to notify both the instructor and the Disability Resources and Services no later than the 2nd week of the term. You may be asked to provide documentation of your disability to determine the appropriateness of accommodations. To notify Disability Resources and Services, call 648-7890 (Voice or TTD) to schedule an appointment. 
The Office is located in 216 William Pitt Union.

###  Academic Integrity

Students in this course will be expected to comply with the University of Pittsburgh’s Policy on Academic Integrity. Any student suspected of violating this obligation for any reason during the semester will be required to participate in the procedural process, initiated at the instructor level, as outlined in the University Guidelines on Academic Integrity. This may include, but is not limited to, the confiscation of the examination of any individual suspected of violating University Policy. Furthermore, no student may bring any unauthorized materials to an exam, including dictionaries and electronic devices.

### Acknowledgments

Attribution and credit is the core currency of respect and recognition in science.  
The structure, lectures, assignments and other material in this course are largely based on material prepared by Prof. Brian D'Urso and Prof. James Mueller.  Additional materials presented in the course are as by attribution; please call me out on non-attributed slides, figures, and plots. 
