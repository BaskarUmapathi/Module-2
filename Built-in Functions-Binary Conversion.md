# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

```
x=16
y=bin(x)
print(y)
```
## Output
![image](https://github.com/user-attachments/assets/2e985875-d209-49d9-ad9e-5bb5b133ae3b)

## Result
Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.



## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```
## Output
![image](https://github.com/user-attachments/assets/f5719231-1cc7-443a-9942-d40ff7ec1748)

## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.


