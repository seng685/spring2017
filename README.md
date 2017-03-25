## Welcome to SENG 685!

## Course Time and Location
- MTWF 1200-1300 Bldg. 640 Rm. 236

## Instructor and Office
- Maj Jason Freels, Bldg. 640, Rm. 205B
- Email: <a href="mailto:jason.freels@afit.edu" target="_top"><b>jason.freels@afit.edu</b></a>
- Email: <a href="mailto:auburngrads@live.com" target="_top"><b>auburngrads@live.com</b></a>
- Phone: (937) 255-3636 ext. 4676
- Cell:  (937) 430-6619

## Office hours
- MTWF 1100-1200 or by appt. (subject to change depending on student schedules).

## Course Objectives
Real-world reliability data are often very complex and analytical solutions using this data rarely exist. Therefore, this course will be both theoretical (learning common theoretical models and concepts) and applied (actually fitting said models to data).  The goals of the course are:

- To introduce the mathematical concepts for analyzing real-world reliability (survivability, time-to-event) data 

- To improve your ability to extract and communicate information from real-world reliability data using software

Three focus areas:

1) Understand concepts for computing statistical estimates from reliability data

2) Apply these concepts to various real-world data structures using the R programming language

3) Communicate analysis techinques and results together using Markdown

## Required Text

- [**William Q. Meeker and Luis A. Escobar**](http://www.public.iastate.edu/~stat533/)<br>Statistical Methods for Reliability Data, Wiley-Interscience, Hoboken, NJ 1998

## Additional Reliability Resources

- [DataCamp](https://www.datacamp.com/) recently decided to provide free access to their content for academic courses (including premium content) Interested students in this class can get 6-month free access

- [**Charles E. Ebeling**](http://www.waveland.com/browse.php?t=392&pgtitle=An+Introduction+to+Reliability+and+Maintainability+Engineering%3A+Second+Edition+by+Charles+E.+Ebeling)<br>An Introduction to Reliability and Maintainability Engineering, 2nd ed., Waveland Press, Long Grove, IL 2010

- [**Marvin. Rausand and Arlnot Hoyland**](http://bcs.wiley.com/he-bcs/Books?action=index&itemId=047147133X&bcsId=9457)<br>System Reliability Theory: Models, Statistical Methods & Applications 2nd ed., Wiley-Interscience, Hoboken, NJ 2004

## Additional Reliability Resources (online)

- [__William Q. Meeker's Homepage__](http://www.public.iastate.edu/~wqmeeker/homepage.html)

- [__Weibull.com - Reliability Engineering Resource Website__](http://www.weibull.com/)

- [__Reliasoft Corporation Homepage__](http://www.reliasoft.com/)

- [__NIST/SEMATECH e-Handbook of Statistical Methods__](http://itl.nist.gov/div898/handbook/)

- [__Defense Systems Information Analysis Center__](http://www.theriac.org/)

- [__Army Material Systems Analysis Activity__](http://web.amsaa.army.mil/home.html/)


## Grading breakdown
- Homework: 35%
- Exams: 35%
- Project: 30% 

## Homework (5 Assignments)

- My homework assignments are intended to assess both your understanding of the course material and your ability to use software to produce and communicate your results.  These assignments will be challenging - therefore each of you will be assigned to a team of two or three to complete them. You're encouraged to work together on the homework assignments, both inter- and intra-team.  Each team must complete and turn in their own work.  You won't learn much from copying someone's homework set, so don't do it.  You may use any other available resource to complete the assignments, however you must cite them.  Homework will be graded on completeness, (i.e. full credit will be given when a "complete" attempt to each problem is made) with one caveat, see __Exams__.  Solutions will be posted after the assignments have been turned in.  Questions to the instructor, both in class and during office hours, are welcomed and encouraged.

- The homework process in this class

    1) I will provide each team a "knitr-shell" of the assignment 

    2) Each team will enter their work into the shell

    3) You ~~may~~ <u>should</u> work together to complete the assignments
    
    4) Every team must turn-in their own work

    5) Completed homework assignments will be emailed to me as a .Rmd file

    6) I will compile the completed assignment on my machine

    7) I will provide the solution after I have received every team's assignment  

## Exams
- I've chosen to modify the standard exam process in a way that I believe is (1) fair to you and (2) easy to grade.  After I receive your completed homework assignments and provide the solutions, I'll choose 3-4 exercises from the homework set to serve as exam questions.  These selected exercises will be evaluated more rigorously than the others and grade will serve as your exam score.  A comprehensive final exam take-home will be given during the final class meeting (due date TBD)

## Final Project

- The final project is intended to develop your skills in applying the reliability concepts learned in this course.  The goal of the project is to perform a reliability analysis using a data set that you create.  Exemptions may be made to allow the use of existing data sets on a case by case basis.

- For this project you will...

    + Form teams of 2-3 and select a problem 

    + Gather data

    + Analyze the data

    + Present your results to the class in a shiny presentation

- The project has three milestones:

    1) Identify the problem and briefly describe what you plan to do<br>__Deliverable:__ 2 paragrahs (informal)<br>&emsp;&nbsp;__Due Date:__ End of Week 3
    
    2) Generate the data and run a preliminary analysis<br>__Deliverable:__ 2 paragrahs (informal)<br>&emsp;&nbsp;__Due Date:__ End of Week 7
    
    3) Present your results to the class<br>__Deliverable:__ A shiny presentation (must have 1+ shiny apps and can have <u>no more</u> than <u>six slides</u>)<br>&emsp;&nbsp;__Due Date:__ During the scheduled Finals time for this class

