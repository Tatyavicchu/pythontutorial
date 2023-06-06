# Input and Output
```c
a=datatype(input("enter the number")) //if data type is not mentioned the the data s automatically taken as string.
print (a)
```

# Variable types
`int -> integer variable`

`float-> decimal values`

`complex-> includes imaginary numbers`//2+4j,28973-8923j

`strings-> include many characters as an string` // no varible as char.

`boolean -> True and False`// these are case sensitive,'T' and 'F' should be capital.

### python basic code:
 ```c
a=input("first name")
b= input("last name")
age=int(input("enter the age"))  // typecasting the age to int from default strings.
print (a)
print(age)
print(b)
 ```
 
 
 # Arithematic function in python
 
 `1-> Addition:` `The addition operator (+) is used to add two numbers together.`
 ```c
 result = 5 + 3
print(result)  # Output: 8 //strings can be added like this too. eg.result="hello"+"world".   output= helloworld

 ```
 
 `2->Subtraction:` `The subtraction operator (-) is used to subtract one number from another.`
 ```c
 result = 9 - 4
print(result)  # Output: 5

 ```
 
 `3-> Division:` `The division operator (/) is used to divide one number by another. The result is a float.`
 ```c
 result = 10 / 3
print(result)  # Output: 3.3333333333333335 //type cast for an integer answer.
 ```
 
 `4->Integer Division:` `The double-slash operator (//) performs integer division, discarding the remainder.`
 ```c
 result = 10 // 4
print(result)  # Output: 2
 ```
 
 `5->Modulo:` `The modulo operator (%) returns the remainder of the division.`
 ```c
 result = 10 % 3
print(result)  # Output: 1
 ```
 `6->Exponentiation:` `The double asterisk operator (**) is used to raise a number to a power.`
 ```c
 result = 2 ** 3
print(result)  # Output: 8
 ```
 
 # Precedence of operators
| Operator                        | Description                             |
| ------------------------------- | --------------------------------------- |
| `()`                            | Parentheses (grouping)                  |
| `f(args...)`, `x[index]`, `x[index:index]` | Function calls, indexing, slicing    |
| `**`                            | Exponentiation                          |
| `~`, `+`, `-`                    | Bitwise NOT, unary plus and minus        |
| `*`, `/`, `//`, `%`              | Multiplication, division, floor division, modulo |
| `+`, `-`                         | Addition, subtraction                   |
| `<<`, `>>`                       | Bitwise left shift, bitwise right shift |
| `&`                             | Bitwise AND                             |
| `^`                             | Bitwise XOR                             |
| `|`                             | Bitwise OR                              |
| `in`, `not in`, `is`, `is not`, `<`, `<=`, `>`, `>=`, `!=`, `==` | Comparison operators         |
| `not`                            | Logical NOT                             |
| `and`                            | Logical AND                             |
| `or`                             | Logical OR                              |
| `lambda`                         | Lambda expression                       |
| `if...else`                      | Conditional expression                   |
| `:=`                            | Assignment expression (Python 3.8+)      |

 
 
 # String functions
 
 `1-> len():` `Returns the length of a string.`
 ```c
 text = "Hello, world!"
length = len(text)
print(length)  # Output: 13
 ```
 
 `2-> lower():` `Converts a string to lowercase.`  //does not change the original string but gives us a new string.
 ```c
 text = "Hello, World!"
lower_text = text.lower()
print(lower_text)  # Output: hello, world!
 ```
 `3-> upper():` `Converts a string to uppercase.` //does not change the original string but gives us a new string.
 ```c
 text = "Hello, World!"
upper_text = text.upper()
print(upper_text)  # Output: HELLO, WORLD!
 ```
 `4-> strip():` `Removes leading and trailing whitespace from a string.`
 ```c
 text = "   Hello, World!   "
stripped_text = text.strip()
print(stripped_text)  # Output: Hello, World!
 ```
 `5-> split():` `Splits a string into a list of substrings based on a delimiter.`
 ```c
 text = "Hello, World!"
words = text.split(",")
print(words)  # Output: ['Hello', ' World!']
 ```
 
 `6-> join():`  `Joins a list of strings into a single string using a specified delimiter.`
 ```c
 words = ['Hello', 'World']
text = ', '.join(words)
print(text)  # Output: Hello, World
 ```
 `7-> replace():` `Replaces all occurrences of a substring with another substring.`
 ```c
 text = "Hello, World!"
new_text = text.replace("World", "Python")
print(new_text)  # Output: Hello, Python!
 ```
 `8-> find():` `Returns the index of the first occurrence of a substring in a string (-1 if not found)`
 ```c
text = "Hello, World!"
index = text.find("World")
print(index)  # Output: 7
 ```
 `9-> boolean :` `It prints true or false in any condition.`
 ```c
 name ="hello world"
 print('h' in name)  //output: True
 ```
 
 # Conditional operators in python
 
 
