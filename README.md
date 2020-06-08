Q1. check_date.py 

The Python program checks accepts a date from the user and checks if that date is valid or not, without using any in-built functions. Also, the date should not be any future date.

Step 1. START

Step 2. The current year, month and day are initialized with present year, month and day respectively.

Step 3. Day, month and year is read as input.

Step 4. If the date is within limit (not considering future date for loop condition), goto step 4.1 otherwise goto step 5:
	4.1 If year is leap year, month is February and day is betweeen 1 and 29, initialize valid=True and goto step 4.6 otherwise goto step 4.2
	4.2 If year is not leap year, month is February and day is between 1 and 28, initialize valid=True and goto step 4.6 otherwise goto step 4.3
	4.3 If month lies in [1,3,5,7,8,10,12] and day is between 1 and 31, initialize valid=True and goto step 4.6 otherwise goto step 4.4
	4.4 If month lies in [4,6,9,11] and day is between 1 and 30, initialize valid=True and goto step 4.6 otherwise goto step 4.5
	4.5 Initialize valid=False.
	4.6 If valid=True and date is a future date, then valid=False else valid=True. Goto step 6.

Step 5. Initialize valid=False

Step 6. If valid=True, display "Valid Date" else display "Invalid Date"

Step 7. STOP



----------------------------------------------------------------------------------------------------------------------------------------

Q2. 

words_rectangle.py


The file words_rectangle.py accepts a list of words and prints one word a line in the given format

 Eg:  List: [“Hello”,”World”,”in”,”a”,”Frame”]
 
           
            Output:    *********
                       * Hello *
                       * World *
	               * in    *
	               * a     *
	               * frame *
                       *********
                
		
Function used: rect_frame().
Argument of the function: list that is accepted from the user 'element_list'.

Step 1.User is asked to input the number of words 'n'.
Step 2.An empty list is created in the name 'list1'.
Step 3.Inside the for loop that ranges from 1 to n :
                                                   >>>>User is asked to input each word.
                                                   >>>>Each word is appended to the list 'list1'.
                                               
Step 4.The function rect_frame() is called passing the list 'list1'.
Step 5.Working of the function :
                               >>>>Length of the largest word is found out.
                               >>>>Using corresponding print statements, the pattern asked for, is printed.
                       
                       
                       
----------------------------------------------------------------------------------------------------------------------------------------             
Q3.

sum_series.py


The file sum_series.py accepts a number N from the user and prints the following series

Series: 1/1! + 2/2! +3/3! + …. + N/N!

Function used: sum_series().
Argument of the function: the number accepted from the user 'num'.

Step 1.A number 'num' is accepted from the user.
Step 2.The function sum_series() is called.

Step 3.Execution of the function:

                         >>> A variable 'sum' is initialised to 0.
			 >>> Variable 'fact' is initialised to 1.
			 >>> In the for loop that ranges from 1 to num :
			 
			                                                >>> Factorial is calculated.
								        >>> Sum is calculated.
								     
			 >>> Sum is returned to the calling function.
			 
Step 4.Sum of the series is printed..
