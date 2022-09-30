Create Database Student_Management;
use student_Management;


Create Table Student_Details(
Student_id int not null,
First_name varchar(255) not null,
Last_name varchar(255) not null,
Birth_Date varchar(255) not null,
Address varchar(255) default'Thane',
primary key(Student_id));

insert into Student_Details values(1,'Kabir', 'Singh', '2000-05-02', 'Nahur'),
(2,'Ishan','Kishan', '2001-11-22', 'Dombivali'),
(3,'Acharya', 'Agarwal', '2000-04-01', 'virar'),
(4,'Anand', 'Ahuja', '2000-08-27', 'Kalwa'),
(5,'Devendra', 'Patel', '2001-06-12', 'Vashi'),
(6, 'Kapil', 'Sharma', '2002-07-01', 'Ghatkopar'),
(7, 'Ananya', 'Panday', '2002-01-30', 'Airoli'),
(8, 'Asthon', 'Fernandis', '2001-08-19', 'Chruchgate'),
(9, 'Junaid', 'Khan', '2001-02-26', 'Mumbra'),
(10, 'Yasir', 'Shaikh', '2000-04-20','Mumbra'),
(11, 'Arun', 'Verma', '2001-07-04', 'Thane'),
(12, 'Rakesh', 'Sharma', '2000-10-29', 'Nerul'),
(13, 'Tushar', 'Pawar', '2001-11-25', 'Titwala'),
(14, 'Piyush', 'Chaudary', '2002-12-28', 'Ulhasnagar'),
(15, 'Anika', 'Sharma', '2001-11-15', 'Shahad'),
(16, 'Raza', 'Sayed', '2000-05-16', 'Bhandup'),
(17, 'Sara', 'Khan', '2001-12-31', 'Kalyan'),
(18, 'Salina', 'Burunkar', '2001-09-18','Bhandup'),
(19, 'Ajay', 'Goswami', '2002-10-22', 'Kurla'),
(20, 'Sunil', 'Shetty', '2000-03-11', 'Kalyan'),
(21, 'Aarohi', 'Yadav', '2001-09-17', 'Nerul'),
(22, 'Kyra',  'Sharma', '2002-10-10', 'Airoli'),
(23, 'Riya', 'Verma', '2001-11-30', 'Kurla'),
(24, 'shraddha', 'kapoor', '2002-08-19', 'Nerul'),
(25, 'Abbas',  'Sayed',  '2001-01-31', 'Mumbra'),
(26, 'Arun',  'Sharma',   '2000-02-27', 'Titwala'),
(27,  'Riya', 'Sharma',  '2001-05-31', 'Shahad'),
(28,  'Kabir', 'Agarwal', '2000-12-18', 'Titwala'),
(29, 'Ritu',  'Singh', '2001-09-11', 'Thane'),
(30,  'Sara', 'Shaikh', '2002-10-10', 'Mumbra'),
(31,  'Tushar', 'Verma', '2000-07-21', 'Ulhasnagar'),
(32, 'Sunil', 'Goswami', '2002-11-23', 'Titwala'),
(33, 'Jacquline', 'Fernandis', '2000-01-01', 'Nerul'),
(34, 'Siya', 'Sharma', '2002-08-28', 'Virar'),
(35, 'Rubina', 'Khan', '2001-10-07', 'Thane'),
(36, 'Rekha', 'Verma', '2000-11-22', 'Kalwa'),
(37,  'Sunil', 'Sharma', '2001-12-01', 'Dombivali'),
(38, 'Vishal', 'Sharma', '2002-11-09', 'Ulhasnagar'),
(39, 'Anjali', 'Mehta', '2000-08-15', 'Bhandup'),
(40,  'Ranjit', 'Singh', '2001-04-24', 'Kalyan'),
(41,  'Taha', 'Shaikh', '2002-05-14', 'Nahur'),
(42, 'Priyanka', 'Chopra', '2000-10-11', 'Dombivali'),
(43, 'Sana', 'Khan', '2001-12-28', 'Mumbra'),
(44, 'Anjali', 'Mishra', '2000-07-12', 'Thane'),
(45, 'Mohd', 'Abbas', '2001-05-13', 'Mumbra'),
(46, 'Abhijeet', 'Gupta', '2002-08-21', 'Ulhasnagar'),
(47, 'Varun', 'Mishra', '2000-12-31', 'Dombivali'),
(48, 'Siddhart', 'Sharma', '2002-01-12', 'Virar'),
(49, 'Ritu', 'Kaur', '2001-10-30', 'Kurla'),
(50, 'Abhijeet', 'Singh', '2002-02-29', 'Nerul');


