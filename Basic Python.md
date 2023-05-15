# Basic Python

This document is a short starter guide to developing in python. It is designed for people who are complete beginners in programming. This document will cover content from variables to classes, and at the end, the readers should have a strong foundation in understanding the python syntax and the skills required to do more with python. 

- Data Types in Python
    
    In Python, there are different types of data you can work with. Each type of data is used for different purposes. Here are some of the most common data types in Python:
    
    ### Integer
    
    An integer is a whole number. You can use integers to represent things like the number of apples in a basket or the number of days in a week. Here's an example of an integer:
    
    ```
    number_of_apples = 5
    
    ```
    
    ### Float
    
    A float is a number with a decimal point. You can use floats to represent things like the temperature outside or the price of a product. Here's an example of a float:
    
    ```
    temperature = 23.5
    
    ```
    
    ### String
    
    A string is a sequence of characters. You can use strings to represent things like names or addresses. Here's an example of a string:
    
    ```
    name = "Alice"
    
    ```
    
    ### Boolean
    
    A boolean is a value that can be either True or False. You can use booleans to represent whether a user is logged in. Here's an example of a boolean:
    
    ```
    is_logged_in = True
    
    ```
    
    That's it for the basic data types in Python. Using these data types, you can start building more complex programs in Python.
    
- Variables in Python
    
    A variable is a container that holds a value. Think of it like a box that can store something inside it. In Python, we use variables to store different types of data.
    
    Here's an example of how to create a variable:
    
    ```
    age = 8
    
    ```
    
    In this example, we created a variable called `age` and assigned it the value of `8`. Now we can use the variable `age` in our program to represent a person's age.
    
    You can also change the value of a variable later in your program. For example:
    
    ```
    age = 8
    age = age + 1
    
    ```
    
    In this example, we first created a variable called `age` and assigned it the value of `8`. Then, we added `1` to the value of `age` and stored the new value back into the `age` variable. Now the value of `age` is `9`.
    
    You can also use variables to store other types of data, such as strings:
    
    ```
    name = "Emily"
    
    ```
    
    In this example, we created a variable called `name` and assigned it the value of `"Emily"`. Now we can use the variable `name` in our program to represent the name of a person.
    
    Remember, variables are like boxes that can store different types of data, and you can change the value of a variable later in your program.
    
- Conditionals in Python
    
    In Python, you can use conditionals to make decisions in your program. Think of it like a game where you have to choose what to do next based on certain rules.
    
    Here's an example of a conditional:
    
    ```
    age = 8
    
    if age < 10:
        print("You are a kid!")
    else:
        print("You are not a kid anymore.")
    
    ```
    
    In this example, we use a conditional to check if the value of `age` is less than `10`. If it is, we print `"You are a kid!"`. If it's not, we print `"You are not a kid anymore."`.
    
    You can also use other comparison operators in conditionals, like `>` (greater than), `<=` (less than or equal to), `>=` (greater than or equal to), and `!=` (not equal to).
    
    Here's another example:
    
    ```
    temperature = 25
    
    if temperature > 30:
        print("It's too hot!")
    elif temperature > 20:
        print("It's just right.")
    else:
        print("It's too cold!")
    
    ```
    
    In this example, we use a conditional to check the value of `temperature`. If it's greater than `30`, we print `"It's too hot!"`. If it's between `20` and `30` (inclusive), we print `"It's just right."`. If it's less than `20`, we print `"It's too cold!"`.
    
    That's it for conditionals! They can help you make decisions in your program based on certain rules, like a game where you have to choose what to do next based on certain rules.
    
- Loops in Python
    
    In Python, loops are like a game where you have to do something over and over again. It's like playing a game of catch where you throw the ball back and forth.
    
    There are two types of loops in Python: `for` loops and `while` loops.
    
    ### For Loops
    
    A `for` loop is like playing a game of catch where you throw the ball a set number of times. You know exactly how many times you're going to throw the ball before you start.
    
    ```
    for i in range(5):
        print("Throwing ball", i+1)
    
    ```
    
    In this example, we're using a `for` loop to throw the ball `5` times. We use the `range()` function to create a sequence of numbers from `0` to `4` (because `range(5)` starts at `0` and ends at `4`). Then we use the variable `i` to keep track of which throw we're on. We print out a message that says we're throwing the ball and what the number of the throw is.
    
    ### While Loops
    
    A `while` loop is like playing a game of catch where you throw the ball back and forth until you reach a certain point. You don't know how many times you're going to throw the ball before you start.
    
    First example of while loops
    
    ```
    balls_caught = 0
    while balls_caught < 3:
        print("Throwing and catching the ball!")
        balls_caught += 1
    
    ```
    
    In this example, we're using a `while` loop to throw and catch the ball until we catch it `3` times. We start with `0` balls caught, and we keep throwing and catching the ball until we catch `3` balls. We print out a message that says we're throwing and catching the ball.
    
    That's it for loops! Loops can help you do things over and over again in your program, like playing a game of catch where you throw the ball back and forth.
    