- Your grade on the project will be based on the quality of your presentation and the quality of your analysis -- taking project difficulty into consideration.  So, don't make the project too hard (duh) or too easy. 

## Software/Computer Programming

- A key component of this course is developing the skills and knowledge to create **reproducible & dynamic** data products to present your research

- In previous offerings of this course, I allowed students to use any software package to complete their assignments.  This became difficult, for the students to complete their work and for me to grade them.  So, I've decided to require you to use the R programming language to complete and submit your assignments.

- Each of these tools will be used ths quarter

    + R Project for Statistical Computing
    
    + RStudio IDE

    + Mathjax

    + Pandoc Markdown

    + HTML~5~, CSS3, and JavaScript (don't need to know these - already built in!)

- I realize that some of you may be new to coding or may have never coded before. Don't worry, you don't need a background in R or \LaTeX to be successful in this course.  Throughout the course I provide LOTS of code that you can copy/paste and modify.  I've also created several demo presentations to get you up to speed. The <a target=' ' href='https://afit.shinyapps.io/R-Installation'>first presentation</a> introduces you to the R/RStudio toolchain and walks you through the process of getting everything installed and ready for the course.

- Finally, the textbook references a well executed package, called SPLIDA, that was originally written by Dr. Meeker in the S-Plus language (SPLIDA stands for S Plus Life Data Anaysis).  The S-Plus language has largely been replaced by R, so Dr. Meeker created an alpha version of the SPLIDA package, modified to run in R, called RSplida.  By Dr. Meeker's own admission, the effort to port SPLIDA to the R language was rushed and incomplete.  Therefore, I've been working with Dr. Meeker to update RSplida to an R package, currently called SMRD.  This package is based on the textbook and will be used throughout the course.

- Throughout the course I'll be providing you with LOTS of code that you can copy/paste and use

## A Few Important Dates
- No Class:   10 October 2016 (Columbus Day), 11 November 2016 (Veteran's Day), 24 November 2016 (Thanksgiving) 

## Final Grades
- (1.00 - 0.93]: A
- (0.93 - 0.90]: A-
- (0.90 - 0.87]: B+
- (0.87 - 0.83]: B
- (0.83 - 0.80]: B-
- (0.80 - 0.77]: C

## Course Outline (Tentative)

- [SENG 585 Review & Software Introduction]() (Week 1)
- [__Chapter  10: Planning Life Tests__](https://afit.shinyapps.io/smrd-chapter-10) (Week 2)
- [__Chapter  12: Prediction of Future Random Quantities__](https://afit.shinyapps.io/smrd-chapter-12) (Week 3)
- [__Chapter  13: Degradation Data, Models and Data Analysis__](https://afit.shinyapps.io/smrd-chapter-13) (Week 4)
- [__Chapter  14: Intro to Bayesian Methods for Reliability__](https://afit.shinyapps.io/smrd-chapter-14) (Week 5)
- [__Chapter  15: System Reliability Concepts and Methods__](https://afit.shinyapps.io/smrd-chapter-15) (Week 6)
- [__Chapter  16: Analysis of Repairable System Data__](https://afit.shinyapps.io/smrd-chapter-16) (Week 7)
- [__Chapter  17: Failure-Time Regression Analysis__](https://afit.shinyapps.io/smrd-chapter-17) (Week 8)
- [__Chapter  18: Accelerated Test Models__](https://afit.shinyapps.io/smrd-chapter-18) (Week 9)
- [__Chapter  19: Accelerated Life Tests__](https://afit.shinyapps.io/smrd-chapter-10) (Week 10)

## My Teaching Philosophy

- As AFIT graduates, you'll be expected to know how to approach and solve real-world problems AND present your results in a meaningful way so that decision makers can make defensible decisions.  

- As AFIT instructors, we do a disservice to our students by not teaching new and improved ways to produce and share your results.  Further, we do a disservice by teaching you to solve problems using tools that you won't have access to after leaving AFIT.  Therefore, I re-built this course using the R/RStudio tool-chain to help you produce better results...faster.

## Challenge your instructor
- If you can't trip me up from time to time, you're not trying.  Discussion leads to a more interesting class, so questions are always good.

## "How not to do Reliability"
- Occasionally, we'll discuss the results of applying poor reliability principles via real world examples.
