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
  mylist=[]  // with list square brackets are used
  
 ```
 
 
 
 
