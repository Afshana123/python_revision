
-[x] Declare a function with the correct syntax called user_name

```python
def user_name():
    pass
```

-[x] Iterate over the list_num = [9, ,8 , 7, 6, 5]

```python
list_num = [9, 8 , 7, 6, 5]
for list in list_num:
    print(list)
```

-[x] How would you apply an `and` operation between two boolean values?

```python
    # Here is an example code:
elif (age >= 15 and age < 18 ):
    print("Hello")
```

-[x] What is the difference between a list and tuple?
```python
Lists:
- are mutable
- Syntax [""]

Tuples:
- are immutable 
- Syntax ("")
```

- [x] Can you add items to tuples?

```python
No, you cannot add items to tuples. 
```

- [x] What is the data collection type for num_id = {'0': 1, '5' : 9 }
```python
It is a dictionary.
```

- [x] What is the syntax to create an object of a class
```python
# any name = class()
snake_object = Snake()
```

- [x] Here is a list called value_list = [9, ,8 , 7, 6, 5]. Add 9 to this list.

```python
value_list = [9, 8 , 7, 6, 5]

value_list.append(9)
print(value_list)

```

- [x] Create a function called greetings that takes 1 string arg "name" and should return True if arg is equal to string "name" otherwise return False 
```python
def greeting(name):
    if name == "name":
        return True
    else:
        return False

print(greeting("name"))
```
- [x] Write the syntax to inherit class A in class B
```python
from animal import Animal

class Reptile(Animal):

    def __init__(self):
```
- [x] Write the syntax for super
```python
super().__init__()
```

- [x] Declare a function that takes a list of numbers as an arg and should iterate over the list and return only even numbers from the list. Create a list with numbers 1 to 11 to use in this function.

````python
def list_of_numbers(list):

    for number in list:
        if number % 2 == 0:
            print(number)
        else:
            continue

list = [1, 2, 3, 4, 5, 6, 7, 9, 10, 11,]
print(list_of_numbers(list))

# to return it

def list_of_numbers(list):

    even_number = []

    for number in list:
        if number % 2 == 0:
            even_number.append(number)
        else:
            continue
    return even_number

list = [1, 2, 3, 4, 5, 6, 7, 9, 10, 11,]
print(list_of_numbers(list))

````
- [x] Create a basic calculator with add, subtract, divide and multiply with return statements to return the mathematical value

```python
def add(value1, value2):
    return value1 + value2

print(add(2, 3))

def subtract(value1, value2):
    return value1 - value2

print(subtract(9, 5))

def multiply(value1, value2):
    return value1 * value2

print(multiply(2, 3))

def divide(value1, value2):
    return value1 / value2

print(divide(10, 5))
```

- [x] Final Task

The dictionary that will be passed is as below:
shopping_items = {"eggs": 5.85, "bread": 3.50, "ice": 0.30}

-Create a function called calculate_total_basket_cost(shoppingList):
- Calculate total cost of shopping items
- You must return the total amount only

```python
def shopping_list(shopping_items):
    return sum(shopping_items.values())

shopping_items = {"eggs" : 5.85, "bread" : 3.50, "ice" : 0.30,}
print(shopping_list(shopping_items))
```