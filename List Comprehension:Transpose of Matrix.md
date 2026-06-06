# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:


```
def create(r, c):
    matrix = []
    for i in range(r):
        row = list(map(int, input().split()))
        matrix.append(row)
    return matrix


r = int(input())
c = int(input())

mat = create(r, c)

transpose = [[mat[j][i] for j in range(r)] for i in range(c)]

print(transpose)
```

## OUTPUT:

<img width="587" height="305" alt="image" src="https://github.com/user-attachments/assets/016055e2-0970-4a83-8cbe-18f968b0b6ba" />


## RESULT:

The program is excuted successfully and the output is verified.


