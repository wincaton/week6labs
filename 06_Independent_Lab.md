# Collections

In this assignment you will practice using collections for a student management system. This system will allow you to add students, view GPA metrics, and assign academic violations.

## Grade Entry System

You are a recent hire for an application development organization. They primarily develop learning management systems for higher education. They are currently migrating their system from Java to C#. Your supervisor has tasked you with developing a grade entry program.

The program should have the following abilities:

| Function | Description |
|:---:|:---|
| Menu Navigation | Provide the user the ability to traverse a menu: Student Information Query, Student Information Entry, Query GPA Metrics, Academic Violations, Quit Program |
| Student Information Query | The user can query the system for a list of all the students in the system. Please display the student information in a nicely formatted manner. |
| Student Information Entry | Prompt the user to create a new student record. Prompt the user for the first name, then the last name, then major, and GPA last. |
| Query GPA Metrics | The user can query the data for the following: *max* GPA, *min* GPA, *average* GPA. Display each of these on a separate line. Your program should update *max* GPA, *min* GPA, and *average* GPA each time the `Query GPA Metrics` menu option is selected. |
| Academic Violations | Provide the user a list of current students. After selecting a student, provide them a list of academic violations which they can select (i.e., copying homework, cheating on exam, plagiarism, cheating on quiz, writing paper for another student). A student may only have one academic violation at a time. |

In addition to the requirements above, you have been asked to rely on arrays and lists. I recommend you do not rely on multidimensional lists for this assignment. Specifically, you will need to use lists for the following:

* Storing student information
* Storing academic violations (see in table above)

In all, you should have 6 lists in your program. Your program should start with the following students in the system:

* Carmen Berzatto
* Sydney Adamu
* Neil Fak
* Marcus Brooks

After you get your program running, you will need to add two more students, one of which is you. Thus, you will have six total students stored in your program. When the user adds a new student to the system, they will not be prompted to add an academic violation. An academic violation is only added via the Academic Violation system.

Run your program and save your notebook with the output of your program showing the following:

1.  Update your system with your two new students and use `Student Information Query` to show all students.
1.  Use `Query GPA Metrics` to show GPA information *before* you add the 2 new students and *after* you add them.
1.  Use`Academic Violations` to show you have successfully added violations to 2 students.