- Functions in Python
    
    Functions are like little machines that do something for you. They take in some input, do some work, and then give you some output. Think of it like a vending machine that takes in your money, gives you some candy, and then spits out your change.
    
    Here's an example of a simple function:
    
    ```
    def add_numbers(a, b):
        result = a + b
        return result
    
    ```
    
    In this example, we're creating a function called `add_numbers` that takes in two parameters, `a` and `b`. Inside the function, we add `a` and `b` together and store the result in a variable called `result`. Then we use the `return` statement to give the result back to whoever called the function.
    
    You can call the function like this:
    
    ```
    result = add_numbers(3, 4)
    print(result)
    
    ```
    
    In this example, we're calling the `add_numbers` function and passing in `3` and `4` as the values for `a` and `b`. The function adds them together and returns `7`. We store the result in a variable called `result` and then print it out.
    
    Functions can be very powerful tools in programming. They can help you do complex tasks with just a few lines of code. But they can also be a bit tricky to understand at first. Just remember that functions are like little machines that do something for you, and they can take in input, do some work, and then give you output.
    
    - Parameters and Return Statements in Python
        
        Parameters are like the inputs to a function. They tell the function what it needs to do its work. Think of it like giving a recipe to a chef. The recipe tells the chef what ingredients to use and how to cook them.
        
        Here's an example of a function with two parameters:
        
        ```
        def greet(name, greeting):
            message = f"{greeting}, {name}!"
            return message
        
        ```
        
        In this example, we're creating a function called `greet` that takes in two parameters, `name` and `greeting`. Inside the function, we use those parameters to create a message that says hello to the person by name. Then we use the `return` statement to give the message back to whoever called the function.
        
        You can call the function like this:
        
        ```
        message = greet("Emily", "Hi")
        print(message)
        
        ```
        
        In this example, we're calling the `greet` function and passing in `"Emily"` as the value for `name` and `"Hi"` as the value for `greeting`. The function creates a message that says `"Hi, Emily!"` and returns it. We store the message in a variable called `message` and then print it out.
        
        Return statements are like the output of a function. They tell the function what it needs to give back to whoever called it. Think of it like a vending machine that gives you candy when you put in your money.
        
        Here's an example of a function with a return statement:
        
        ```
        def square(number):
            result = number * number
            return result
        
        ```
        
        In this example, we're creating a function called `square` that takes in one parameter, `number`. Inside the function, we multiply `number` by itself to get the square. Then we use the `return` statement to give the square back to whoever called the function.
        
        You can call the function like this:
        
        ```
        result = square(3)
        print(result)
        
        ```
        
        In this example, we're calling the `square` function and passing in `3` as the value for `number`. The function squares `3` to get `9` and returns it. We store the result in a variable called `result` and then print it out.
        
        That's it for parameters and return statements! They're like the inputs and outputs of a function, and they help the function do its work and give you back some result.
        
        - Programming Problems
            
            Here are some programming problems that will help you practice using functions:
            
            ### Problem 1: Add Two Numbers
            
            Write a function called `add` that takes in two numbers and adds them together. The function should return the sum of the two numbers.
            
            ### Problem 2: Find the Average
            
            Write a function called `average` that takes in a list of numbers and calculates the average of those numbers. The function should return the average.
            
            ### Problem 3: Factorial
            
            Write a function called `factorial` that takes in a number and calculates the factorial of that number. The factorial of a number is the product of all the numbers from 1 to that number. For example, the factorial of 5 is 5 * 4 * 3 * 2 * 1 = 120. The function should return the factorial.
            
            ### Problem 4: Fibonacci Sequence
            
            Write a function called `fibonacci` that takes in a number and calculates the nth number in the Fibonacci sequence. The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding numbers. For example, the first few numbers in the Fibonacci sequence are 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377, 610, 987, 1597, 2584, 4181, 6765, 10946, 17711, 28657, 46368, 75025, 121393, 196418, 317811, and so on. The function should return the nth number in the sequence.
            
            ### Solutions
            
            Here are the solutions to the programming problems:
            
            ### Problem 1: Add Two Numbers
            
            ```
            def add(a, b):
                return a + b
            
            ```
            
            ### Problem 2: Find the Average
            
            ```
            def average(numbers):
                total = sum(numbers)
                count = len(numbers)
                return total / count
            
            ```
            
            ### Problem 3: Fibonacci Sequence
            
            ```
            def fibonacci(n):
                if n == 0:
                    return 0
                elif n == 1:
                    return 1
                else:
                    return fibonacci(n-1) + fibonacci(n-2)
            
            ```
            
            That's it for the programming problems! These problems should help you practice using functions and get more comfortable with programming in Python.
            
