# Code Snippets Dataset

This repository contains a dataset of code snippets in various programming languages. Each code snippet is accompanied by a description.

## Python

### Hello World Function

```python
def hello_world():
    print('Hello, world!')
```

A simple Python hello world function.

### Loop to Print Numbers

```python
for i in range(5):
    print(i)
```

Python loop to print numbers 0 to 4.

### Function to Add Two Numbers

```python
def add(a, b):
    return a + b
```

Python function to add two numbers.

### Calculate Square Root

```python
import math
print(math.sqrt(16))
```

Python code to calculate the square root of 16.

### Conditional Statement

```python
x = 10
if x > 5:
    print('x is greater than 5')
```

Python conditional statement.

### Loop through Colors

```python
colors = ['red', 'green', 'blue']
for color in colors:
    print(color)
```

Python loop to iterate through a list of colors.

### Recursive Factorial Function

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
```

Python recursive function to calculate factorial.

### Person Class

```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
```

Python class definition for a Person.

### Generate Random Number

```python
import random
print(random.randint(1, 100))
```

Python code to generate a random number between 1 and 100.

### List Comprehension

```python
numbers = [1, 2, 3, 4, 5]
squared_numbers = [x ** 2 for x in numbers]
print(squared_numbers)
```

Python list comprehension to square numbers.

### Query an API using GET

```python
import requests
url = 'https://api.example.com/data'
try:
    response = requests.get(url)
    if response.status_code == 200:
        data = response.json()
        print('Data received successfully:', data)
    else:
        print('Failed to retrieve data. Status code:', response.status_code)
except requests.RequestException as e:
    print("Error occurred: ", e)
```

Python request library to get response from an API

### Car Class and Inheritance

```python
class Car(self, make, model, year, color):

    def __init__(self):
        self.make = make
        self.model = model
        self.year = year
        self.color = color
        self.speed = 0

    def accelerate(self, mph):
        self.speed += mph

new_car = Car("Dodge", "Charger", 2009, "Red")
new_car.accelerate(20)

print(f"My car current speed: {new_car.speed}")
```

Python Car class with method to accelerate

```python
class ElectricCar(Car):

    def __init__(self, make, model, year, color, battery_capacity):
        super().__init__(make, model, year, color):
        self.battery_capacity = battery_capacity
        self.charge_level = 50

    def charge(self, charge_percentage):
        self.charge_level += charge_percentage
        self.charge_level = min(self.charge_level, 100)

new_electric_car = ElectricCar("Tesla", "Model 3", 2020, "Black", 100)
new_electric_car.charge(30)

print(f"My electric car current charge level: {new_electric_car.charge_level}")
```

Python Class to demonstrate inheritance


### Take Input from user

```python
name = input('Enter your name: ')
print(name)
```

Python code that takes input from user and prints it out


### Exception Handling

```python
try:
    first_number = int(input('Enter first number: '))
    second_number = int(input('Enter second number: '))
    result = first_number / second_number
except ZeroDivisionError:
    print('Error: Division by zero not allowed')
except Exception as e:
    print(f'Error: {e}')
else:
    print('No exceptions ocurred')
finally:
    print('Always executes')
```

Python code to demonstrate exception and error handling in python

<!-- Add more Python snippets here... -->

## JavaScript

### Basic Greeting Function

```javascript
function greet() {
    console.log('Hello, world!');
}
```

A basic JavaScript greeting function.

### Array Declaration and Logging

```javascript
let numbers = [1, 2, 3, 4, 5];
console.log(numbers);
```

JavaScript array declaration and logging.

<!-- Add more JavaScript snippets here... -->

## Java

### Java Program - Hello World

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println('Hello, world!');
    }
}
```

A Java program that prints 'Hello, world!'.

### Java Program - Sum of Two Numbers

```java
int x = 10;
int y = 20;
int sum = x + y;
System.out.println('Sum: ' + sum);
```

Java program to calculate and print the sum of two numbers.

<!-- Add more Java snippets here... -->

## Usage

You can use these code snippets for various purposes, including code language detection, educational materials, and code examples.

## License

This dataset is provided under the [License Name] license. See the [LICENSE](LICENSE) file for details.
