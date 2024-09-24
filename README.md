# Calculator
a=('''Simple Calculator
+ for addition, - for subtraction, * for multiplication, / for division''')
print(a)
choice=input("enter your choice +,-,*,/:")
n1=float(input("enter your first number"))
n2=float(input("enter your second number"))
if choice=='+':
  print("sum of n1 and n2:",n1+n2)
elif choice=='-':
  print("subtraction of n1 and n2:",n1-n2)
elif choice=='*':
  print("multiplication of n1 and n2:",n1*n2)
elif choice=='/':
  if n2==0:
    print("divided by zero is not define")
  else:
    print("division of n1 and n2:",n1/n2)
