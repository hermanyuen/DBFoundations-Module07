# DBFoundations-Module07

Name: Herman Yuen <br>
Date: 5/31/2023 <br>
Course: IT FDN 130 <br>

# Assignment 07 – Functions
## Introduction
This week I learned about functions and how to apply them. Certain key common functions (e.g. sum, count, cast, convert) are available to use and provides useful purposes in SQL. Custom functions can also be created using a user defined function (UDF) where SQL commands can be tailored within a function to provide re-usable code. The following topics will cover UDF and the differences between Scalar, Inline, and multi-statement functions.

## User Defined Function (UDF)
A user defined function takes one or more arguments into its parameter and uses these arguments to provide return values. What goes into the function is the input and what comes out of the function is the output. This makes usability of functions very common in cases where inputs and outputs allow other users to capitalize on re-using code. A user-defined function can be scalar which provides a single return value or tabled value functions which returns a table just like select would (https://medium.com/@smitagudale712/scalar-valued-and-table-valued-functions-in-sql-server-a0ae6e7f4fe9, 2019).

## Scalar, Inline, and Multi-Statement Function
The differences between scalar, inline, and multi-statement function is the degree of complexity in the function’s logic and the return that the function outputs. A scalar returns a single value where-as inline table-valued functions return a table using select. The multi-statement table valued function similarly returns a table but are constructed within the function. This function essentially creates a virtual table and outputs it to the user. (https://www.sqlteam.com/articles/intro-to-user-defined-functions-updated, 2001)

The similarities include having arguments just like any function would and logic that would lead to a function’s return output. 

## Summary
Overall I learned about how SQL applies functions in queries and the usefulness of re-using code. I also learned about the different types of common functions offered by SQL compilers and how they can be used in different situations. 

