```python
operator = input("Enter an operator ( + - * /): ")
num1 = float(input("Enter the 1st number: "))
num2 = float(input("Enter the 2nd number: "))

if operator == "+":
    result = num1 + num2
    print (round(result, ))
elif operator == "-":
    result = num1 - num2
    print (round(result, ))
elif operator == "*":
    result = num1 * num2 
    print (round(result, ))
elif operator == "/":
    result = num1 / num2
    print (round(result, ))
else  :
    print (f"{operator} is not a valid operator")
   
```

    Enter an operator ( + - * /):  +
    Enter the 1st number:  78
    Enter the 2nd number:  89
    

    167
    


```python

```
