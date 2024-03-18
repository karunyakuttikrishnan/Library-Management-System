# Library-Management-System
You are going to build a project based on Library Management System. It keeps track of all information about books in the library, their cost, status and total number of books available in the library.<br />
Create a database named library and following TABLES in the database:<br />
1. Branch<br />
2. Employee<br />
3. Books<br />
4. Customer<br />
5. IssueStatus<br />
5. ReturnStatus<br />
Attributes for the tables:<br />
1. Branch <br />
Branch_no - Set as PRIMARY KEY <br />
Manager_Id <br />
Branch_address <br />
Contact_no<br />
2. Employee <br />
Emp_Id – Set as PRIMARY KEY <br />
Emp_name <br />
Position <br />
Salary<br />
Branch_no - Set as FOREIGN KEY and it refer Branch_no in Branch table <br />
3. Books <br />
ISBN - Set as PRIMARY KEY <br />
Book_title <br />
Category <br />
Rental_Price <br />
Status [Give yes if book available and no if book not available] <br />
Author <br />
Publisher<br />
4. Customer <br />
Customer_Id - Set as PRIMARY KEY <br />
Customer_name <br />
Customer_address <br />
Reg_date<br />
5. IssueStatus<br /> 
Issue_Id - Set as PRIMARY KEY <br />
Issued_cust – Set as FOREIGN KEY and it refer customer_id in CUSTOMER table  Issued_book_name<br />
Issue_date<br />
Isbn_book – Set as FOREIGN KEY and it should refer isbn in BOOKS table<br />
6. ReturnStatus <br />
Return_Id - Set as PRIMARY KEY <br />
Return_cust <br />
Return_book_name <br />
Return_date <br />
Isbn_book2 - Set as FOREIGN KEY and it should refer isbn in BOOKS table<br />
Display all the tables and Write the queries for the following :<br />
1. Retrieve the book title, category, and rental price of all available books.<br />
2. List the employee names and their respective salaries in descending order of salary.<br />
3. Retrieve the book titles and the corresponding customers who have issued those books.<br />
4. Display the total count of books in each category.<br />
5. Retrieve the employee names and their positions for the employees whose salaries are above Rs.50,000.<br />
6. List the customer names who registered before 2022-01-01 and have not issued any books yet.<br />
7. Display the branch numbers and the total count of employees in each branch.<br />
8. Display the names of customers who have issued books in the month of June 2023.<br />
9. Retrieve book_title from book table containing history.<br />
10.Retrieve the branch numbers along with the count of employees for branches having more than 5 employees<br />
