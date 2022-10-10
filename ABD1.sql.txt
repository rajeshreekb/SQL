CREATE DATABASE IF NOT EXISTS TESTSAMPLE2;
use TESTSAMPLE2;
CREATE TABLE IF NOT EXISTS TESTSAMPLE2.students(
       Name varchar(40),
       Regno int,
       email varchar(40),
       phone int
);
CREATE TABLE IF NOT EXISTS TESTSAMPLE2.instructor(
       name varchar(40),
       empid int,
       email varchar(40),
       Designation varchar(40),
       phone int
);
CREATE TABLE IF NOT EXISTS TESTSAMPLE2.course(
       name varchar(40),
       courseid int,
       contacthours int,
       instid int
);
CREATE TABLE IF NOT EXISTS TESTSAMPLE2.take(
       studentid int,
       courseid int,
       grade varchar(40)
);
CREATE TABLE IF NOT EXISTS TESTSAMPLE2.newcourse(
       name varchar(40),
       courseid int,
       contacthours int,
       instid int
);
