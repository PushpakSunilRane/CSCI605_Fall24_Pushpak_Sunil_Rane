# CSCI605 - DATA STRUCTURE AND ALGORITHM 
# ASSIGNMENT - 01

# Calculator using Python
____________________________________________________________________________
Calculator performs fours basic operations :-
    1. Addition
    2. Substraction
    3. Multiplication
    4. Division
____________________________________________________________________________
Initially code asks to select operation number to perform through user input.
____________________________________________________________________________
Then, after entering number :-
    if selected number = (1-4) then
        ask for user input for two values to perform operation on such as 2 and 4.
        if entered values != (int/float)
            print("Invalid input, enter correct input values...!!")
    if selected number != (1-4) then
         print("Invalid input...!!")
_____________________________________________________________________________
then performing calculations as per selection of operation number :-
    if operation number = 1 then
        perform addition,display result and ask whether to continue or exit.
    if operation number = 2 then
        perform substraction,display result and ask whether to continue or exit.
    if operation number = 3 then
        perform multiplication,display result and ask whether to continue or exit.
    if operation number = 4 then
        if num2 = 0 then 
            print("Division Error.")
        else
            perform division,display result and ask whether to continue or exit.
_______________________________________________________________________________
Choose to continue or exit operations -:
    if calc = Y then
        start from initial step from entering operation to perform.
    if calc != Y then
        print("Calculator Shutdown Successfully") and break loop to exit from program.
________________________________________________________________________________
