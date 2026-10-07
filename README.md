# GRADEBOOK-MANAGEMENT-SYSTEM

**NAME**: AME LETSHELAPHALA
**STUDENT NUMBER**: bida25-118

**INTRODUCTION**
This is a project that is used to grade students across 3 different subjects. Thia project will be done in different sections which will result in one being able to grade students across different varieties.

**SECTION A: INITIAL SETUP-SCALAR OBJECTS AND LOOPS**

**OBJECTIVE**: This includes the student data entry, grade calculation and basic validation.

**DATA STRUCTRES**: This includes of two different lists which are 'names=[]' and 'grades=[]'

**IMPLEMENTATION**
1.Loop (Loop with start, stop and step): The code that represents this is 'for i in range (0, num_students,1)': This means that one starts with zero, stops at Num students and steps 1.
2.Grade Calculation: The code is 'for g in grades: and total= total+g': This will calculate the total of the whole class and the average of the students
3.Basic Validation: 'while True: which is followed by 'if 0<=grade<=100:': This will keep the range between 0 and 100.

**LIMITATIONS**
To search  through the whole list you would need to use a loop.

**SECTION B: EXPANDING WITH LISTS AND TUPLES**

**OBJECTIVE**: To make sure that the grading system is does not crash when a wrong input is inserted.

**IMPLEMENTATION**
-'except ValueError:'code was implemented to notice letters like 'abc'
-A range of 0-100 was added so that numbers that are beyond 100 are rejected.
-A list of tuples were still used.

**SECTION C: INTRODUCTION TO DICTIONARIES**

**OBJECTIVE**: To change from lists to dictionaries for increased effiency

**DATA STRUCTURES**
'students={"Michelle": {"Maths":[80], "Science':[70]}}': This code shows the outer key which is the student name and the inner keys which are the subject and values.

**FEATURES**
1.Add:'add_student()': Adds a students name
2.Update:'update_grades()': Updates students grades
3.Remove: 'remove_student()': Removes a students name
4.View Subject:  'view_subjects_grades()': displays the grades of a particular subject
5.Search:  'search_students()': Looks for details of a particular student
6.Show all:  'for n,d in students.items()': calculates the average mark for a student

**TO RUN THE CODE**  you open pycharm and look for the SECTION C ASSIGNMENT python file and follow the menu which includes of add, update, remove, view subject, search, show all and exist.





