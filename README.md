# Introduction_To_Optimization

In this project, me and my team members proposed to design a student-friendly course planner that outputs an optimal schedule based on his/her preferences to graduate. The data used in our project is taken from the course list offered by CS department at UW-Madison (https://www.cs.wisc.edu/courses/list). We model the problem as a mixed-integer linear program (MILP). Though the objectives to graduate are different for every person, we assume that every student's objective falls into one of the following categories :

1. Maximize grade point average
2. Graduate by choosing courses of minimum difficulty
3. Graduate by spending minimum tuition fees
4. Graduate with maximum knowledge in his/her's area of interest

The motivation for this problem comes from the scheduling problem studied in class. We propose to provide the optimal schedule based on the student's objective. The general problem setting is as follows:

1. Complete the number of credits needed to graduate.
2. Courses are numbered 200 through 900. Courses numbered 700 through 900 are core credit courses and the rest are non-core credits.
3. Every course is associated with a fixed number of credits. Credits vary from 1 to 6.
4. Courses are offered only in Spring or Fall semester or both. 
5. The university demands that atleast 50 percent of the credits should be core credits.
