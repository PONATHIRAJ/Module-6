# Exp.No:26  
## Method Overriding

---

### AIM  
To write a Python program to create a class  Player with two private attributes name and player number, change the value of the attributes  with getters and setters for both. 

class Player:
    def __init__(self, name: str, player_number: int):
        self.__name = name
        self.__player_number = player_number

---

### ALGORITHM

1. **Begin the program.**
2. **Define the Bird class**:
   - Create a method `intro()` to print "There are many types of birds."
   - Create a method `flight()` to print "Most of the birds can fly but some cannot."
3. **Define the Sparrow class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Sparrows can fly."
4. **Define the Ostrich class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Ostriches cannot fly."
5. **Create an object `obj_bird`** of the `Bird` class.
6. **Create an object `obj_spr`** of the `Sparrow` class.
7. **Create an object `obj_ost`** of the `Ostrich` class.
8. **Print the general message** "There are many types of birds."
9. **Call the `flight()` method** on each object (`obj_bird`, `obj_spr`, `obj_ost`) to display the respective messages.
10. **Terminate the program.**

---

### PROGRAM

```
class Player:
    def __init__(self):
        self.a = 'Betty Ballmer'
        self.b = 10 
    def getter(self):
        print(self.a)
        print(self.b)
    def setter(self,a,b):
        self.a = a
        self.b = b
obj = Player()
obj.getter()
obj.setter('Buster Ballmer',11)
obj.getter()
```

### OUTPUT
![image](https://github.com/user-attachments/assets/326eef05-5f61-45cf-bc50-d0039e3b44b2)

### RESULT
Thus, the program is executed and verified successfully.
