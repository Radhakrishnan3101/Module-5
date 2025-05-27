# Exp.No:24  
## PYTHON PROGRAM TO DISPLAY STUDENT DETAILS AND VALIDATE STUDENT ID

---

### AIM  
To write a Python program to input student details such as student ID and name, display them using a tuple, and validate the student based on the ID.

---

### ALGORITHM

Start the program.

Define a class stu.

In the constructor init():

Accept student ID (a) as integer input.

Accept student name (b) as string input.

Define a method s1():

Return a tuple containing the student ID and name.

Define another method s2():

If student ID > 100000:

Return "Valid Student".

Else:

Return "Invalid Student".

Create an object x of class stu.

Call s1() and s2() using the object and display both results using formatted output.

End the program.

---

### PROGRAM


class stu:

   def __init__(self):
   
 self.a = int(input())
 
 self.b = input()
        
   def s1(self):
    
 return tuple([self.a, self.b])
        
   def s2(self):
    
   if self.a > 100000:
   
   return "Valid Student"
   
 else:
 
   return "Invalid Student"
            
x = stu()

print("{}  {}".format(x.s1(), x.s2()))



### OUTPUT
![image](https://github.com/user-attachments/assets/21372605-d8d1-4ca5-8a75-dcc00a5c06bf)

### RESULT
Thus the python program was initiated and implemented successfully.
