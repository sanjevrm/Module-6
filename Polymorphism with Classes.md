# 🐍 Python OOP: Polymorphism with Classes
## Name: SANJEV R M
## Reg No: 212223040186
## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
~~~
  class Beans:
      def type(self):
          print("Vegetable")
      
      def color(self):
          print("Green")
  
  
  class Mango:
      def type(self):
          print("Fruit")
      
      def color(self):
          print("Yellow")
  
  def func(obj):
      obj.type()
      obj.color()
  beans_obj = Beans()
  mango_obj = Mango()
  print("Beans object:")
  func(beans_obj)
  
  print("\nMango object:")
  func(mango_obj)
~~~
## Output
![446373655-42ca840d-9836-4dbb-ab25-3a0a420a1f40](https://github.com/user-attachments/assets/5ac40734-9f5b-4772-817f-60520524f79e)

## Result
Thus, the program is verified successfully.
