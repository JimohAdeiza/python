# Python Script

**#Area of Triangle**
def area_of_triangle():
        b = int(input("Enter the base of triangle"))
        h = int(input("Enter it's height"))
        area = 1/2 * b * h
        print(f"The area of the triangle is {area}")
area_of_triangle()

#Area of Rectangle
def area_of_rectangle():
    w = int(input("enter width of rectangle"))
    l = int(input("enter length of rectangle"))
    area_rec = l*w
    print(f"The Area of Rectangle is {area_rec}")
area_of_rectangle()

#Perimeter of a Square
def perimeter_of_square():
    h = int(input("Enter the length of square"))
    perimeter = 4*h
    print(f"The perimeter of a square is {perimeter}")
perimeter_of_square()

#Area of a Circle
def Area_of_a_circle():
    r = int(input("Enter Radius of a Circle "))
    pi = 22/7
    Area = pi*r**2
    print(f"The Area of a Circle is {Area}")
Area_of_a_circle()

#Lagos State University Law Departments Admissions Cut off Mark Automation.
#jamb total is over 400
#jamb score is 240
jambscore = 240/8
print(jambscore)
english = 70
if english >=75 and english <=100:
  print("A")
elif english >=60 and english <=74:
  print("B")
elif english >=50 and english <=59:
  print("C")
elif english >=40 and english <=49:
  print("D")
elif english >=30 and english <=39:
  print("E")
elif english >=20 and english <=29:
  print("F")
else:
  print("undefined")
mathematics = 65
if mathematics >=75 and mathematics <=100:
  print("A")
elif mathematics >=60 and mathematics <=74:
  print("B")
elif mathematics >=50 and mathematics <=59:
  print("C")
elif mathematics >=40 and mathematics <=49:
  print("D")
elif mathematics >=30 and mathematics <=39:
  print("E")
elif mathematics >=20 and mathematics <=29:
  print("F")
else:
  print("undefined")
goverment = 75
if goverment >=75 and goverment <=100:
  print("A")
elif goverment >=60 and goverment <=74:
  print("B")
elif goverment >=50 and goverment <=59:
  print("C")
elif goverment >=40 and goverment <=49:
  print("D")
elif goverment >=30 and goverment <=39:
  print("E")
elif goverment >=20 and goverment <=29:
  print("F")
else:
  print("undefined")
literature = 68
if literature >=75 and literature <=100:
  print("A")
elif literature >=60 and literature <=74:
  print("B")
elif literature >=50 and literature <=59:
  print("C")
elif literature >=40 and literature <=49:
  print("D")
elif literature >=30 and literature <=39:
  print("E")
elif literature >=20 and literature <=29:
  print("F")
else:
  print("undefined")
economics = 60
if economics >=75 and economics <=100:
  print("A")
elif economics >=60 and economics <=74:
  print("B")
elif economics >=50 and economics <=59:
  print("C")
elif economics >=40 and economics <=49:
  print("D")
elif economics >=30 and economics <=39:
  print("E")
elif economics >=20 and economics <=29:
  print("F")
else:
  print("undefined")
A = 10
B = 8
C = 6
D = 4
E = 2
F = 0
if english >=60 and english <=74:
	print('english, grade = B = 8')
if mathematics >=60 and mathematics <=74:
	print('mathematics, grade = B = 8')
if goverment >=75 and goverment <=100:
	print('goverment, grade = A = 10')
if literature >=60 and literature <=74:
	print('literature, grade = B = 8')
if economics >=60 and economics<=74:
	print('economics, grade = B = 8')
Olevelresultgradepoint = (B+B+A+B+B)
print(Olevelresultgradepoint)
lasulawcutoff = jambscore + Olevelresultgradepoint
print(lasulawcutoff)
if lasulawcutoff >=70 and lasulawcutoff <=100:
	print("Congratulation you passed successfully")

#Quadratic formula

import math
a = int(input("enter the value of a"))
b = int(input("enter the value of b"))
c = int(input("enter the value of c"))
X1 = (-b + math.sqrt(b**2 - 4*a*c))/2*a
X2 = (-b - math.sqrt(b**2 - 4*a*c))/2*a
print(a)
print(b)
print(c)
print(X1)
print(X2)


#SIMPLE CALCULATOR
def add(x,y):
    return x + y
def subtract(x,y):
    return x - y
def multiply(x,y):
    return x * y
def divide(x,y):
    return x / y

print("select operation.")
print("1.add")
print("2.subtract")
print("3.multiply")
print("4.divide")

while True:
    choice = input("enter choice(1/2/3/4):")
    if choice in ("1","2","3","4"):
        numb1 = float(input("enter number:"))
        numb2 = float(input("enter number:"))
        
        if choice == "1":
            print(numb1, "+",numb2,"=",add(numb1,numb2))
        elif choice == "2":
            print(numb1, "-",numb2,"=",subtract(numb1,numb2))
        elif choice == "3":
            print(numb1,"*",numb2,"=",multiply(numb1,numb2))
        elif choice == "4":
            print(numb1,"/",numb2,"=",divide(numb1,numb2))
        Another_calculation = input("do you want to do another calculation? (yes/no):")
        if Another_calculation == "no":
            break
    else:
        print("continue")
        
            
