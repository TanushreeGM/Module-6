# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program

<img width="465" height="280" alt="image" src="https://github.com/user-attachments/assets/09dc81d6-3607-4ac6-a0f2-4ba1b6cfde55" />

## Output
<img width="233" height="43" alt="image" src="https://github.com/user-attachments/assets/b9f83629-0bbd-4eed-98ec-7a8e71730114" />

## Result
Thus, the program is successfully executed.