- Classes in Python
    
    Classes are like templates that you can use to create objects. Think of it like building a robot. You have a blueprint that tells you how to build the robot, and then you build as many robots as you want based on that blueprint.
    
    Here's an example of a class:
    
    ```
    class Dog:
        def __init__(self, name, breed):
            self.name = name
            self.breed = breed
    
        def bark(self):
            print("Woof!")
    
    ```
    
    In this example, we're creating a class called `Dog`. The class has two attributes, `name` and `breed`, which are set when we create a new `Dog` object. The class also has a method called `bark` that prints out `"Woof!"`.
    
    You can create a new `Dog` object like this:
    
    ```
    my_dog = Dog("Fido", "Labrador")
    
    ```
    
    In this example, we're creating a new `Dog` object called `my_dog`. We pass in `"Fido"` as the value for `name` and `"Labrador"` as the value for `breed`. Now we can use the `my_dog` object to access its attributes and methods.
    
    ```
    print(my_dog.name)
    print(my_dog.breed)
    my_dog.bark()
    
    ```
    
    In this example, we're using the `my_dog` object to print out its `name` and `breed` attributes and to call its `bark` method.
    
    That's it for classes! They're like templates that you can use to create objects, and they help you organize your code into reusable pieces.
    
- Polymorphism in Python
    
    Polymorphism is like having different versions of the same thing. Think of it like a car that can be a sedan, a coupe, or a convertible. They're all cars, but they're different versions of the same thing.
    
    Here's an example of polymorphism:
    
    ```
    class Shape:
        def area(self):
            pass
    
    class Rectangle(Shape):
        def __init__(self, width, height):
            self.width = width
            self.height = height
    
        def area(self):
            return self.width * self.height
    
    class Circle(Shape):
        def __init__(self, radius):
            self.radius = radius
    
        def area(self):
            return 3.14 * (self.radius ** 2)
    
    ```
    
    In this example, we're creating a `Shape` class that has an `area` method. We're also creating two classes that inherit from `Shape`: `Rectangle` and `Circle`. Each of these classes has its own implementation of the `area` method that's specific to its shape.
    
    You can create a `Rectangle` object like this:
    
    ```
    my_rectangle = Rectangle(5, 10)
    print(my_rectangle.area())
    
    ```
    
    In this example, we're creating a new `Rectangle` object called `my_rectangle`. We pass in `5` as the value for `width` and `10` as the value for `height`. We then call the `area` method on the `my_rectangle` object to calculate its area.
    
    You can create a `Circle` object like this:
    
    ```
    my_circle = Circle(5)
    print(my_circle.area())
    
    ```
    
    In this example, we're creating a new `Circle` object called `my_circle`. We pass in `5` as the value for `radius`. We then call the `area` method on the `my_circle` object to calculate its area.
    
    That's it for polymorphism! It's like having different versions of the same thing, and it helps you write more flexible code that can work with different types of data.
    
