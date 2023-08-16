# Python Notes 

- For a comment placed on one line use #, more than one line use """ """ or ''' '''.

- We learn to data type of variable with type( ) function.

- String variables can be shown:

  ​	x = 'Alice' or x = "Alice"

- Variable names is case-sensitive. a and A are not the same.

- Variable names rules

   * must start with a letter or underscore character.
   * cannot start with a number.
   * can only contain alpha-numeric characters and underscores.
   * case-sensitive.
   * cannot be any of the python keywords.

- Camel Case : myVariableName, Pascal Case: MyVariableName, Snake Case: my_variable_name

- Since Python does not have the concept of {}, indentation becomes crucial, and 4 spaces or 1 tab is used. For example:

  ​	if x > y:
  ​    	print("hello")

- x = "awesome"

  def myfunc():
      x = "fantastic"  # When we define a variable inside a function, it's only valid within that function and not outside it
      print("Python is " + x)

  myfunc()
  print("Python is " + x)

- global( ) function exp:

  x = "awesome"

  def myfunc():
      global x   # When a variable is defined as global, its value becomes globally accepted, whether inside or outside the function.
      x = "fantastic"

  myfunc()
  print("Python is " + x)

- s = b'ankara' ---> Converts the variable to bytes.

- The expression "10+20" is death code, don't impact anything in program.

- Compilers perform better code optimization than interpreters.

- print(r"kale\n")  r is regular. 

  ​	>>> kale\n
  
__Data Types__

  - Text Type: __str__ , x = "Hello"
  - Numeric Types: __int__, __float__, __complex__, x = 20(int), x = 20.5(float), x = 1j(complex)
  - Sequence Types: __list__, __tuple__, __range__, x = ["apple", "banana", "cherry"] list, x = ("apple",       "banana", "cherry") tuple, x = range(6) 
  - Mapping Types: __dict__,  x = {"name" : "John", "age" : 36}
  - Set Types: __set__, __frozenset__, x = {"apple", "banana", "cherry"} set, x = frozenset({"apple",           "banana", "cherry"}) frozen set
  - Boolean Type: __bool__,  x = True
  - Binary Types: __bytes__, __bytearray__, __memoryview__, x = b"Hello" bytes, x = bytearray(5), x =            memoryview(bytes(5))
  - None Type: __NoneType__, x = None
  
- Tuples are similar to lists but with one key difference: once a tuple is created, its elements cannot be modified, added, or removed. Each element within a tuple is referred to as an "__item__".
  
- Range type usually use 3 way:

 1. One Parameter:
    ​	for i in range(5):
       	print(i)

 2. Two Parameter:
    ​	for i in range(2, 8):  #2 is __start__ and 8 is __stop__
    ​		print(i)

3. Three Parameters:
       for i in range(1, 10, 2):  #1 is __start__, 10 is __stop__, 2 is __step__
         print(i)