Create table Academics_performance (
Student_id int,
Marathi_score int,
Maths_score int,
English_score int,
Arts_score int,
PE_score int,
primary key(Student_id));

Insert into academics_performance
Values (1,90,80,70,60,50),
(2,85,52,98,56,58),
(3,70,85,99,95,91),
(4,100,86,95,99,94),
(5,68,64,65,65,69),
(6,95,98,98,99,95),
(7,65,69,64,65,65),
(8,81,86,85,85,84),
(9,50,65,68,65,75),
(10,80,95,86,45,75),
(11,90,80,70,60,50),
(12,85,52,98,56,58),
(13,70,85,99,95,91),
(14,100,86,95,99,94),
(15,68,64,65,65,69),
(16,95,98,98,99,95),
(17,65,69,64,65,65),
(18,81,86,85,85,84),
(19,50,65,68,65,75),
(20,80,95,86,45,75),
(21,90,80,70,60,50),
(22,85,52,98,56,58),
(23,70,85,99,95,91),
(24,100,86,95,99,94),
(25,68,64,65,65,69),
(26,95,98,98,99,95),
(27,65,69,64,65,65),
(28,81,86,85,85,84),
(29,50,65,68,65,75),
(30,80,95,86,45,75),
(31,90,80,70,60,50),
(32,85,52,98,56,58),
(33,70,85,99,95,91),
(34,100,86,95,99,94),
(35,68,64,65,65,69),
(36,95,98,98,99,95),
(37,65,69,64,65,65),
(38,81,86,85,85,84),
(39,50,65,68,65,75),
(40,80,95,86,45,75),
(41,90,80,70,60,50),
(42,85,52,98,56,58),
(43,70,85,99,95,91),
(44,100,86,95,99,94),
(45,68,64,65,65,69),
(46,95,98,98,99,95),
(47,65,69,64,65,65),
(48,81,86,85,85,84),
(49,50,65,68,65,75),
(50,80,95,86,45,75);



select * from academics_performance;
Select count(students_id) from academics_performance;
Select max(Maths_score), max(Marathi_score), max(English_score), max(Arts_Score), max(PE_Score)  from academics_performance;
Select min(Maths_score), min(Marathi_score), min(English_score), min(Arts_Score), min(PE_Score)  from academics_performance;
Select avg(Maths_score), avg(Marathi_score), avg(English_score), avg(Arts_Score), avg(PE_Score)  from academics_performance;
Select sum(Maths_score), sum(Marathi_score), sum(English_score), sum(Arts_Score), sum(PE_Score)  from academics_performance;

select Student_id, First_name, Last_name, concat(First_name," _ ", Last_name) as Combination, length(concat(first_name," _ " ,last_name)) as l_name from Student_Details;

Select concat(UPPER(LEFT(first_name, 1)), lower(SUBSTRING(first_name, 2)))
from student_details;

select first_name from student_details where last_name = "verma";

select student_details.first_name, student_details.last_name, academics_performance.marathi_score, academics_performance.maths_score
from academics_performance
inner join student_details
on student_details.student_id = academics_performance.student_id;

select student_details.first_name, student_details.last_name, academics_performance.arts_score, academics_performance.pe_score
from academics_performance
left join student_details
on student_details.student_id = academics_performance.student_id;

create view Abbas as
select maths_score, arts_score, english_score
from academics_performance where student_id=31;

select first_name, last_name from student_details limit 20;

select first_name, last_name from student_details order by last_name;

select first_name, last_name from student_details order by last_name desc;

select first_name, length(first_name), last_name, length(last_name) from student_details;

select first_name, last_name from student_details where first_name like "a%";

select first_name, last_name from student_details where first_name like "%a";

select first_name, student_id from student_details where (select student_id > 20);

select * from student_details where first_name in ('tushar','abbas','kyra');

select distinct address from student_details;

SELECT student_id , maths_score
FROM  academics_performance
GROUP BY maths_score
HAVING maths_score > 20
ORDER BY student_id;

