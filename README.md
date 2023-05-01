Download Link: https://assignmentchef.com/product/solved-bbm-103-quiz-2
<br>



: Introduction to Programming Laboratory I

<h1></h1>

<strong>Subject: </strong>Loops, conditional statements, basic arithmetic operations, and their functions

Accept your <a href="https://classroom.github.com/a/bDwttBlh"><em>2nd Quiz</em></a><a href="https://classroom.github.com/a/bDwttBlh">.</a>

<h1>The Aim of This Quiz</h1>

In this quiz, we expect you all to get practice on basic python commands, and also get experience with the programming environments, the user interface of the Integrated Development Environment (or IDE), python programming console, or terminal.

This quiz consists of two separate parts: Problem1 and Problem2. You should handle each problem in a separate <em>.py </em>file and name it with the problem index; i.e., your solution should be named <em>1.py </em>for the problem1.

<h2>Problem1: Quadratic Equation Solver</h2>

In problem1 you are to solve a quadratic equation in a form of <em>ax</em><sup>2 </sup>+ <em>bx </em>+ <em>c </em>= 0 The roots of a quadratic equation can be calculated using the <strong>Quadratic Formula:</strong>

Before finding the solution to the equation, your program should first output if the equation has a real solution. If a solution exists then you should display how many solutions there are in the equation.

In order to check if a formula has a real solution, you need to calculate the <em>discriminant </em>of that formula using the equation below:

<em>b</em><sup>2</sup>− 4<em>ac</em>

The discriminant can be positive, zero, or negative, and this determines how many solutions there are to the given quadratic equation

<ul>

 <li>A <strong>positive </strong>discriminant indicates that the quadratic has two distinct real number solutions.</li>

 <li>A discriminant of <strong>zero </strong>indicates that the quadratic has a repeated real number solution.</li>

 <li>A <strong>negative </strong>discriminant indicates that neither of the solutions are real numbers.</li>

</ul>

1

Fall 2020

BBM 103: Introduction to Programming Laboratory I

The constant values (<em>a</em>, <em>b</em>, and <em>c</em>) are provided as the command line arguments. The output of this problem (for <em>a </em>= 1<em>,b </em>= 4<em>,c </em>= 3) should match the format provided below including white spaces and punctuations:

There are two solutions

Solution(s): -1.00 -3.00

The order of command-line arguments:

python3 1.py a b c                         =&gt;                   python3 1.py 1 4 3

<h2>Problem2: Even Number Evaluator</h2>

In problem2, you are expected to consider only even numbers (E) within a string (S). The numbers in the string should be; a) greater than zero, b) provided in command line arguments and, c) separated by commas. Once you have obtained the even numbers from the string, you should print the following output considering the output format (for <em>S </em>= ”75<em>,</em>41<em>,</em>14<em>,</em>8<em>,</em>73<em>,</em>45<em>,</em>−16”) :

Even Numbers: “14,8”

Sum of Even Numbers: 22

Even Number Rate: 0.086

While calculating the even number rate, you should divide the sum of even numbers by the sum of all numbers in the string.

Note: Your program should discard the numbers less than zero!

The order of command-line arguments:

python3 2.py S                      =&gt;                        python3 2.py “75,41,14,8,73,45,-16”

<h1>Notes</h1>

<ul>

 <li>Do not miss the submission deadline.</li>

 <li>Save all your work until the quiz is graded.</li>

 <li>You can ask your questions via Piazza and you are supposed to be aware of everything discussed on Piazza.</li>

 <li>You must submit your work with the file hierarchy as stated below:</li>

</ul>

→ <em>&lt;</em>1.py<em>&gt;</em>

→ <em>&lt;</em>2.py<em>&gt;</em>

2