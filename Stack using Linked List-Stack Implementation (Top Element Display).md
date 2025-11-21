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

## 💻 Program
```
stack = []

stack.append('a')
stack.append('b')
stack.append('c')
stack.append('d')
print('Initial stack: ' + str(stack))

print("\nElement at the top of the stack is .... ", stack[-1])

stack.pop()

print("\nAfter removing an element from the stack.")
print("\nElement at the top of the stack is .... ", stack[-1])
```

## Output

<img width="1053" height="336" alt="image" src="https://github.com/user-attachments/assets/60f7c031-f8ec-4413-a4a5-6c103deddeaa" />

## Result
Thus to write a python program to display the top element in stack implementation is created and executed successfully.
