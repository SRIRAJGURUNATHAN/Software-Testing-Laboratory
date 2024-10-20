# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 30-08-2024                                                                           
### REGISTER NUMBER : 212222040161

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.

### Program:
### do...while:
```
def display(): 
    start=input("Enter a positive value for START: ") 
    end=input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start=int(start) 
            end=int(end) 
            print(start,end=" ") 
            if start<end: 
                start+=1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.") 
display() 
```
### while...do:
```
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
```
### switch:
```
def switch(): 
    switcher={ 0:"even", 1:"odd" } 
    n=input('Enter a value for N: ') 
    try: 
        n=int(n) 
        print(switcher[n%2]) 
    except ValueError: 
        print("Enter a valid number.") 

switch() 
```
### if..else:
```
def compare(): 
    a=input("Enter a value for A: ") 
    b=input("Enter a value for B: ") 
    try: 
        a=int(a) 
        b=int(b) 
        if a>b: 
            print("A is greater than B") 
        elif a<b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")

compare()
```
### for:
```
def iterate(): 
    string=input("Enter a string: ") 
    for i in string: 
        print(ord(i),end=" ") 
iterate()
```

### Output:
### do...while:

![STL EXP1(I)](https://github.com/user-attachments/assets/9c3bc992-c639-4b4a-83d3-78044da59451)


### while...do:

![STL EXP1-(II(1))](https://github.com/user-attachments/assets/4da62cd2-dc9a-4a8a-9678-17b3fb4a06a6)
![STL EXP1-(II(2))](https://github.com/user-attachments/assets/c2db5137-40ab-4fad-865e-0e5d011431b2)


### switch:

![STL EXP1-(III)](https://github.com/user-attachments/assets/4e4fac77-ff45-4afa-b694-7fd63be3d614)


### if..else:

![STL EXP1-(IV)](https://github.com/user-attachments/assets/12666a67-e4b8-4a14-a53a-24915549bdb8)


### for:

![STL EXP1-(V)](https://github.com/user-attachments/assets/c639bcd1-5a84-4b8e-8710-63aaf6c4ebb9)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