- Abstraction in Python
    
    Abstraction is like hiding the details and showing only the important parts. Think of it like a TV remote. You don't need to know how the TV works, you just need to know how to use the remote to change the channels.
    
    Here's an example of abstraction:
    
    ```
    class Car:
        def __init__(self, make, model, year):
            self.make = make
            self.model = model
            self.year = year
    
        def start(self):
            pass
    
        def stop(self):
            pass
    
        def drive(self):
            pass
    
    class SportsCar(Car):
        def start(self):
            print("Starting the sports car.")
    
        def stop(self):
            print("Stopping the sports car.")
    
        def drive(self):
            print("Driving the sports car.")
    
    ```
    
    In this example, we're creating a `Car` class that has three attributes, `make`, `model`, and `year`. We're also creating three methods, `start`, `stop`, and `drive`. Each of these methods doesn't have any implementation yet, because we're going to hide the details and only show the important parts.
    
    We're also creating a `SportsCar` class that inherits from `Car`. This class has its own implementations of the `start`, `stop`, and `drive` methods that are specific to a sports car.
    
    You can create a `SportsCar` object like this:
    
    ```
    my_sports_car = SportsCar("Ferrari", "458 Italia", 2015)
    my_sports_car.start()
    my_sports_car.drive()
    my_sports_car.stop()
    
    ```
    
    In this example, we're creating a new `SportsCar` object called `my_sports_car`. We pass in `"Ferrari"` as the value for `make`, `"458 Italia"` as the value for `model`, and `2015` as the value for `year`. We then call the `start`, `drive`, and `stop` methods on the `my_sports_car` object to control the car.
    
    That's it for abstraction! It's like hiding the details and showing only the important parts, and it helps you write more readable and maintainable code.
    
- QUESTIONS
    1. Write a program that calculates the sum of two numbers.
    2. Write a program that calculates the area of a rectangle given its length and width.
    3. Write a program that calculates the factorial of a number.
    
    ```python
    def factorial(number):
      value = 1
      for i in range(number, 0, -1):
        value *= i
      print(value)
    
    factorial(100)
    ```
    
    1. Write a program that converts Celsius to Fahrenheit.
    2. Write a program that calculates the nth number in the Fibonacci sequence.
    3. Write a program that sorts a list of numbers in ascending order.
    4. Write a program that finds the largest number in a list.
    5. Write a program that checks if a given string is a palindrome.
    6. Write a program that finds all the prime numbers between 1 and 100.
    7. Write a program that simulates a game of tic-tac-toe.
    
    These challenges cover a range of programming concepts, from basic arithmetic to more advanced algorithms and data structures. They should be challenging but not overly difficult for a programmer with some experience in Python.
    
- HARDER QUESTIONS
    
    Here are 10 more programming challenges, each building on the concepts covered in the previous set of challenges:
    
    1. Write a program that calculates the area of a circle given its radius.
    2. Write a program that converts a decimal number to binary.
    3. Write a program that calculates the greatest common divisor of two numbers.
    4. Write a program that checks if a given number is a prime number.
    5. Write a program that simulates a game of Blackjack.
    6. Write a program that sorts a list of strings in alphabetical order.
    7. Write a program that encrypts and decrypts messages using the Caesar cipher.
    8. Write a program that parses a CSV file and calculates statistics based on the data.
    9. Write a program that generates a random password and checks its strength.
    10. Write a program that simulates a game of chess.
    
    These challenges involve more complex algorithms and data structures and may require more advanced programming concepts to solve. Good luck!
    
- Python Projects
    1. Calculator: Build a basic calculator that can perform simple arithmetic operations like addition, subtraction, multiplication, and division.
    2. Hangman Game: Build a classic hangman game that asks the user to guess a word by suggesting letters. You can create a list of words to choose from and keep track of the number of guesses the user has left.
    3. Tic Tac Toe: Build a two-player tic tac toe game where players take turns placing X's and O's on a board until one player wins or the game ends in a draw. 
    4. Weather App: Build an application that retrieves weather information for a user-specified location. You can use a weather API to get the data and display it to the user.
    5. Quiz Game: Build a quiz game that asks the user a series of questions and provides feedback on their answers. You can store the questions and answers in a database or a file.
    6. Password Generator: Build a password generator that generates random passwords based on user-specified criteria like length, character set, and strength.
    7. Web Scraper: Build a web scraper that extracts data from a website and saves it to a file or database. You can use libraries like Beautiful Soup and requests to perform the scraping.
    8. Chatbot: Build a simple chatbot that can answer user questions or perform simple tasks. You can use a natural language processing library like NLTK to analyze user input and generate responses.
    9. File Manager: Build a file manager that allows users to create, edit, delete, and move files and directories on their computer. You can use the os and shutil libraries to perform file operations.
    10. Image Resizer: Build an application that can resize and convert image files. You can use libraries like Pillow to perform image processing operations.
