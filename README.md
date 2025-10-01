# Stack-Implementation-Using-Array-in-CPP  

## Aim  
To study and implement **Stack implementation using array** in C++.  

## Software Required  
- Visual Studio  

---

## Theory  

A **stack** is one of the fundamental data structures in computer science, used to store a collection of objects. It operates on the **Last In, First Out (LIFO)** principle: the most recently added element is the first to be removed.  

This property makes stacks highly useful in scenarios such as reversing operations, implementing undo features, and managing nested function calls.  

### Stack Data Structure in C++  
A stack can be visualized as a vertical collection of elements, much like a stack of plates. We can only **add (push)** or **remove (pop)** the top plate. Similarly, in a stack data structure, elements can be inserted and removed only from the **top**.  

There are two common implementations:  

- **Array-based implementation:** Uses a fixed-size array to store elements, with a pointer/index `top` to track the current top element.  
- **Linked-list-based implementation:** Each element is represented by a node in a linked list, with the head acting as the top of the stack.  

### Applications of Stack in C++  
- Expression evaluation (prefix, postfix, infix).  
- Function calls and recursion.  
- Undo functionality in text editors.  
- Syntax parsing and syntax checking.  

---

## Implementation  
The following implementation demonstrates **stack operations** (push and pop) using arrays in C++.  

---

## Algorithm  

**Algorithm: Stack using Array**  

1. Start  
2. Initialize an array `arr[SIZE]` and set `top = -1`.  
3. **Push Operation (Insert):**  
   - If `top == SIZE - 1`, display **"Stack Overflow"**.  
   - Else, increment `top` by 1 and set `arr[top] = new_element`.  
4. **Pop Operation (Delete):**  
   - If `top == -1`, display **"Stack Underflow"**.  
   - Else, print the element `arr[top]` and decrement `top` by 1.  
5. Perform multiple push operations and check for overflow.  
6. Perform multiple pop operations and check for underflow.  
7. Display the stack contents.  
8. End  

---

## Conclusion  

The above program demonstrates the implementation of a **stack using arrays in C++**.  
Key concepts covered:  

- **Push operation** to insert elements into the stack.  
- **Pop operation** to remove elements from the stack.  
- **Overflow and underflow conditions** for error handling.  

This implementation provides the foundation for understanding stack behavior and its applications in real-world problem-solving.  
