# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE: 06-03-2025                                                                           
### REGISTER NUMBER : 212222040102
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:
```
x = input("Enter the input: ")
if x.isnumeric():
    x = int(x)
    temp = x
    cube = 0
    while temp > 0:
        digit = temp % 10
        cube = cube + (digit ** 3)
        temp //= 10
    if cube == x:
        print("Armstrong Number")
    else:
        print("Not Armstrong Number")
else:
    print("Enter a Positive Integer.")


```

### Output:
```
Enter the Input: 0
Armstrong Number

Enter the Input: 153
Armstrong Number

Enter the Input: 44
Not a Armstong Number

Enter the Input: -153
Not a Armstrong Number
Reason: The input can only be a positive integer.

Enter the Input: Teja
Enter a positive integer
Reason: The input can only be of a positive integer.

Enter the Input: !@#
Enter a positive integer
Reason: The special characters are not allowed

