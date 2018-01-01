[![licence badge]][licence]
[![stars badge]][stars]
[![forks badge]][forks]
[![issues badge]][issues]

[licence badge]:https://img.shields.io/badge/license-MIT-blue.svg
[stars badge]:https://img.shields.io/github/stars/hey-red/Markdown.svg
[forks badge]:https://img.shields.io/github/forks/hey-red/Markdown.svg
[issues badge]:https://img.shields.io/github/issues/hey-red/Markdown.svg

[licence]:https://github.com/nglthu/Datawarehousing/blob/master/LICENSE
[stars]:https://github.com/nglthu/Datawarehousing/stargazers
[forks]:https://github.com/nglthu/Datawarehousing/network
[issues]:https://github.com/nglthu/Datawarehousing/issues

# Data Warehousing
# Project Overview: 
	
Data Warehousing (DW) Project Building and Analysing a DW for NatureFresh Stores in NZ, built using a high-performance Oracle database 12c, and Index-Nested Loops Join-Oracle.

![alt text](https://github.com/nglthu/Datawarehousing/blob/master/img/dataIntegration.png)



1) First create dimension tables and fact tables using scripts : 
   Step-1_Creating dimension tables and fact table (Star Schema).sql
2) Second step is to execute PL/SQL procedure using it's script : 
   Step-2_PROCESS_INLJ.sql
     The OLAP queries for questions 1 to 5 can be executed using the following scripts :
3)  Question 1 :-  Script for OLAP Question 1 - The top 5 products in Dec 2019
4)  Question 2 :-  Script for OLAP Question 2 - store that produced highest sales in the whole year
5)  Question 3 :-  Script for OLAP Question 3 - top 3 products for December, November and October	
6)  Question 4 :-  Script for OLAP Question 4 - Creation of Materialized view STOREANALYSIS.	
      Question 5 :-  Using ROLLUP and CUBE functions the following scripts can be executed by the top manamgement :
7)   Script for OLAP Question 5 - ROLLUP_1 - STORE AND PRODUCT WISE
8)   Script for OLAP Question 5 - ROLLUP_2 - PRODUCT AND STORE WISE
9)   Script for OLAP Question 5 - CUBE_1 - STORE AND PRODUCT WISE CROSS TABULAR REPORTL
10) Script for OLAP Question 5 - CUBE_2 - PRODUCTAND STORE WISE CROSS TABULAR REPORTL

