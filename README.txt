Main concept of object oriented programming (OOPS):
1)class
2)object
3)polymorphism
4)Encapdulation
5)Inheritance
6)Data Abstarction

** Object oriented programming(oops):
    Total code is divided into objects.
    There things are very important in oop:
        1)class
        2)object
        3)referance variable

**What is class:
    -> class is a blueprint plan to constact object
    -> class is a logical entity
    -> class does not require momory for execution
    -> class is a user defined data type
    syntax: 
        class class_name:
            body_of_class

    e.g.
        class A:
            pass

**What is object:
    -> It is a physical entity
    -> It is a instance of class. instance-> means object.
    -> Object requires memory for execution.
    syntax:
        referance_vairable = class_name
    e.g.
        a1 = A()

** What is referance vairable:
    -> It is a vairable which is pointing to object and used to access the functionality of the object.

**Relation between**
1) class and object --> one to many
2) object and referance vairable --> one to one

** By using class we can group variable ??
eg.1.

class student:
    def __init__(self, nm, rl, mk):
        self.name = nm
        self.roll = rl
        self.marks = mk

s1 = student('jay', 1, 88)
print(f"student name is {s1.name}, roll number is {s1.roll} and marks are {s1.marks}")

s1 = student('viru', 2, 70)
print(f"student name is {s1.name}, roll number is {s1.roll} and marks are {s1.marks}")

o/p
student name is jay, roll number is 1 and marks are 88
student name is viru, roll number is 2 and marks are 70

eg.2.

class student:
    def __init__(self, nm, rl, mk):
        self.name = nm
        self.roll = rl
        self.marks = mk

    def get_details(self):
        print(f"student name is {self.name}, roll number is {self.roll} and marks are {self.marks}")

s1 = student('jay', 2, 88)
s1.get_details()

s2 = student('viru', 2, 70)
s2.get_details()

o/p :
student name is jay, roll number is 1 and marks are 88
student name is viru, roll number is 2 and marks are 70

