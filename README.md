# LScript 1.0
## An under development interpreted programming language made with C++
The vision is to make it more user friendly to help learners to learn programming easily. You can see some examples of basic program in the /examples folder.
To create a LScript program you need to create file with .lsc extension. To use the interpreter of LScript open the LScript executable.

### To run a lsc file or LScript Program use the command bellow:
```
/path/to/LScript filename.lsc
```

### Current Features:
1. Variable
2. Array
3. Loop
4. Conditional Statement
5. And some built-in functions.

### Variable Declare 
```
Integer number1 = 10;
Floating number2 = 10.10;
String name = "Abthahi Ahmed Rifat";
Boolean isProgrammingLanguage = True;
```
### Array
```
Array(Integer) numbers = [10, 20, 30, 40, 50];
Array(String) names = ["Abtahi", "Ahmed", "Rifat"]
```
### Output function
```
print("Hello Bangladesh!");
```
### Input function
```
Integer num;
input(num);
print(num);
```

### Loop 
```
while (expression)
{	
	statements
}

for (condition; increament/decreament)
{
  statements
}
```
### Conditional Statement
```
if (condition)
{
  statements
}
else if (condition)
{
  statements
}
else
{
  statements
}
```
### To see memory addresses of stored variables
```
showVarTable()
```


