Download Link: https://assignmentchef.com/product/solved-cse1321-assignment7-arrays
<br>



Program 1: Design (pseudocode) and implement (source code) a program (name it Occurrences) that counts the occurrences of integers in an array. The program main method defines a single-dimensional array of size 10 elements and prompts the user to enter 10 integers to initialize the array. The main method then calls method Count()to printout the count of each value in the array. Method Count()takes an integer array, counts the occurrences of each value in the array, and prints out the results as shown below. Document your code and properly label the input prompts and the outputs as shown below.

Sample run 1:

Entered integers: 7 7 7 7 7 7 7 7 7 7

7 occurred 10 times

Sample run 2:

Entered integers: 5 2 3 2 1 5 17 22 3 5

5 occurred 3 times2 occurred 2 times3 occurred 2 times1 occurred 1 time17 occurred 1 time22 occurred 1 time

Sample run 3:

Entered integers: 25 35 25 11 35 35 35 45 35 10

25 occurred 2 times35 occurred 5 times11 occurred 1 time45 occurred 1 time10 occurred 1 time

Program 2: Design (pseudocode) and implement (source code) a program (name it IndexOfLargest) to find the index of the first largest value in the array. Note that the largest value may appear more than once in the array. The program main method defines a single-dimensional array of size 10 elements and prompts the user to enter 10 integers to initialize the array. The main method then calls method findIndex() that takes a single-dimensional array of integer values and return the index of the first largest value in the array. Notice that array indexing in Java starts with 0. Document your code and properly label the input prompts and the outputs as shown below.

Sample run 1:

Entered integers: 15 23 -13 12 11 90 25 -17 90 90Index of largest value is 5

Sample run 2:

Entered integers: 5678 123 -113 12 5678 -500 2578 17 51 100Index of largest value is 0

Sample run 3:

Entered integers: 125 -3 -13 -62 -11 541 -125 -117 555 1300Index of largest value is 9

Program 3: Design (pseudocode) and implement (source code) a program (name it DistinctValues) to display only district values in an array. The program main method defines a single-dimensional array of size 10 elements and prompts the user to enter 10 integers to initialize the array. The main method then calls method getValues() that takes an integer array and returns another single-dimensional array containing only distinct values in the original (passed) array. Document your code and properly label the input prompts and the outputs as shown below.

Sample run 1:

Original array: 5 2 1 5 2 3 2 1 5 9Distinct array: 5 2 1 3 9

Sample run 2:

Original array: 45 2 1 45 2 45 2 1 45 2Distinct array: 45 2 1

Sample run 3:

Original array: 0 0 0 0 0 0 0 0 0 0Distinct array: 0

Sample run 4:

Original array: 1 2 3 4 5 6 7 8 9 10Distinct array: 1 2 3 4 5 6 7 8 9 10

Program 4: Design (pseudocode) and implement (source code) a program (name it MinMaxAvg) to determine the highest grade, lowest grade, and the average of all grades in a 4-by-4 two-dimensional arrays of integer grades (representing 4 students’ grades on 4 tests). The program main method populates the array (name it Grades) with random grades between 0 and 100 and then displays the grades as shown below. The main method then calls method minMaxAvg()that takes a two-dimensional array of type integer as a parameter and prints out the class highest grade, the class lowest grade, and class average grade as shown below. Document your code and properly label the outputs as shown below.

Sample run 1:

Array Grades:38 44 22 9181 60 71 8099 49 98 6371 33 93 49

Highest grade: 99Lowest grade: 22Class average: 65.13

Sample run 2:

Array Grades:60 88 98 10087 75 68 9395 86 98 7356 73 88 71

Highest grade: 100Lowest grade: 56Class average: 81.82

Program 5: Design (pseudocode) and implement (source code) a program (name it WeeklyHours) to compute the total weekly hours for 3 employees. The program main method defines a two-dimensional array of size 3×7 to store employers’ daily hours for the week. Each row represents one employee and each column represent one day of the week such that column 0 designates Monday, column 1 designates Tuesday, etc. The program main method populates the array with random numbers between 0 and 10 and then prints out the array in rows and columns as shown below. The main method then calls method addHours() that takes a two-dimensional array as a parameter and displays the total weekly hours for each employee as shown below. Document your code and properly label the outputs as shown below.

Sample run 1:

Employees Data:

Mon Tue Wed Thu Fri Sat SunEmployee1 5 3 2 9 6 5 7Employee2 7 6 8 5 5 4 5Employee3 1 2 2 1 5 8 7

Employee# Weekly Hours—————————-1 372 403 26

Sample run 2:

Employees Data:

Mon Tue Wed Thu Fri Sat SunEmployee1 10 2 7 2 0 3 8Employee2 5 6 1 5 1 4 2Employee3 1 5 2 6 4 8 7

Employee# Weekly Hours—————————-1 322 243 33


