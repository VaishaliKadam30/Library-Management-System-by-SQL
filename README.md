# Library-Management-System-by-SQL
Conversion of Manual to Automated Library Management System Using SQL
Mini Project
 – SQL Domain: Library Management System 

The concept behind this project is to create a library management system that is capable of issuing books and let consumers check different books and their titles categorically. It keeps track of all the details about the books in the library, their price, status, and the total number of books available in the Library. The user will find this automated system easy instead of using the manual writing system.

Table that we use in this Project are as follows:

Publisher :             Publisher name [v]{p} ,publisher address [v] ,publisher phone no
Book:                     book id [n]{p}, book title [v], book publisher name [v]{f}
Library Branch:     branch id [n]{p} , branch name [v] ,branch address [v]
Borrower:             Card no [n]{p}, Borrower address [v], Borrower phone no [n]
Loans:                   loans id [n]{p}, book id [n]{f}, branch id [n]{f}, card no [n]{f}, date out [v], due date [v]
Copies:                  copies id [n]{p}, book id [n]{f}, branch id [n] {f}, no of copies [n]
Author:                   author id [n]{p}, book id [n]{f}, author name [v]
