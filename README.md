# array
This repository contains some basics codes related to 1-D and 2-D Arrays.
A. Element Position The first program takes 10 inputs from user in form of integer and displays it as well. It further asks the user for a number to be searched, if the number is present in the array , it is displayed along withit's position If number is not found, an error message is displayed. Algorithm -

Create an integer array 'arr1' of size 10.
Create an integer variable 'num' to store the number to be found.
Initialize a for loop with 'i' ranging from 0 to 9 to input 10 numbers into 'arr1': a. Display "Enter number ". b. Read and store the entered number in arr1[i]. c. Increment 'i' by 1.
Display "Array elements are:".
Initialize a for loop with 'i' ranging from 0 to 9 to print the elements of 'arr1': a. Display arr1[i]. b. Increment 'i' by 1.
Display "Enter number to find".
Read and store the number to be found in the 'num' variable.
Initialize a for loop with 'i' ranging from 0 to 9 to search for 'num' in 'arr1': a. If arr1[i] is equal to 'num', then:
Display "Present at position " and the value of i. b. If arr1[i] is not equal to 'num', then:
Display "Not present". c. Increment 'i' by 1.
End of the program.
**B. Grading System **
The second program reads marks of 5 subjects as input in an array.
It further compares the average of the inputs with the set conditions and produces output accordingly.
Algorithm-

Create an integer variable 'var' and initialize it to 0. This variable will store the average marks.
Create an integer array 'marks' of size 5 to store marks in 5 subjects.
Create an integer variable 'var1' and initialize it to 0. This variable will store the sum of marks.
Use a loop to iterate 5 times, once for each subject: a. Display "Enter marks of subject " followed by the current subject index + 1 and "- ". b. Read and store the entered marks in 'marks[i]'. c. Update 'var1' by adding 'marks[i]' to it.
Calculate the average by dividing 'var1' by 5 and store it in 'var'.
Use conditional statements (if-else if) to assign a grade based on the value of 'var': a. If 'var' is greater than or equal to 90, display "O". b. Else if 'var' is greater than 80, display "A+". c. Else if 'var' is greater than or equal to 70, display "A". d. Else if 'var' is greater than or equal to 60, display "B+". e. Else if 'var' is greater than or equal to 50, display "B". f. Else if 'var' is greater than or equal to 40, display "C". g. Else, display "Fail".
End of the program.
C. Matrix Addition
The Third program reads inputs of 2 matrices(2-D arrays) and if the order of the two matrices matche then it displays their sum.
Algorithm-

Create integer variables 'i', 'j', 'rows_matrix1', 'column_matrix1', 'rows_matrix2', 'column_matrix2'.

Display "Enter No. of Rows (Matrix 1) - ".

Read and store the number of rows of Matrix 1 in 'rows_matrix1'.

Display "Enter No. of Columns (Matrix 1) - ".

Read and store the number of columns of Matrix 1 in 'column_matrix1'.

Display "Enter No. of Rows (Matrix 2) - ".

Read and store the number of rows of Matrix 2 in 'rows_matrix2'.

Display "Enter No. of Columns (Matrix 2) - ".

Read and store the number of columns of Matrix 2 in 'column_matrix2'.

Create integer arrays 'matrix1' and 'matrix2' with sizes [rows_matrix1][column_matrix1] and [rows_matrix2][column_matrix2] respectively.

Display "Enter Matrix 1".

Initialize a nested loop with 'i' ranging from 0 to 'rows_matrix1' and 'j' ranging from 0 to 'column_matrix1': a. Display "Enter element " + i + j + " - ". b. Read and store the input value in 'matrix1[i][j]'.

Display "Enter Matrix 2".

Initialize a nested loop with 'i' ranging from 0 to 'rows_matrix2' and 'j' ranging from 0 to 'column_matrix2': a. Display "Enter element " + i + j + " - ". b. Read and store the input value in 'matrix2[i][j]'.

If 'rows_matrix1' is equal to 'rows_matrix2' and 'column_matrix1' is equal to 'column_matrix2', then: a. Initialize a nested loop with 'i' ranging from 0 to 'rows_matrix2' and 'j' ranging from 0 to 'column_matrix2': i. Display matrix1[i][j] + matrix2[i][j] followed by a tab character. b. Repeat step 15a for all elements in the matrices.

If the dimensions do not match (i.e., 'rows_matrix1' is not equal to 'rows_matrix2' or 'column_matrix1' is not equal to 'column_matrix2'), then: a. Display "Invalid Order!! Matrix Can't be multiplied."

End of the program.

D. Smallest_Largest number
The fourth program reads 10 integer inputs and displays the largest and the smallest input. Algorithm-

Create an integer array 'arr1' of size 10.
Initialize 'largest' and 'smallest' variables to the first element of 'arr1' (i.e., arr1[0]).
Use a loop to iterate 10 times: a. Display "Enter number " followed by the current iteration index + 1 and "- ". b. Read and store the entered number in 'arr1[i]'.
Set 'largest' and 'smallest' to 'arr1[0]' initially.
Use another loop to iterate over each element of 'arr1': a. If 'arr1[i]' is greater than 'largest', update 'largest' with 'arr1[i]'. b. If 'arr1[i]' is smaller than 'smallest', update 'smallest' with 'arr1[i]'.
After the loop, 'largest' will contain the largest number in 'arr1', and 'smallest' will contain the smallest number.
Display "Largest= " followed by the value of 'largest'.
Display "Smallest= " followed by the value of 'smallest'.
End of the program.