| Operator   | Meaning                                     | Example                          |
|------------|---------------------------------------------|----------------------------------|
| ==         | Equal to                                    | `x == y` (True if x equals y)    |
| !=         | Not equal to                                | `x != y` (True if x does not equal y) |
| >          | Greater than                                | `x > y` (True if x is greater than y) |
| <          | Less than                                   | `x < y` (True if x is less than y) |
| >=         | Greater than or equal to                    | `x >= y` (True if x is greater than or equal to y) |
| <=         | Less than or equal to                       | `x <= y` (True if x is less than or equal to y) |
| is         | Object identity                             | `x is y` (True if x and y refer to the same object) |
| is not     | Negated object identity                     | `x is not y` (True if x and y do not refer to the same object) |
| in         | Membership (checks if value is in a sequence) | `x in y` (True if x is found in y) |
| not in     | Negated membership                          | `x not in y` (True if x is not found in y) |


# if/else conditions in python

```c
if age>=18:
  print("can vote") // always use indentation in loops and conditions.
elif (age<18 and age>3)
   print("not valid age")
else :
    print("thankyou")
```

# Range

 -> this shows the limit of the numbers.
 ```c
 range(5)  // output: 1,2,3,4
 ```
 
# LOOPS
 
 -> loops are used to do a task mutiple times.
  
  `Syntax`
  
  ### while loop
  ```c
     while i<=5:
      print(i)
      i+=1
   ``` 
   
   ### for loop
  ```c
   for i in range(limit):
       print(i)
       i=+1
   ```
 
 
 # LIST -> It is a collection of items of diffrent data type.
 ```c
  mylist=[134,423,232,545]  // with list square brackets are used.
  print(mylist[1])  // Output: 423
  print(mylist[0:3] // Output: 134,423,232
 ```
 -> In python we can use negetive indexing too.  // -3 = 545,  -2 = 232.
 -> Be wary of indentation in python cause it can cause erors.
 -> List is mutable unlike tuples ahead.


## function used in List
    
    In Python, there are several built-in functions that are commonly used with lists. Here are some of the most frequently used functions for working with lists:

1. `len()`: Returns the number of elements in a list.
   ```python
   numbers = [1, 2, 3, 4, 5]
   length = len(numbers)
   print(length)  # Output: 5
   ```

2. `append()`: Adds an element to the end of a list.
   ```python
   fruits = ['apple', 'banana', 'cherry']
   fruits.append('orange')
   print(fruits)  # Output: ['apple', 'banana', 'cherry', 'orange']
   ```

3. `extend()`: Adds all the elements from another list to the end of the current list.
   ```python
   numbers = [1, 2, 3]
   numbers.extend([4, 5, 6])
   print(numbers)  # Output: [1, 2, 3, 4, 5, 6]
   ```

4. `insert()`: Inserts an element at a specific index in the list.
   ```python
   names = ['Alice', 'Bob', 'Eve']
   names.insert(1, 'Charlie')
   print(names)  # Output: ['Alice', 'Charlie', 'Bob', 'Eve']
   ```

