
#!/bin/bash


read -p "Enter a number: " numecho "You have entered the number $num"

I have learned about Control Flow in shell scripting and that it directs the order
in which commands or insreuctions are executed in a script.
I learned that control flow statement is the 
backbone of making decisions in programming .Control flow in shell scripting allows you to execute 
different parts of your script based on certain conditions.

Example of some common shell script flow construct.
examining the if-else statement and the for statement

1.if-else Statement : 

The script below will tell us if the stdin is positive,negative or zero

#!/bin/bash

read -p "Enter a Number" numeral

if   [ $numeral -gt 0 ]; then
     echo "The number is a positive number."
elif [ $numeral -lt 0 ]; then
     echo "The number is a negative number."
else echo "Number is zero"
fi

Thus,I have learned how the if,elif and if statement works


2. for Loops: I have learned that there are three primary loops that are commonly used 
to repeat a set of commands multiple times based on set conditiond.
1.for
2.while
3.Until

I have learned how to iterates using the for loop and leant the different forms of the for loops 
which are the list form and C-style form.

Example of a list form style is the script below.

#!/bin/bash

for i in 1 2 3 4 5
do
    echo "Hello, World! This is message $i"
done

Example of c-style form is the script below.

#!/bin/bash
for (( i=0; i<5; i++ )); do
    echo "Number $i"
done

MAKING A TRIAL COMMIT AT THE BUTTOM OF MY GAME!!

OK SEEN
MYADDED ADDENDED
wasnt better
