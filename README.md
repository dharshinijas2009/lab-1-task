'''#safe calculator
try:
    a=int(input("Enter a num:"))
    b=int(input("Enter a num:"))
    print(a/b)
except ZeroDivisionError:
    print("Division by zero is not posssible")

#ATM
try:
   print("Available amount 20000")
   a=int(input("Enter the amount:"))
   if a>20000:
    raise ValueError("Enter valid amount")      
except ValueError as e:
    print(f"Error:{e}")
else:
    print("Processing..")
    print(f"With drawing${a}")

#file opener
try:
    a=input("Enter a file name:")
    with open(a,'r') as f:
        conent=f.open()
        print(content)
except:
    print("Error:File not found")

#marks
try:
    a=int(input("Enter your mark:"))
    if a<0 or a>100:
        raise ValueError("Invalid mark")
except ValueError as e:
    print(f"Error:{e}")'''
 



    

    

    
