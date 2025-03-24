Use Case: Student Course Registration
Actors:
Student: A university student who wants to register for courses.

Administrator: The university admin responsible for managing student and course data.

System (Student Course Registration System): The platform handling student registration and course management.

Preconditions:
The student must have valid login credentials (Enrollment Number and Password).

The admin must have access credentials to manage student and course data.

The system must have a list of available courses.

Main Flow (Student Course Registration):
Student logs in using their enrollment number and password.

The system verifies the credentials and redirects the student to their dashboard.

The student selects "Register for Courses" from the dashboard.

The system displays the list of available courses.

The student selects courses they want to enroll in and submits the form.

The system performs validation to ensure:

The student meets course prerequisites.

The student has not exceeded the maximum course limit.

The system saves the registered courses in the database and shows a confirmation message.

The student can view registered courses under the "View Submitted Data" section.

Alternative Flows:
Invalid Credentials: If login details are incorrect, the system shows an error message.

Course Full: If a course has reached maximum capacity, the student is notified and must select another course.

Duplicate Registration: If the student tries to register for the same course again, the system prevents duplication.

Admin Actions:
Admin logs in using their credentials.

The system verifies credentials and redirects to the Admin Dashboard.

The admin can perform the following tasks:

Add new students and generate login credentials.

View and edit student details, including course registration.

Add, edit, or delete courses and departments.

View course details and see which students are enrolled.

The system updates the database accordingly.

Postconditions:
Student course registrations are stored securely in the database.

Admin has updated student and course data.

The system maintains data integrity and security by preventing redundant entries and SQL injections.

Future Enhancements:
Improve the UI design for a better user experience.

Implement course filtering to help students find relevant courses.

Add a list of students enrolled in each course for better administration.

Implement stronger security measures to prevent SQL Injection and unauthorized access.


Database Assignment, You can use everything, just don't copy the Names and stuff.

Objective
We are supposed to build a Student Course Registration System for the University. We should be using the lamp stack and php for this purpose. According to our plans , we implemented the following features in the system,

A Student panel :
The Student can log in to the system using the enrollment number and password provided to him by the administration during admission.
He can register for new courses and see the data that he submitted and make proper changes to it if there are any errors. An Admin Panel:
To view the data submitted data provided by the students.
To Make Proper Changes to the student data, edit or delete a student.
To add students
To add a course and department.
Make changes to the current courses (edit or delete them).
Results
We implemented the system using php and wrote commands to query the SQL database.
Student Login:
Here, the student logs in the system using the enrollment number and password provided to him by the university.

Student Dashboard
Here the Student can view the options he has, it is his dashboard. He can :

Register his courses.
View his submitted data.
Logout.
Register
This is where the student register for the course and supplies valid data to the fom. The form does all types of checking to see that the user doesn’t do invalid input on the fields.

View Student Data
Here, the student can view the data he submitted.

The Admin Panel:
This is the panel used by the administrators of the database. They log in using the password given to them.We consider that the admin details has already been included in the database.

Admin Dashboard
This gives a view of the different tasks that can be performed by the administrator such as viewing student data , viewing courses and edit or delete them according to convenience.

Add New Student
Here the administrator can generate a new roll number for a student and a password for him. The student logs in using this data provided to him by the administration.

Add New Course
Here, the admin can add new courses to the system.

Course Details
Here the admin can view the current courses running , delete them if necessary or edit them.

Student Details
Here, the admin can view and edit student details accordingly. He can edit their details in case of error and even delete a student.

What's Next
There are further improvements to be done, such as improving the layout, adding an option to view the list of students opting for a particular course. Also, we have to make sure that there is less redundancy in the data as possible.
We have to add additional security features to avoid SQL Injection and other harmful attacks on the database.
Tools:
Bootstrap: https://getbootstrap.com/ Codepen: https://codepen.io/
