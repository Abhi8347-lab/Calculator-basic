
operation = input('Enter any arthmetic operation(+,-,*,/)')
num1 = float(input('Enter number1: '))
num2 = float(input('Enter number2: '))

if operation == '+':
    result = num1 + num2
    print(result)
    result7 = round(num1 + num2, 2)
    print(f'approx = {result7}')
    
elif operation == '-':
    result = num1 - num2
    print(result)
    result8 = round(num1 - num2, 2)
    print(f'approx = {result8}')

elif operation == '*':
    result = num1 * num2
    print(result)
    result9 = round(num1 * num2,2)
    print(f'approx = {result9}')



elif operation == '/':
    result = num1 / num2
    print(result)
    result2 = num1 % num2
    print(f'remainder = {result2}')
    result3 = round(num1 / num2, 2)
    print(f'approx = {result3}')
    
else:
    print("Invalid operator")
