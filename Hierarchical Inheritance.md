# Exp.No:25  
## Multi-level Inheritance

---

### AIM  
To write a Python program that collects a person's name, age, and salary, and displays them using multilevel inheritance in object-oriented programming.


---

### ALGORITHM

Start the program.

Define class a (base class):

In the constructor init(), get input for:

x → Name (string)

a → Age (integer)

b → Salary (integer)

Define class b inheriting from a:

Define dis1() to return name.

Define class c inheriting from a:

Define dis2() to return age.

Define class d inheriting from a:

Define dis3() to return salary.

Define class e inheriting from b, c, and d:

Use pass since it inherits everything needed.

Create an object y of class e.

Print the outputs from dis1(), dis2(), and dis3().

End the program.

---

### PROGRAM
class a:

   def __init__(self):
   
   self.x=input()
   
   self.a=int(input())
   
   self.b=int(input())
        
class b(a):

   def dis1(self):
   
   return self.x
    
class c(a):

 def dis2(self):
 
 return self.a 
 
class d(a):

   def dis3(self):
   
 return self.b
        
class e(b,c,d):

   pass

y=e()

print(y.dis1() ,y.dis2() ,y.dis3())


### OUTPUT  

![image](https://github.com/user-attachments/assets/534030ec-de3d-42fd-91f8-cb7345cfa810)



### RESULT
Thus the python program was initiated and implemented successfully.
