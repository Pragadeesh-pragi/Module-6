# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, breadth):
        # Private member variables
        self.__length = length
        self.__breadth = breadth

    def display(self):
        # Accessing private variables within the class
        print(f"Length: {self.__length}")
        print(f"Breadth: {self.__breadth}")

# Create an object of Rectangle
rect = Rectangle(10, 5)
rect.display()
```
## Output
<img width="1096" height="897" alt="image" src="https://github.com/user-attachments/assets/5c4dd8e1-50b2-4596-9c42-63790dae7e47" />

## Result
Thus To implement Encapsulation in Python by defining a class Rectangle with private member variables __length and __breadth has been executed sucessfully.
