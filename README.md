Printing Parallelogram Star Pattern
In this Python Program, we will be discussing about how to write a program to print Parallelogram Star Pattern. In this pattern, number of rows and numbers of columns are different. Then, User have to enter two value, in which one value will be determine as a number of rows and other value will be considered as columns of the pattern. With the help of “For-Loop” and “Nested For Loop” we will print Parallelogram Star Pattern.

Python Program for Printing Parallelogram Star Pattern
Working:
Step 1. Start

Step 2. Take number of rows input from the user and store it in any variable (‘rows’ in this case).

Step 3. Take number of column input from the user and store it in any variable (‘cols’ in this case).

Step 4. Run a loop ‘i’ number of times to iterate through all the rows which is Starting from i=0 to rows.

Step 5. Run a nested loop inside the main loop for printing spaces which is starting from j=1 to i+1.

Step 6. Run a nested loop inside the main loop for printing stars which is starting from j=0 to cols.

Step 7. Move to the next line by printing a new line using print() function.

Stop 8. Stop

Python Program:
rows = int(input("Enter rows:"))
cols = int(input("Enter Cols:"))

for i in range(0, rows):
    for j in range(1, i+1):
        print(" ", end="")
    for j in range(0, cols):
        print("*", end="")
    print()
