Download Link: https://assignmentchef.com/product/solved-cs135-project-1
<br>
<u> Formatted input/output</u>




<h1>Project Goals</h1>

The goal of this project is to:

<ol>

 <li>Get students familiar with the printf and scanf functions</li>

</ol>




<strong><u>Important Notes:</u> </strong>

<ol>

 <li><strong>Formatting: </strong>Make sure that you follow the precise recommendations for the output content and formatting: for example, do not change the text in the first problem from “Enter the value of the radius: ” to “Enter the radius: ”. Your assignment will be auto-graded and any changes in formatting will result in a loss in the grade.</li>

 <li><strong>Comments: </strong>Header comments are required on all files and recommended for the rest of the program. Points will be deducted if no header comments are included.</li>

</ol>




<h1>Problem 1</h1>

Write a program that will ask the user for the radius of a circle that has been inscribed in a square. Then your program will calculate and print out: the diameter of the circle, the circumference of the circle, the area of the circle, the perimeter of the square, the area of the square, and the difference between the area of the square and the area of the circle.

The program should function as follows (items underlined are to be entered by the user):

This program computes values related to an inscribed circle.

Enter the value of the radius: 7

The diameter of the circle is: 14

The circumference of the circle is: 43.960

The area of the circle is: 153.860

The perimeter of the square is: 56

The area of the square is: 196

The difference between the area of the square and the circle is: 42.140

<strong>Notes: </strong>

<ul>

 <li>You can assume that the radius will be a positive, whole number</li>

 <li>Please use 14f as your value for pi (This is a good place to use #define)</li>

 <li>The circumference, area of the circle, and difference in areas should output only 3 digits after the decimal place</li>

</ul>




Save your program as circle.c




<h1>Problem 2</h1>

Write a program that takes as input four dates in the format dd/mm/yyyy and prints them out in a tabular format.

The program should function as follows (items underlined are to be entered by the user):




Enter date 1 (dd/mm/yyyy): 05/03/2017

Enter date 2 (dd/mm/yyyy): 21/03/2010

Enter date 3 (dd/mm/yyyy): 07/04/1776

Enter date 4 (dd/mm/yyyy): 11/12/0200




Year Month Day

2017  3     5

2010  3     21 1776  4 7

200 12     11




The year, month and day columns should be separated by tabs (t) (this also refers to the words Year, Month and Day from the header of the table). The year column should occupy 4 spaces and the values should be right justified. The month column should occupy 2 spaces and the values should be right justified. The day column should occupy 2 spaces and the values should be left justified.

<strong>Note: </strong>

<ul>

 <li>You should use t to print a tab instead of hitting the tab button on the keyboard</li>

</ul>




Save your program as date.c




<strong>Challenge for problem 2 </strong>(10 extra credit points):

Modify your previous program so that if the value of the year is less than 4 digits, add a 0 in front of the year to make the year have 4 digits. If the values of the month and day are less than 10 (meaning they have just one digit), the values of month/day will always have two digits displayed.



















The program should function as follows (items underlined are to be entered by the user):

Enter date 1 (dd/mm/yyyy): 05/03/2017

Enter date 2 (dd/mm/yyyy): 21/03/2010

Enter date 3 (dd/mm/yyyy): 07/04/1776

Enter date 4 (dd/mm/yyyy): 11/12/0200




Year Month Day

2017 03     05

2010 03     21

1776 04     07

0200 12     11




Save your challenge separately as date_c.c


