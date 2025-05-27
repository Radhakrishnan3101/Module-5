# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

class Awesome:

  # some method
  
   def greetings(self):
   
  print("My name is Vishvajit Rao and I am 22 years old.")

    
  def __del__(self):
  
  print("Vishvajit Rao student is deleted.")


obj = Awesome()

obj.greetings()


### OUTPUT
![image](https://github.com/user-attachments/assets/4d12e5e5-2671-4789-9a41-58d39da87498)



### RESULT
Thus the python program was initialised and executed successfully.
