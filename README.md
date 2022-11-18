# CumulativeProject

This is Cumulative Project Part 1. I am tasked to Create, Read, Update and Delete files from a database. This part creates a Minimum Viable Product (MVP)
from a table using a Web API. 

In this project, I am tasked to create:
  - model class for SchoolDatabase    --> connects to MySQL Database
  - model class for Teacher           --> model that connects information of a teacher (variables)
  - API controller for TeacherData    --> allows access to teacher's information
  - a controller for Teacher          --> link and routes pages from the teacherdatacontroller
  - a view for List                   --> Shows you the list of teachers in separate links
  - and a view for Show               --> once you click a specific teacher, it will route you to their own profile showing all employment information about them
  
With the controllers, models, and views given, once you run the server (via MAMP) and set-up the database, root, etc, you will be able to search and access the
data of teachers including their teacher Id, Employee Number, First and last name, Hire Date, and Salary. You can base this data from the PhpMyAdmin.
