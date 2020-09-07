================================
Modelling an Engineering College
================================


Introduction
============

An engineering college can be modelled using 'objects' that we have
learnt so far. For this one needs to look at all the entities in a college.
Some entities will be Physical, others may not be Physical entities, but
Logical entities. Let's take an example

1. Department of a college is a Physical Entitiy (Almost all colleges have
   a separate building/floor/office for a department.)

2. Professors in a college is a Physical Entitiy (Almost all the Prof.s
   in a college are humans (at-least yet)).

3. A Course in a department is a Logical Entity - It is not possible to
   'locate' a course. It only exists logically.


Simple Model
============

1. Department: Think of attributes that will be there for a department

2. Professor: Think of attributes that will be there for a Professor

3. Student: Think of attributes that will be there for a Student

4. Subject: Think of attributes that will be there for a Subject

5. Course: Think of attributes that will be there for a Course.

6. Semester: May be this is an entity as well. What type of entity this will
   be?

Actions etc.
============

1. A department should be able to 'offer' a course. When a course is
   'offered', A Professor is assigned to the course, provided - The professor
   actually teaches that course. Note: A professor cannot teach infinite
   courses.

2. A department will have an HOD, who is also a professor.

3. A professor can teach at the most 2 courses unless they are an HOD in
   which case they can only teach 1 course.

4. There will be Academic and non-Academic departments

5. Students can take up a course only if certain criteria are met -
   a. The course offered in a Semester to which a student can register
   b. Once the capacity of the course is over, the student cannot register
      for a course.

Code
====

Your code should have following modules -

1. ``department.py`` - Everything about a Department object.
2. ``course.py`` - Everything about a Course object.
3. ``professor.py`` - Everything about a Professor object.
4. ``student.py`` - Everything about a Student object.


Questions
=========

Write attributes, methods such that, it's possible to answer following questions -

1. Print a list of roll numbers of all students that are taking the course.

2. Print names of all courses a student is taking.

3. Given a professor name, tell whether the person is an HOD if so of which department.

4. Print all courses in a department.

5. Print all professors in department.

6. Given a department name and a subject, answer if the course is being offered now.
