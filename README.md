# unit-converter-
# 📌📌 Problem statement 
# Create a  CLI app that converts units like km to Miles celsius to fahrenheit based on user input
def km_to_miles(km):
    return km*0.621371
def miles_to_km(miles):
    return miles/0.621371
def c_to_f(celsius):
    return(celsius*9/5)+32
def f_to_c(fahrenheit):
    return(fahrenheit-32)*5/9
print("*"*15,"UNIT CONVERTER","*"*15)
print("1.Kilometer to Miles")
print("2. Miles to Kilometer")
print("3.Celsius to Fahrenheit")
print("4. Fahrenheit to celsius")
choise=input("Choose  conversion(1-4)===  ")
try:
    if   choise=="1":
        km=float(input("enter the kilometers"))
        print(f"{km}km to miles is{km_to_miles(km)}miles")
    if   choise=="2":
        miles=float(input("enter the miles"))
        print(f"{miles}miles to kilometer is{miles_to_km(miles)}km")
    elif   choise=="3":
        c=float(input("enter the celsous"))
        print(f"{c}celsius to faherenheit is{c_to_f(c)}F")
    elif   choise=="4":
        f=float(input("enter the kilometers"))
        print(f"{km}F to celsius{f_to_c(f)}c")
except ValueError:
    print("please enter a valied number")   
    
    
    
