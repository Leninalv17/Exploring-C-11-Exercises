# Exploring-C-11-Exercises
<h1>Exercises from handsbook Exploring C++ 11 writing it myself<h1/>

Project 1: Body-Mass Index

It’s project time! Body-mass index (BMI) is a measurement some health-care professionals use to determine whether
a person is overweight, and if so, by how much. To compute BMI, you need a person’s weight in kilograms and height
in meters. The BMI is simply weight/height2
, converted to a unitless value.
Your task is to write a program that reads records, prints the records, and computes some statistics. The program
should start by asking for a threshold BMI. Only records with a BMI greater than or equal to the threshold will be
printed. Each record needs to consist of a person’s name (which may contain spaces), weight in kilograms, height in
centimeters (not meters), and the person’s sex ('M' or 'F'). Let the user enter the sex in uppercase or lowercase.
Ask the user to enter the height in centimeters, so you can compute the BMI using integers. You will have to adjust the
formula to allow for centimeters instead of meters.
Print each person’s BMI immediately after reading his or her record. After collecting information for everyone,
print two tables—one for men, one for women—based on the data. Use an asterisk after the BMI rating to mark
records for which the number meets or exceeds the threshold. After each table, print the mean (average) and median
BMI. (Median is the value at which half the BMI values are less than the median and half are greater than the median.
If the user enters an even number of records, take the mean of the two values in the middle.) Compute individual BMI
values as integers. Compute the mean and median BMI values as floating-point numbers, and print the mean with
one place after the decimal point
