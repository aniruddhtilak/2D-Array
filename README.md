# 2D-Array
This repository contains some basics codes related to 1-D and 2-D Arrays.
1.Element Position
The first program takes 10 inputs from user in form of integer and displays it as well. 
It further asks the user for a number to be searched, if the number is present in the array , it is displayed along withit's position
If number is not found, an error message is displayed.
Algorithm - 
1. Create an integer array 'arr1' of size 10.
2. Create an integer variable 'num' to store the number to be found.
3. Initialize a for loop with 'i' ranging from 0 to 9 to input 10 numbers into 'arr1':
   a. Display "Enter number ".
   b. Read and store the entered number in arr1[i].
   c. Increment 'i' by 1.
5. Display "Array elements are:".
6. Initialize a for loop with 'i' ranging from 0 to 9 to print the elements of 'arr1':
   a. Display arr1[i].
   b. Increment 'i' by 1.
7. Display "Enter number to find".
8. Read and store the number to be found in the 'num' variable.
9. Initialize a for loop with 'i' ranging from 0 to 9 to search for 'num' in 'arr1':
   a. If arr1[i] is equal to 'num', then:
      - Display "Present at position " and the value of i.
   b. If arr1[i] is not equal to 'num', then:
      - Display "Not present".
   c. Increment 'i' by 1.
10. End of the program.


                                                                                                                                                                                                                                                                                                                                    
2.Grading System                                                                                                                                                  
The second program reads marks of 5 subjects as input in an array.                                                                                                
It further compares the average of the inputs with the set conditions and produces output accordingly.                                                            
Algorithm-                                                                                                                                                       
1.Initialize an integer variable 'var' with value as 0,create an integer 'var1' and an inteher array 'marks' with 5 as length.                                    
2.Initialize a for loop with 'i' ranging from 0 to 4 to input 5 numbers into 'marks':                                                                           
   a.Display "Enter marks of subject", value of i+1.                                                                                                              
   b.Read and store the input.                                                                                                                                 
   c.Increment the value of 'var1' by the input.                                                                                                               
   d. Increment 'i' by 1.                                                                                                                                       
3.Calculate 'var' by dividing 'var1' by 5.                                                                                                                        
4.Check for condition-                                                                                                                                           
  a.If 'var' is greater than equal to 90, then:                                                                                                                  
     Display "O".                                                                                                                                                
  b.Else if 'var' is greater than equal to 80, then:                                                                                                            
     Display "A+".                                                                                                                                                
  c.Else if 'var' is greater than equal to 70, then:                                                                                                              
     Display "A".                                                                                                                                                
  d.Else if 'var' is greater than equal to 60, then:                                                                                                              
     Display "B+".                                                                                                                                                
  e.Else if 'var' is greater than equal to 50, then:                                                                                                              
     Display "B".                                                                                                                                                
  f.Else if 'var' is greater than equal to 40, then:                                                                                                              
     Display "C".                                                                                                                                                
  g.Else:                                                                                                                                                         
     Display "Fail".                                                                                                                                              
5.End of the program.                                                                                                                                             
                                                                                                                                                               
                                                                                                                                                                  
                                                                                                                                                                  
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      
3.Matrix Addition                                                                                                                                                 
The Third program reads inputs of 2 matrices(2-D arrays) and if the order of the two matrices matche then it displays their sum.                                  
Algorithm-                                                                                                                                                        
1. Create integer variables 'i', 'j', 'rows_matrix1', 'column_matrix1', 'rows_matrix2', 'column_matrix2'.
2. Display "Enter No. of Rows (Matrix 1) - ".
3. Read and store the number of rows of Matrix 1 in 'rows_matrix1'.
4. Display "Enter No. of Columns (Matrix 1) - ".
5. Read and store the number of columns of Matrix 1 in 'column_matrix1'.
6. Display "Enter No. of Rows (Matrix 2) - ".
7. Read and store the number of rows of Matrix 2 in 'rows_matrix2'.
8. Display "Enter No. of Columns (Matrix 2) - ".
9. Read and store the number of columns of Matrix 2 in 'column_matrix2'.
10. Create integer arrays 'matrix1' and 'matrix2' with sizes [rows_matrix1][column_matrix1] and [rows_matrix2][column_matrix2] respectively.
11. Display "Enter Matrix 1".
12. Initialize a nested loop with 'i' ranging from 0 to 'rows_matrix1' and 'j' ranging from 0 to 'column_matrix1':
    a. Display "Enter element " + i + j + " - ".
    b. Read and store the input value in 'matrix1[i][j]'.
13. Display "Enter Matrix 2".
14. Initialize a nested loop with 'i' ranging from 0 to 'rows_matrix2' and 'j' ranging from 0 to 'column_matrix2':
    a. Display "Enter element " + i + j + " - ".
    b. Read and store the input value in 'matrix2[i][j]'.
15. If 'rows_matrix1' is equal to 'rows_matrix2' and 'column_matrix1' is equal to 'column_matrix2', then:
    a. Initialize a nested loop with 'i' ranging from 0 to 'rows_matrix2' and 'j' ranging from 0 to 'column_matrix2':
        i. Display matrix1[i][j] + matrix2[i][j] followed by a tab character.
    b. Repeat step 15a for all elements in the matrices.
16. If the dimensions do not match (i.e., 'rows_matrix1' is not equal to 'rows_matrix2' or 'column_matrix1' is not equal to 'column_matrix2'), then:
    a. Display "Invalid Order!! Matrix Can't be multiplied."

17. End of the program.
                                                                                                                                                                  
                                                                                                                                                                  
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      
                                                                                                                                                                  
4.Smallest_Largest number                                                                                                                                         
The fourth program reads 10 integer inputs and displays the largest and the smallest input.
Algorithm-
1. Create an integer array 'arr1' of size 10.
2. Initialize 'largest' and 'smallest' variables to the first element of 'arr1' (i.e., arr1[0]).
3. Use a loop to iterate 10 times:
   a. Display "Enter number " followed by the current iteration index + 1 and "- ".
   b. Read and store the entered number in 'arr1[i]'.
4. Set 'largest' and 'smallest' to 'arr1[0]' initially.
5. Use another loop to iterate over each element of 'arr1':
   a. If 'arr1[i]' is greater than 'largest', update 'largest' with 'arr1[i]'.
   b. If 'arr1[i]' is smaller than 'smallest', update 'smallest' with 'arr1[i]'.
6. After the loop, 'largest' will contain the largest number in 'arr1', and 'smallest' will contain the smallest number.
7. Display "Largest= " followed by the value of 'largest'.
8. Display "Smallest= " followed by the value of 'smallest'.
9. End of the program.




