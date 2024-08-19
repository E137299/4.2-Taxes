# 4.2 Taxes

## Java Documentation
[Classes and Objects](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)

## Java Tutorials
[Classes and Objects](https://runestone.academy/ns/books/published/apcsareview/JavaBasics/toctree.html)

## Background:

There are many absolutes in life, one of which is taxes. In this lesson we study the tax deductions required to print a payroll check. The first tier of the federal income tax rate is 15% (as of 1996) and FICA is an abbreviation for Social Security Tax. The latest calculations show that the average American worker toils for the government for about 5 out of the 12 months of the year.

## Assignment:

1. Write a program that calculates, stores, and prints tax info about one person. The constructor will take the hours worked and the hourly rate paid. You are not required to line up the decimal points in your output. Note: “Gross Pay” means income before tax is deducted, and “Net Pay” means income after tax is deducted. Here is an example output:
    ```java
    Hours worked: 30.0
    Hourly rate: 12.35

    Gross pay: 370.5

    Federal Tax (15.4%): 57.057
    FICA Tax (7.75%): 28.71375
    State Tax (4.0%): 14.82

    Net pay: 269.90925

    Your program may give a slightly different net pay answer due to rounding off issues. Do not worry about this difference.
    ```

2. Use final values to store the tax rates in your program.