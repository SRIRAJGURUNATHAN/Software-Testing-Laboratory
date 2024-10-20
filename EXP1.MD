# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:30.08.2024                                                                            
### REGISTER NUMBER : 212222040161

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
### a) do…while 
```
def display(): 
 
 start=input("Enter a positive value for START: ") 
 end=input("Enter a positive value for END: ") 
 if start.isnumeric() and end.isnumeric(): 
   while True: 
     start=int(start) 
     end=int(end)  
     print(start,end='')  
     if start<end: 
        start+=1 
     else: 
        break 
 else: 
  print("Enter a valid positive number.",)
display()
```
### b) while…do
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
### c) if …else 
```
def compare(): 
    a = input("Enter a value for A: ") 
    b = input("Enter a value for B: ") 
    
    try: 
        a = int(a) 
        b = int(b) 
        if a > b: 
            print("A is greater than B") 
        elif a < b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")


compare()

```
### d)switch
```
def check_odd_even(): 
    switcher = { 
        0: "even", 
        1: "odd" 
    } 
    
    n = input('Enter a value for N: ') 
    try: 
        n = int(n)  # Convert input to an integer
        print(switcher[n % 2])  # Access the dictionary based on n % 2
    except ValueError: 
        print("Enter a valid number.") 

# Call the function
check_odd_even()

```
### e)for
```
def iterate(): 
 string=input("Enter a string: ") 
 for i in string: 
  print(ord(i),end=" ") 
iterate() 
```













### Output:


### a) do…while
![image](https://github.com/user-attachments/assets/6af9b788-5e56-453f-887e-b4995602a12a)
![image](https://github.com/user-attachments/assets/d962af1b-f22b-4073-9d4e-36e5104eefcd)


### b) while…do
![image](https://github.com/user-attachments/assets/39e14987-f626-42a4-9758-5962ac5f1d33)
![image](https://github.com/user-attachments/assets/fa361c0b-b5c0-4728-a907-f5c28f557f3d)



### c) if …else 
![image](https://github.com/user-attachments/assets/b1b6aaca-9b6f-4723-90e2-d166ce411bb7)



### d)switch
![image](https://github.com/user-attachments/assets/99913595-47a5-497d-a62f-818c195c8c8a)

### e)for
![image](https://github.com/user-attachments/assets/9c545a28-60ca-4595-bfab-c17180151b16)






### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


