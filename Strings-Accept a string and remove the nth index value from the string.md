# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
def remove(str):  <br />
l=len(str)  <br />
a=""  <br />
n=int(input())  <br />
for i in range(0,l):  <br />
if i==n:  <br />
a=a+""  <br />
else:  <br />
a=a+str[i]  <br />
print(a)

## Output
<img width="638" height="183" alt="image" src="https://github.com/user-attachments/assets/8b93d0b3-4629-4c0b-a725-8086a88b5bf9" />

## Result
Thus ,the program has been executed successfully.
