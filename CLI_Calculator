import math
def algebric_operation():
    a=float(input("Enter the Value of a:"))
    b=float(input("Enter the Value of b:"))
    userinput=input("Enter the Operation:(+,-,*,/):")
    if(userinput == '+'):
        print("The Addition of both num is:",a+b)
    elif(userinput == '-'):
        print("The Subtraction of both num is:",a-b)
    elif(userinput == '*'):
        print("The Multiplication of both num is:",a*b)
    elif(userinput == '/'):
        if(b == 0):
            print("Invalid! Denominator Can't be 0")
        else:
         print("The Division of both num is:",a/b)
    else:
        print("Sorry! Choose the correct operation")
def trigo_operation():
    userinput=input("Select the operation Sin/Cos/Tan/log/sqrt/power:").lower()
    if(userinput == 'sin'):
        angle=float(input("Enter the Angle:"))
        value=math.sin(math.radians(angle))
        print(value)
    elif(userinput == 'cos'):
        angle=float(input("Enter the Angle:"))
        value=math.cos(math.radius(angle))
        print(value)
    elif(userinput == 'tan'):
        angle=float(input("Enter the Angle:"))
        value=math.tan(math.radius(angle))
        print(value)
    elif(userinput == 'log'):
        x=int(input("Enter the Value:"))
        if(x>0):
         value=math.log(x)
         print(value)
        else:
            print("ERROR! Negative Num Not Have log Value")
    elif(userinput == 'sqrt'):
        y=int(input("Enter the Value:"))
        if(y>0):
         value=math.sqrt(y)
         print("The Squart Root of this Num is:",value)
        else:
         print("Error! negative num doesn't have sqrt value")
    elif(userinput == 'power'):
       base=float(input("Enter the Base:"))
       exp=float(input("Enter the Exponent:"))
       result = math.pow(base, exp)
       print(f"{base} to the power {exp} is:{result}")
    else:
       print("please! enter the correct operation")
def conversion_operator():
    print("1. cm <-> inch")
    print("2. kg <-> lb")
    print("3. Celsius <-> Fahrenheit")
    choice = int(input("Enter your choice: "))
    if(choice == 1):
       unit=input("Enter the unit Which You want(cm/inch): ").lower()
       if(unit == 'cm'):
          value=float(input("enter the value in inch:"))
          val=value/2.5
          print("The value of lenght in cm is:",val)
       elif(unit == 'inch'):
          value=float(input("enter the value in cm:"))
          val=value*2.5
          print("The value of lenght in inch is:",val)
       else:
        print("Invalid Unit!")
    elif(choice == 2):      
        unit=input("Enter the unit Which You want(kg/lb): ").lower()
        if(unit == 'kg'):
          value=float(input("enter the value in lb:"))
          val=value/2.20462
          print("The value of weight in kg is:",val)
        elif(unit == 'lb'):
          value=float(input("enter the value in kg:"))
          val=value*2.20462
          print("The value of weight in lb is:",val)
        else:
         print("Invalid Unit!")
    elif(choice == 3):      
         unit=input("Enter the unit Which You want(c/f): ").lower()
         if(unit == 'c'):
          value=float(input("enter the value in Fahrenheit:"))
          val=value/2.20462
          print("The value of Temp in Celcius is:",val)
         elif(unit == 'f'):
          value=float(input("enter the value in Celcius:"))
          val=value*2.20462
          print("The value of Temp in Fahrenheit is:",val)
         else:
          print("Invalid Unit!")
    else:
     print("Invalid Choice!")    

def main():
    print("\n========== Smart CLI Calculator ==========")
    print("1. Basic Arithmetic (+, -, *, /)")
    print("2. Scientific Functions (sin, cos, log, sqrt, power)")
    print("3. Unit Conversion (cm<->inch, kg<->lb, Celsius<->Fahrenheit)")
    print("4. Exit")
    print("==========================================")
    while True:
         choice = input("Enter your choice (1-4): ")
         if choice == "1":
          algebric_operation()
         elif choice == "2":
             trigo_operation()
         elif choice == "3":
             conversion_operator()
         elif choice == "4":
            print("Thank you for using Smart CLI Calculator!")
            break
         else:
          print("Invalid choice! Try again.")
         again = input("Do you want to do another calculation? (y/n): ").lower()
         if again != 'y':
          print("Thank you for using Smart CLI Calculator!")
          break   
main()
