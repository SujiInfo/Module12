# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

##  Program
Add Code here
```
  stack = []
  stack.append('a')
  stack.append('b')
  stack.append('c')
  print('Initial stack: ' + str(stack))
  for i in range(len(stack)):
     print(i, end=" ")
     print(stack[i])
```
## Sample Input & Output
![image](https://github.com/user-attachments/assets/23981b48-1e1e-4d96-9de2-39f0ba0857ae)

## Result
Thus, the program has been execueted successfully.
