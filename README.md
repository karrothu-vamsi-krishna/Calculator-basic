# Calculator-basic
# Its a basic calculator which contains division and multiplication and addition and subtraction of only 2 numbers
# Begginer Friendly
print(''' 1.addition
2.subtraction
3.multiplication
4.division
5.exit''')
while True:
  enter_choice = int(input("enter number = " ))
  if enter_choice==5:
    print("exit")
    break
  if enter_choice != 5 :
    a = int(input("a = "))
    b = int(input("b = "))
    if enter_choice==1:
      sum = a+b
      print(f"result = {sum}")
    elif enter_choice==2:
      subtraction = a-b
      print(f"result = {subtraction}")
    elif enter_choice==3:
      multiplication = a*b
      print(f"result = {multiplication}")
    elif enter_choice==4:
      if b == 0:
        print("division by 0 not possible")
      else :
        division = a/b
        print(f"result = {division}")
  
