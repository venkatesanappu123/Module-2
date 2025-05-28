# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
a=int(input())
def fact(x):
    f=1
    for i in range(1,x+1):
        f*=i
    return f
for i in range(a):
    for j in range(i+1):
        a=fact(i)/((fact(j))*fact(i-j))
        print(int(a),end=" ")
    print()
```
## Sample Output
![440814303-5f42a960-dc01-40ec-9ecf-826053e3ff80](https://github.com/user-attachments/assets/3f68e96c-e2fa-4b0f-a04d-f46c657aa058)

## Result

Thus the program that generates Pascal's Triangle using numbers is executed successfully.