5. `remove()`: Removes the first occurrence of a specified element from the list.
   ```python
   colors = ['red', 'green', 'blue', 'green']
   colors.remove('green')
   print(colors)  # Output: ['red', 'blue', 'green']
   ```

6. `pop()`: Removes and returns the element at a specific index in the list. If no index is specified, it removes and returns the last element.
   ```python
   numbers = [1, 2, 3, 4, 5]
   popped_element = numbers.pop(2)
   print(popped_element)  # Output: 3
   print(numbers)  # Output: [1, 2, 4, 5]
   ```

7. `index()`: Returns the index of the first occurrence of a specified element in the list.
   ```python
   fruits = ['apple', 'banana', 'cherry']
   index = fruits.index('banana')
   print(index)  # Output: 1
   ```

8. `count()`: Returns the number of occurrences of a specified element in the list.
   ```python
   numbers = [1, 2, 2, 3, 2, 4, 5]
   count = numbers.count(2)
   print(count)  # Output: 3
   ```

9. `sort()`: Sorts the elements in the list in ascending order.
   ```python
   numbers = [5, 2, 4, 1, 3]
   numbers.sort()
   print(numbers)  # Output: [1, 2, 3, 4, 5]
   ```

10. `reverse()`: Reverses the order of the elements in the list.
    ```python
    letters = ['a', 'b', 'c', 'd']
    letters.reverse()
    print(letters)  # Output: ['d', 'c', 'b', 'a']
    ```

 11. `del statement`: You can use the del statement to remove an element or a slice of elements from a list by specifying the index or slice you want to delete.

  ```python
  numbers = [1, 2, 3, 4, 5]
  del numbers[2]  # Remove the element at index 2
  print(numbers)  # Output: [1, 2, 4, 5]
 
  fruits = ['apple', 'banana', 'cherry', 'orange']
  del fruits[1:3]  # Remove the elements from index 1 to 2 (excluding index 3)
  print(fruits)  # Output: ['apple', 'orange']
  ```
 # Break and Continue in python
 
1. `break`: The `break` statement is used to exit the loop prematurely. When encountered within a loop, it immediately terminates the loop and continues execution with     the next statement after the loop.
   ```python
    numbers = [1, 2, 3, 4, 5]
    for num in numbers:
       if num == 3:
           break  # Exit the loop when num equals 3
       print(num)
   # Output: 1 2
   ```

   In the example above, when the value of `num` is 3, the `break` statement is executed, causing the loop to terminate. As a result, only the numbers 1 and 2 are printed.


2. `continue`: The `continue` statement is used to skip the remaining code within a loop iteration and move to the next iteration. It allows you to bypass certain  iterations without terminating the entire loop.
   ```python
   numbers = [1, 2, 3, 4, 5]
   for num in numbers:
       if num == 3:
           continue  # Skip the iteration when num equals 3
       print(num)
   # Output: 1 2 4 5
   ```
  In this example, when the value of `num` is 3, the `continue` statement is executed. This causes the loop to skip the remaining code within that iteration and move    to the next iteration. As a result, the number 3 is not printed.
  
  
# Tuple

In Python, a tuple is an ordered, immutable collection of elements enclosed in parentheses `()`. Tuples are similar to lists, but the key difference is that tuples are immutable, meaning their elements cannot be modified once they are defined. Here's an example of a tuple:

```python
my_tuple = (1, 2, 3, 'apple', 'banana')
```

In this example, `my_tuple` contains five elements: the integers 1, 2, and 3, and the strings 'apple' and 'banana'.

Tuples support various operations and methods, including indexing, slicing, and some built-in functions. Here are a few examples:

### Accessing Elements:
```python
my_tuple = (1, 2, 3, 'apple', 'banana')
print(my_tuple[0])       # Output: 1 (accessing element at index 0)
print(my_tuple[3])       # Output: 'apple' (accessing element at index 3)
```

