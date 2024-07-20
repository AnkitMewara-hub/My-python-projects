1# project of electricity bill checking
unit = int(input("Enter your units:  "))
print("your units are: ",unit)

if(0<unit<100):
    print("no cahrges")
elif(100<unit<200):
    print("RS 5 per unit: ")
    print(int(unit)*int(5))
elif(unit==350):
    print("your amount is 2000")
else:
    print("incorrect value")


2# my project of divisible by 3 or not 
num = int(input("enter a number which is divisible or not:  "))
print("your number is: ",num)

if(num%3==0):
    print(num/3)
    print("given number is divisible by 3.")
else:
    print("given number is not divisible by 3.")


3# grading project
per = int(input("Enter the percentage: "))
print("your percantage is",per)

if(100>per>90):
    print("A grade")
elif(90>=per>80):
    print("B grade")
elif(80>=per>=60):
    print("C gade")
elif(0<per<60):
    print("D grade")
else:
    print("invalid percentage")


4# wheather the year is leap year or not 
year = int(input("Enter the year: "))
print("your entered year is:",year)

if(year % 100 == 0 and year % 400 == 0): 
    print("the given year {} is leap year:",format(year))

elif(year % 4 == 0 and year % 100 !=0):
    print("enter year {} is leap year ",format(year))
else:
    print("entered year {} is not leap year")


5# program for sunday, monday
day = int(input("Enter a day between 1 to 7: "))

if(day == 1):
    print("sunday")
elif(day == 2):
    print("monday")
elif(day == 3):
    print("tuesday")
elif(day == 4):
    print("wednesday")
elif(day == 5):
    print("thursday")
elif(day == 6):
    print("friday")
elif(day == 7):
    print("saturday")
else:
    print("entered number is not between 1 to 7")

6# The Entered number is three digit or not
num1 = (input("Enter a number: "))
L = len(num1)

if(L!= 3):
    print("Enter three digid number: ")
else:
    print("enter number is three digit number: ")


7# find smallest number from two given number 
num3 = int(input("Enter a first number: "))
num4 = int(input("Enter a second number: "))

if(num3<num4):
    print("Entered frist number is smaller",num3)
elif(num4<num3):
    print("Entered seconnd number is smaller",num4)
else:
    print("both number are same ")


8# Accept the ages of four people
age1 = int(input("Enter the age of person 1: "))
age2 = int(input("Enter the age of person 2: "))
age3 = int(input("Enter the age of person 3: "))
age4 = int(input("Enter the age of person 4: "))


if(age1 <= age2 and age1 <= age3 and age1 <= age4):
    youngest = age1
elif(age2 <= age1 and age2 <= age3 and age2 <= age4):
    youngest = age2
elif(age3 <= age1 and age3 <= age2 and age3 <= age4):
    youngest = age3
else:
    youngest = age4
    
print("The youngest age is:", youngest)


9# 75% programm of attendence 
present = int(input("Enter the total working days:  "))
absent = int(input("Enter the total number of absebties: "))
total_day = (present + absent)
per = (present/total_day)*100
print("The percentage of working days are: ",per)
if(per<75):
    print("Not allowed for examination")
else:
    print("Allowed for examination")


10# calculator
num9 = int(input("Enter a first number: "))
num10 = int(input("Enter a second number: "))
operator = (input("Enter a operator: "))

if(operator=='+'):
    print("Result is", num9 + num10)
if(operator=='*'):
    print("Result is", num9 * num10)
if(operator=='/'):
    print("Result is", num9 / num10)
if(operator=='%'):
    print("Result is", num9 % num10)
if(operator=='//'):
    print("Result is", num9 // num10)

11# calculator using match case statement 

x = int(input("Enter a number: "))
y = int(input("Enter second number: "))
oper = int(input("Enter the operator: "))
match oper:
    case 0:
        print(x + y)
    case 9:
        print(x * y)
    case 8:
        print(x / y)
    case 7:
        print(x % y)
    case 6:
        print(x // y)


# while loop
# multiplication table project
m = int(input("Enter the multiplication table: "))
n = 1
while n<=10:
    print(n*m)
    n += 1

def isgreater(a,b):
    if(a>b):
        print("frist number is greater: ")
    else:
        print("second number is greater: ")
# function using program
a = int(input("Enter the number : "))
b = int(input("Enter the second number : "))
isgreater(a,b)

c = int(input("Enter the number : "))
d = int(input("Enter the second number : "))   
    
isgreater(c,d)








    





    
