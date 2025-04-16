# OOP
Python Oop Assignment

Assignment 1: Design Your Own Class! 🏗️
🎯 Objective:
Create your own class, add some properties (attributes) and functions (methods), and make it feel real using object-oriented programming concepts: constructor, inheritance, polymorphism, or encapsulation.

A Superhero Class 
1️⃣ Create the Class

class Superhero:
    def __init__(self, name, power, age):
        self.name = name
        self.power = power
        self.age = age

__init__() → the constructor method, used to give each object its own unique values

self.name, self.power, self.age → these are attributes of the superhero.

2️⃣ Add Some Methods
Let’s add behavior to our superhero:

    def introduce(self):
        print(f"My name is {self.name}, I am {self.age} years old and my power is {self.power}.")

    def save_the_day(self):
        print(f"{self.name} uses {self.power} to save the day!")
        
3️⃣ Create Objects

hero1 = Superhero("Wonder Wani", "Invisibility", 25)
hero2 = Superhero("Captain Kenya", "Super Speed", 30)

hero1.introduce()
hero2.save_the_day()

4️⃣ Add Inheritance 👨‍👩‍👧
create a subclass for a Villain that inherits from Superhero:
class Villain(Superhero):
    def evil_laugh(self):
        print(f"{self.name} says 'Mwahaha!' and uses {self.power} for evil.")

bad_guy = Villain("Dr. Doom", "Mind Control", 40)
bad_guy.introduce()
bad_guy.evil_laugh()


✅ Activity 2: Polymorphism Challenge! 🎭
🎯 Objective:
Create different classes with the same method name (move()), but each one acts differently.

1️⃣ Create Multiple Classes

class Dog:
    def move(self):
        print("Dog is walking ")

class Fish:
    def move(self):
        print("Fish is swimming ")

class Bird:
    def move(self):
        print("Bird is flying ")
        
2 Polymorphism in Action

animals = [Dog(), Fish(), Bird()]

for animal in animals:
    animal.move()

All classes have a move() method.


