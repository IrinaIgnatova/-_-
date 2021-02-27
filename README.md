# Task3

a = int(input("Введите значение переменной a: "))
b = int(input("Введите значение переменной b: "))
c = int(input("Введите значение переменной c: "))
class Person:
    def __init__(self, a, b, c):
        self.a = a
        self.b = b
        self.c = c
        
   def check(self, a, b, c):
        if (a+b+c == 180):
            print ("True")
        else:
            print ("False")
