
# Course Registration System

The project is mainly built for students in an university for them to select the courses that they wish to enrol for that particular semester.

## Design features about the source code 
the above source code consists of multiple modules.The modules which are present in Course Registration system are :

1)Login module
2)View courses module
3)Choice filling module
4)Seat allotment module


## Modules and supporting files
## Login module
Here the above module has 2 operations .They are:
1) Login
2) forgot password 
Here this module evaluates the student's userID and password and allows them into the course registration process.
The students userid and password data is stored in students.txt file

## View courses module
Here this module reads the contents of two text files,
core_courses.txt and elective_courses.txt and saves it in a structure and displays it upon request from the user.

This module gets semester number and department as inputs and displays all the courses available.

## choice filling module
Here the above module has 3 operations .They are:
1)Checking backlog details
2)Adding courses
3)Dropping courses

This module asks for the student's backlog history and stores it in backlog_courses.bin file

Here in this module the student will be able to select for his desired courses from the list of courses available for him and stores it in the 
core_selected.bin and elective_selected.bin files.

The students will be able to add courses upto 6 and delete courses within 2 weeks if he/she wishes for.

## seat allotment module
Here the above module has 3 operations .They are:
1)Core courses allotment
2)Elective courses allotment
3)Waitlisting students

Here in the module the seats for the students on their choice of the course and faculty will be alloted and details will be stored in 
Allotment.bin file.

The class strength and number of seats left and seats filled is updated and stores in Core_details.bin , Elective_details.bin and course_details.bin  .

If the seats are not available in that particular class, the students will be put in waitinglist and upon cancellation of any other students lets the student in waitlist confirmed .The wailist will be 10% of the class strength.

The waitlisting student details will be written to Waitlist.bin file.
## Compilation method 
Ensure the all the C files,header files and the csv files are in the same location. 

## Steps to run the source code in linux based machines
1)open terminal
2)locate the directory where all the files are saved
3)run the command " gcc C_Project.c -o CourseRegistrationSystem "
4)run the command " ./CourseRegistrationSystem"

## To run the source code in any C IDLE
Create a project file and add all the  source c files and the header files  and build the project and click run to execute the project.
1)Open the IDLE and open C_Project.c file  
2)Compile the project
3)Execute the project 
