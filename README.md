# python.calculator
calculator easy
num_1 = input("number one??? : ")
num_2 = input("number Two??? " )
operation = input("choose one? +, -, *,")

if operation == "*":
    result = int(num_1) * int(num_2)
if operation == "+":
    result = int(num_1) + int(num_2)
if operation == "-":
    result = int(num_1) - int(num_2)
print(result)
