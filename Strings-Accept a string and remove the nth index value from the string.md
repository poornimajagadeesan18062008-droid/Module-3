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
```
def remove(b):
  n=int(input("index:"))
  a=''
  for i in range(len(b)):
    if i!=n :
      a+=b[i]
  return a
b=input()
print(remove(b))
    
```

## Output
<img width="1663" height="186" alt="image" src="https://github.com/user-attachments/assets/39dd1587-8626-4f66-b47a-6e2b9a17355b" />


## Result
Thus,to write a Python program that accepts a string and removes the character at a specified index is executed successfully.
