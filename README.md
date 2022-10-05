# Database-to-store-students-details-using-mysql

The Database ‘eei_2022_studentdetails’ consists of following tables. 


 subject – subjects that offered by ABS Institute
 student – Students primary data
 student_subject – Students registeredsubjects
 classschedule – class schedule for the subjects
 classattendence – class attendance of students

The Tables has following fields.

 subject (s_code, s_title)
 student (s_reg, s_fname, s_sname, tel_no, address)
 student_subject (s_reg, c_code, year_reg)
 classschedule (c_code, classhall, classdate, day, time)
 classattendence (s_reg, classdate, s_code, classhall, attendence)

Abbreviations used in the tables

o s_code – Subject Code
o s_title – Subject Title
o s_reg – Student Registration number
o s_fname – Student First Name
o s_sname – Student Surname
o tel_no – Student Telephone Number
o address – Student postal address
o year_reg – The year in first time registered for a subject
EEI4366/EEX4366

----------------------------------- QUESTIONS ---------------------------------------------------

Write SQL statements to do the following operations.

Part 01

1. View all subjects in the ABC Institute.
2. View details of 5 students.
3. View all student registration numbers.
4. View student registration number, Student first name, and Student surname of all 
students in ABC Institute.
5. View Student first name, and Student Surname of all students with the column headings 
as First_Name and Surname respectively.
6. View all Student Registration numbers of students who have registered for the course 
EEX4366.
7. View all students‟ first name, surname and Telephone no in the alphabetic order of the 
student first name.
8. View subject code of subjects which have lab classes on weekdays.
9. View subject codes of subjects which have classes on Sundays at 01 hall.
10. View subject codes of subjects which do not have lab classes on 15-06-2022.

Part 02

1. View student Registration number and the length of student first name.
2. View subject codes of subjects that will have classes on coming Monday.
3. Write SQL statement to get answers for the following.
4. How many students have registered for the subject EEX4342?
5. How many students have attended for the class held on 10th of July2010?
6. View Student registration number, Student first name, and Student surname of all 
students who have registered for the subject EEX4346 in the year 2020.
7. View Student registration number, Student first name, and Student surname of all 
students who have not attended for any class. (note: attendance field must be taken into 
consideration as if a student has not attended for any class, that student can be traced 
here.)
8. View Student registration numbers of students registered for more than one subject