### Slicing:
```python
my_tuple = (1, 2, 3, 'apple', 'banana')
print(my_tuple[1:4])     # Output: (2, 3, 'apple') (slicing elements from index 1 to 3)
print(my_tuple[:3])      # Output: (1, 2, 3) (slicing elements from start to index 2)
print(my_tuple[2:])      # Output: (3, 'apple', 'banana') (slicing elements from index 2 to end)
```

### Length of a Tuple:
```python
my_tuple = (1, 2, 3, 'apple', 'banana')
print(len(my_tuple))     # Output: 5 (length of the tuple)
```

### Counting Items
```python
my_tuple = (1, 2, 3,3,3,3 'apple', 'banana')
print(mytuple.count(3)) # output :4(frequency)
```

### Iterating Over a Tuple:
```python
my_tuple = (1, 2, 3, 'apple', 'banana')
for item in my_tuple:
    print(item)
# Output:
# 1
# 2
# 3
# 'apple'
# 'banana'
```

Note that due to their immutability, tuples cannot be modified by adding, removing, or changing elements after they are created. However, you can create a new tuple by concatenating or slicing existing tuples.

Tuples are commonly used when you want to store a collection of related values that should not be modified, such as coordinates, settings, or multiple return values from a function.

## Conversion of tuples into list

To convert a tuple into a list in Python, you can use the `list()` function. The `list()` function takes an iterable as an argument and returns a new list containing the elements of the iterable. Here's an example of converting a tuple into a list:

```python
my_tuple = (1, 2, 3, 'apple', 'banana')
my_list = list(my_tuple)
print(my_list)
# Output: [1, 2, 3, 'apple', 'banana']
```
 -> list can be converted into tuples with same method just use tuple instead of list.
 
# SET in python

In Python, a set is an unordered collection of unique elements enclosed in curly braces `{}` or created using the `set()` constructor. Sets are similar to lists or tuples, but they do not allow duplicate values and their elements are not ordered. Here's an example of a set:

```python
my_set = {1, 2, 3, 'apple', 'banana'}
```

In this example, `my_set` contains five elements: the integers 1, 2, and 3, and the strings 'apple' and 'banana'.

Sets support various operations and methods for set operations like union, intersection, and difference. Here are a few examples:

Adding Elements:
```python
my_set = {1, 2, 3}
my_set.add(4)   # Add a single element
my_set.update([5, 6, 7])   # Add multiple elements
print(my_set)   # Output: {1, 2, 3, 4, 5, 6, 7}
```

Removing Elements:
```python
my_set = {1, 2, 3, 4, 5}
my_set.remove(3)   # Remove a specific element
my_set.discard(6)  # Remove an element (if present)
my_set.pop()       # Remove an arbitrary element
print(my_set)      # Output: {1, 2, 4, 5}
```

Set Operations:
```python
set1 = {1, 2, 3}
set2 = {3, 4, 5}
union = set1.union(set2)        # Union of two sets
intersection = set1.intersection(set2)  # Intersection of two sets
difference = set1.difference(set2)  # Difference between two sets
print(union)        # Output: {1, 2, 3, 4, 5}
print(intersection) # Output: {3}
print(difference)   # Output: {1, 2}
```

Iterating Over a Set:
```python
my_set = {1, 2, 3, 'apple', 'banana'}
for item in my_set:
    print(item)
# Output:
# 1
# 2
# 3
# 'apple'
# 'banana'
```

# Set vs Tuple vs List



|          | Sets                  | Tuples                | Lists                 |
|----------|-----------------------|-----------------------|-----------------------|
| Syntax   | `{}` or `set()`       | `()` or without        | `[]` or `list()`       |
| Ordering | Unordered             | Ordered               | Ordered               |
| Duplicates | Not allowed         | Allowed               | Allowed               |
| Mutability | Mutable             | Immutable             | Mutable               |
| Indexing  | Not supported        | Supported             | Supported             |
| Slicing   | Not supported        | Supported             | Supported             |
| Use Cases | Finding unique elements, testing membership, eliminating duplicates | Representing fixed collections, dictionary keys | General-purpose storage and manipulation of data |








