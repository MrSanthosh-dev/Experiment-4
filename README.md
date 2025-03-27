# Experiment-4
## ARMSTRONG NUMBER 
# Aim: Write a python program to check the number is Armstrong number or not and inspect for failures. 

# Algorithm
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

# Program
```
x = input("Enter a number: ")  

if x.isnumeric():  
    x = int(x)  
    temp = x  
    cube = 0  

    while temp > 0:  
        digit = temp % 10  
        cube += digit ** 3  
        temp //= 10  

    if cube == x:  
        print("Armstrong Number")  
    else:  
        print("Not an Armstrong Number")  
else:  
    print("Enter a Positive Integer.")
```

# Output

![image](https://github.com/user-attachments/assets/c6d368cf-59c9-4f74-ba12-6bdaf7cc6b08)

![image](https://github.com/user-attachments/assets/bb9df17d-240c-45f4-a468-bd0b439e7e28)

![image](https://github.com/user-attachments/assets/88419556-2bea-44f6-98da-32e3d1a31e97)

![image](https://github.com/user-attachments/assets/0a457cc4-fa97-463c-8582-664da1198efa)

![image](https://github.com/user-attachments/assets/eae84874-0e2e-442e-b67f-c99bf5210082)


# Result
Thus, the python program to check the number is Armstrong number or not implemented and the 
output is verified successfully.
