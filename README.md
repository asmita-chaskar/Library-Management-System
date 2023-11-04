# library-management-system
Library Management System Project in Python

****Requirements and Installation****

Use pip3 instead of pip for Linux and Mac.

Install PyMySQL
☛pip install PyMySQL

Install Tkinter
☛pip install tk



****Install MySQL server****



****Create a Database and Two Tables****
☛Create a table "book_list" under the "library_management" database

create table book_list(
	book_id VARCHAR(10) NOT NULL,
	book_name VARCHAR(50) NOT NULL,
	author VARCHAR(50) NOT NULL,
	edition VARCHAR(10) NOT NULL,
	price Int(6) NOT NULL,
	qty Int(4) NOT NULL,
	PRIMARY KEY ( book_id )
);

☛Create a table "borrow_record" under the same database
create table borrow_record(
	book_id VARCHAR(10) NOT NULL,
	book_name VARCHAR(50) NOT NULL,
	stu_roll VARCHAR(15) NOT NULL,
	stu_name VARCHAR(50) NOT NULL,
	course VARCHAR(10) NOT NULL,
	subject VARCHAR(30) NOT NULL,
	issue_date date NOT NULL,
	return_date date NOT NULL
);


# Application Images
![sample_1](https://github.com/asmita-chaskar/Library-Management-System/assets/117060364/5b21272b-ca31-49e1-a492-a2e0045e25af)
![sample_2](https://github.com/asmita-chaskar/Library-Management-System/assets/117060364/541b014a-8be7-480c-89af-7fcf561708ba)
![sample_3](https://github.com/asmita-chaskar/Library-Management-System/assets/117060364/a2839a01-d8b2-4bdd-87f2-976ad9b58917)


