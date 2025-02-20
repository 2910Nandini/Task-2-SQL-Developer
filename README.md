# Task-2-SQL-Developer

# Objective
Analyze relationships between multiple tables and use SQL joins and filtering techniques to extract meaningful insights from the data.

# Project Steps
  Step 1: Database Setup
    Tables to Create
#   1. Students:
      ○ Already created in Task 1.
      ○ Contains student details such as student_id, name, and email.
#   2. Courses:
      ○ Fields:
      ■ course_id: Primary Key.
      ■ course_name: Name of the course.
      ■ course_description: Optional field for details.
#   3. Enrolments:
      ○ Fields:
      ■ enrolment_id: Primary Key.
      ■ student_id: Foreign Key referencing the Students table.
      ■ course_id: Foreign Key referencing the Courses table.
      ■ enrolment_date: Date of enrolment.

  Step 2: Tasks to Perform

#  Task 1: List all students and the courses they are enrolled in.
#  Task 2: Find the number of students enrolled in each course.
#  Task 3: List students who have enrolled in more than one course.
#  Task 4: Find courses with no enrolled students.
