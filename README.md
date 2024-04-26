# DSA


### What is an Array?
An array is a special variable, which can hold more than one value at a time.

If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:

car1 = "Ford"
car2 = "Volvo"
car3 = "BMW"
However, what if you want to loop through the cars and find a specific one? And what if you had not 3 cars, but 300?

The solution is an array!

An array can hold many values under a single name, and you can access the values by referring to an index number.

![Screenshot 2024-04-26 164010](https://github.com/iamganeshsalunkhe/DSA/assets/143490640/bfa98266-6798-4f6e-b794-13e553e7e595)


### Strings

Strings in python are surrounded by either single quotation marks, or double quotation marks.

'hello' is the same as "hello".

You can display a string literal with the print() function:

```
print("Hello")
print('Hello')
```

#### Quotes Inside Quotes


You can use quotes inside a string, as long as they don't match the quotes surrounding the string:

```
print("It's alright")
print("He is called 'Johnny'")
print('He is called "Johnny"')
```
#### Assign String to a Variable

Assigning a string to a variable is done with the variable name followed by an equal sign and the string:
```
a = "Hello"
print(a)
```

#### Multiline Strings

You can assign a multiline string to a variable by using three quotes:

```
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```


#### Strings are Arrays
Like many other popular programming languages, strings in Python are arrays of bytes representing unicode characters.

However, Python does not have a character data type, a single character is simply a string with a length of 1.

Square brackets can be used to access elements of the string.



#### Looping Through a String

Since strings are arrays, we can loop through the characters in a string, with a for loop.

Loop through the letters in the word "banana":
```
for x in "banana":
  print(x)
```


#### String Length

To get the length of a string, use the len() function.


The len() function returns the length of a string:
```
a = "Hello, World!"
print(len(a))
```

#### Check String
To check if a certain phrase or character is present in a string, we can use the keyword in.


Check if "free" is present in the following text:
```
txt = "The best things in life are free!"
print("free" in txt)
```

