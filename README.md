# Calculation-of-Student-s-Grades-through-Matrix-Multiplication-Python
 to further improve the quality of the program and to enhance user’s 
convenience when using the program, we added a multiple of enhancements in the 
code. These enhancements are the following:
1. Increased Maximum Data
From the previous 20, the program now has the maximum allowable number 
of students, assessments, and grading system variations of 100. The user can now 
solve for student’s final grades in bulk as long as all of them are under one grading 
system or subject.
2. Grading System Error-Checking
To prevent wrong computations of final grades, the program now has an 
error-checking for grading system wherein if the sum of the inputted grading 
system exceeds 1 or 100%, the program prompts that the user inputted an invalid 
grading system and ends the program. This ensures that the possible final grades 
of students are within the bound of 100.
As an example, say the user inputs the grading system of three (3) 
assessments as 60% (0.6), 30% (0.30), and 20% (0.20). Notice that this grading 
system adds up to 110% and thereby exceeds the maximum 100 grade. The 
grading system error-checking detects this mistake, prompting the user that it is 
an invalid grading system, and ends the program. As long as the grading system 
does not exceed 100% or 1, this checker will not be triggered.
3. Input Data Error-Checking
To ease the user’s operation of the program, this python program now has 
an input data error-checker which is done through “while True” handling 
exceptions in python. Whenever the user mistakenly enters an invalid data
(number of assessments, students, and grading system variations), assessment 
grade, or grading system, the user no longer has to restart the program. The 
program simply prompts the user to reenter a correct input. Until a valid value is 
inputted, the program won’t proceed to the next input but instead continuously ask 
the user for a correct value.
Additionally, note that the input data error-checker for grading system is 
different from the previously stated grading system error-checker. The input data 
error-checker for grading system checks if the entered value is between 0 and 1 
such as 0.1 (10%), 0.5 (50%), or 0.6 (60%). On the other hand, the grading system 
error-checker ensures that the summation of 1 grading system does not exceed
100% or 1.
4. Improved Output Display
The program’s code for output display is also enhanced in this python 
program. The display for student’s assessment grades, grading system per 
assessment, and student’s final grades is now all formatted in a table form with 
labels for rows and columns. This improved output display guides the user to 
determine what each value in the table of data represents making it easier and 
more convenient for the user to read the resulting values.
