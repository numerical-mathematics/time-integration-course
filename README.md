# AMCS 390D
### Fall 2017

Time: 1:00-2:30 p.m. every Monday and Thursday (tentative)
Location: Building 9, Room 3135 

Instructor: David Ketcheson  
david.ketcheson@kaust.edu.sa   
Instructor's office: Al-Khawarizmi building, Room 4202  
Office hour: By appointment  

Primary text: Solving Ordinary Differential Equations (2 vols. by Hairer, Norsett, Wanner)
- [Volume 1 (explicit methods)](https://link.springer.com/book/10.1007%2F978-3-540-78862-1)
- [Volume 2 (implicit methods)](https://link.springer.com/book/10.1007%2F978-3-642-05221-7)

Supplementary texts:

- [Numerical methods for ordinary differential equations (Butcher)](http://onlinelibrary.wiley.com/book/10.1002/9781119121534)
- [Numerical solution of time-dependent advection-diffusion-reaction equations (Hundsdorfer & Verwer)](https://link.springer.com/book/10.1007%2F978-3-662-09017-6)

Small portions of a few other texts will be used during the course; these may be distributed as handouts if not available online.


Course homepage: https://github.com/numerical-mathematics/time-integration-course

## Overview and preparation

This course will introduce you to advanced concepts in the theory of numerical solution of differential equations.  It is expected that you have an understanding of numerical methods at the level provided by completing AMCS 252 (i.e., the level of RJ LeVeque’s text on finite differences).  For instance, you should understand the concepts of consistency, stability, and convergence; absolute stability; stiffness; and so forth.  You should also be comfortable programming simple numerical methods, such as finite difference methods for the wave equation or the heat equation.

The numerical solution of ordinary differential equations is a relatively mature field, and excellent packages are available to solve problems that involve no special difficulties (and even for stiff problems).  After a brief review of important concepts, the course will focus first on important topics usually left out of introductory courses, such as error estimation and step size control; order reduction; and some theoretical tools like the logarithmic norm.  The remainder of the course will focus on dealing with the more difficult kinds of problems that may arise in practice.

Many important problems must be solved while respecting qualitative properties of the system, such as energy conservation or energy dissipation.  We will review the developments in these areas from the (very productive) last 40 years.

Another important difficulty is that of multiple concurrent physical processes, which may proceed on widely differing time scales.  A host of techniques have been developed to deal with such problems, and they are one of the most important topics of ongoing research in the field at present.  We will examine the state of the art in this area.

Chief among these difficulties is the sheer size of problems, which nowadays may include billions of unknowns or more.  The dream of efficient parallel-in-time methods has come to the forefront with the rapid increase of supercomputer core counts, as spatial parallelism begins to reach strong-scaling limits.  We will investigate some of the contemporary efforts in this direction.

As you can see, most of the topics in the course are still active areas of research, and there is no single book that covers them all adequately.  Thus the reading for the course will include selections from several books, as well as some research articles.  Furthermore, the scope described above is probably enough for several semesters of study, so we will refine it based on the interests of the participants.

## Evaluation

As this is an advanced topics course, I expect that most students will be enrolled because it is relevant to their research.  Thus evaluation is a secondary concern (the primary one being learning things that are useful to your research!)  However, evaluation is often a useful motivator to make sure you stay engaged with the course at a level that will benefit you.

### Exercises (50%)
A small number of exercises will be assigned regularly, and students will be asked to present solutions in class.  Typically solutions will be presented at the next class meeting or one week after being assigned.  Your grade for this portion depends on both (a) presenting solutions; and (b) actively participating in discussions of other students’ solutions.

Exercises will involve both programming and analysis.

### Course project (50%)
The remainder of your grade for the course will be based on completion of a research project.  This project should involve reading one or more relevant articles or book chapters (beyond the regular reading for the course), and typically will include development of a basic software implementation.  To finalize the project, you have the option of writing a report or giving a presentation to the class.

Important project dates:

- Project proposal due: Sept. 25
- Progress report due: October 23
- Preject presentations/reports due: December 7
 
Your project may be loosely related to your thesis research (but you must follow KAUST’s ethical guidelines on double submission) and you are encouraged to propose your own project topic.  A list of suggested project topics is available [here](https://github.com/numerical-mathematics/time-integration-course/wiki/Potential-course-project-topics-and-resources).
