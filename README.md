# Exception-handling-
# Aim:-
To implement a C++ program that demonstrates exception handling during division, particularly when the denominator is zero.
To implement a C++ program that demonstrates exception handling for validating age input.

# Apparatus:-
vs code(C++ complier)

# Theory:-
Exception handling in C++ is used to manage runtime errors gracefully without crashing the program.

It uses try, throw, and catch keywords.

If an invalid condition occurs (like division by zero), an exception is thrown inside the try block.

The catch block receives the exception and handles it with a proper error message.
Exception handling helps in validating user inputs.

If a condition violates predefined rules (like age < 18), an exception is thrown.

The catch block handles the error and informs the user without crashing the program.

# Algorithm:-
# Program 1:

1. Start the program.
  
2. Declare three variables: n1, n2, ans.
   
3. Take input values for n1 and n2.
  
4. Enter try block:

If n2 == 0, then throw n2.

Else, perform ans = n1 / n2 and display result.

5. Enter catch block:
6. 
Display error message "ERROR: Division by 0".

8. End program.

# Program 2:-

1. Start the program.
  
2. Declare variable age.
   
3. Take input for age.

4. Enter try block:

If age < 18, then throw age.

Else, display "Age: <age>" and "APPROVED".

5. Enter catch block:

Display error message "ERROR: Underage!".
