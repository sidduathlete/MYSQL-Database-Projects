📁 My 4 MySQL Database Projects
Hello! 👨‍🏫 I’m Siddhartha Buyya, a first-year student at Nxtwave Institute of Advanced Technology (NIAT).
Here are the 4 database projects I designed and implemented during my first year.
These projects showcase my understanding of MySQL, relational databases, and ER schema design.

🔹 Tools Used:
MySQL

🔹 Main Takeaways:
✅ Designing and normalizing databases.
✅ Establishing relationships (One-to-One, One-to-Many, Many-to-Many).
✅ Implementing Primary and Foreign Keys.
✅ Querying and retrieving data with JOINs, GROUP BY, and HAVING.
✅ Updating, inserting, and retrieving data accurately.
✅ Handling special cases like co-authored books, multiple hotel employees, department heads, etc.
✅ Built a strong foundation for designing scalable databases.

🔹 Project 1: Research Project Database
Brief:
Design an ER schema to track research projects, funding agencies, and employees.
Each project is funded by a single funding agency and managed by an employee.
Employees can work on multiple projects.

Key points:

One-to-Many: Funding agency to projects

Many-to-Many: Employees to projects (through junction table)

Primary & Foreign keys: To maintain referential integrity

Manager: An employee is designated as a project manager

<img width="587" alt="project1 er diagram" src="https://github.com/user-attachments/assets/4b9c8af5-379f-4031-a50e-34eb67b5aef5" />

🔹 Project 2: University Examination System
Brief:
Design a database to track departments, professors, students, courses, exams, attendance, and enrollments.

Key points:

One department can have many professors and students.

Courses are taught by professors and taken by students.

Exams and attendance are related to a course and a student.

![project2 er diagram](https://github.com/user-attachments/assets/4637482c-c27f-4826-b9c3-661615660ab1)


🔹 Project 3: Online Book Publishing and Sales Platform
Brief:
Design a schema for authors, books, genres, publishers, customers, orders, payments, and wishlist.

Key points:

One book can have multiple authors and genres.

One customer can have many delivery addresses and a wishlist of books.

Each order comprises multiple books with per-item discounts.

![project3 er diagram](https://github.com/user-attachments/assets/c732166c-83ab-4b37-884d-1128a3c6ce3d)


🔹 Project 4: Multi-City Hotel Chain Management System
Brief:
Design a database to track hotels, rooms, guests, employees, managers, booking, payments, and feedback across multiple hotel locations.

Key points:

One hotel has many rooms and employees.

A guest can book many hotel rooms over time.

Feedback is tied to a booking and can affect loyalty level.

Management: Manager is an employee of the hotel.

![project4 er diagram](https://github.com/user-attachments/assets/d589c581-760c-476c-93fb-ce89b7b835de)


