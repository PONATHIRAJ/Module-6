# Exp.No:30  
##  Polymorphism

---

### AIM  
To write a Python program to create two classes Employee and Admin. These two different classes have the same method name info()

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**

---

### PROGRAM

```
class Employee:
    def info(self):
        print("Rooney from Electronics")
class Admin:
    def info(self):
        print("Kalesh from CS")
obj1= Employee()
obj2 = Admin()
obj1.info()
obj2.info()
```

### OUTPUT
![image](https://github.com/user-attachments/assets/df48b543-2f3e-4519-aba9-8e2fe3bebc7d)

### RESULT
