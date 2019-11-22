# Week3Day1 is a daily assignment on Servlet.

In this project simple servlet's lifecycle is implemented for Login. Servlet lifecycle consists of init, service (doGet and doPost) and destroy. 

1. dto: dto is a package in this project with Login class which is like a POJO for the application. Constructor, getters and setters are methods in this class.

2. LoginServlet: Login Servlet is a class in this project which defined the entire process of a servlet lifecycle from initialization till destruction. It has pre defined ist of users and just verifies if the inpout matches with the elememts in the list using forEach. If it matches then Sucess message is printed.
