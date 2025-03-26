Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for

REGISTER NUMBER : 212222040102
AIM:
To write python programs for do…while, while, for, switch and if…else and test with possible test Cases

Algorithm:
Start the program.
Create separate files for each given program.
Write simple program for each construct.
the program with possible test cases.
Stop the program.
Program:
i)do…while:

def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
ii) while…do:

start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")
iii) switch:

def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 
iv) if else:

def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”) 
v.) for:

def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 

Output:
i)do…while:

Screenshot 2024-10-01 135840

ii) while…do:

Screenshot 2024-10-01 141338

iii) switch:

Screenshot 2024-10-01 143652

iv) if else:

Screenshot 2024-10-08 142941

v) for:

Screenshot 2024-10-08 143731

Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.








