unit = input("give the input: ")
weight = int(input("enter your weight: "))
if unit.upper()=="L":
    converted = weight*0.45
    print(f'you are {converted} kilos')
else:
    converted = weight/0.45
    print(f'you are {converted} pounds')
