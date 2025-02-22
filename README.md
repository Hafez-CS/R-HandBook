R-HandBook
===============================
![Monty Python](https://cdn.dribbble.com/users/330915/screenshots/3587000/10_coding_dribbble.gif)

## Introduction
**Welcome to my R handbook!
This handbook is a complete collection of R tips and topics in a "learning by example" approach and I hope it is useful.**

### What is R?
**R is a programming language for statistical computing and data visualization. It has been adopted in the fields of data mining, bioinformatics and data analysis.
The core R language is augmented by a large number of extension packages, containing reusable code, documentation, and sample data.
R software is open-source and free software. It is licensed by the GNU Project and available under the GNU General Public License. It is written primarily in C, Fortran, and R itself. Precompiled executables are provided for various operating systems.
As an interpreted language, R has a native command line interface. Moreover, multiple third-party graphical user interfaces are available, such as RStudio—an integrated development environment—and Jupyter—a notebook interface. **

### What can R do?
**R can handle data analysis, statistical modeling, machine learning, data visualization, and reporting. It is widely used for tasks like regression, classification, clustering, time series analysis, and working with large datasets.**

### Why R?
**R is great for statistical analysis, data visualization, and machine learning. It has extensive libraries, strong community support, and is widely used in academia and industry for data science.**

### good to know!
**R : [https://www.python.org/](https://www.r-project.org/)**

**RStudio : [https://pypi.org/](https://posit.co/download/rstudio-desktop/)**

**Learn more about python : [https://www.w3schools.com/python/default.asp](https://www.w3schools.com/r/default.asp)**

## Contents
**&nbsp;&nbsp;&nbsp;** **1. R-Syntax :** **&nbsp;**  **[`R-Syntax`](#r-syntax)** 

**&nbsp;&nbsp;&nbsp;** **2. R-Comments :** **&nbsp;**  **[`R-Comments`](#r-comments)** 

**&nbsp;&nbsp;&nbsp;** **3. R-Variables :** **&nbsp;**  **[`R-Variables`](#r-variables)** 

**&nbsp;&nbsp;&nbsp;** **4. R-Data-Types :** **&nbsp;**  **[`R-Data-Types`](#r-data-types)** 

**&nbsp;&nbsp;&nbsp;** **5. What-is-Data-Type :** **&nbsp;**  **[`What-is-Data-Type`](#what-is-data-type)** 

**&nbsp;&nbsp;&nbsp;** **6. type-conversion :** **&nbsp;**  **[`Type-Conversion`](#type-conversion)** 

**&nbsp;&nbsp;&nbsp;** **7. R-Input :** **&nbsp;**  **[`R-Input`](#r-input)** 

**&nbsp;&nbsp;&nbsp;** **8. r-math :** **&nbsp;**  **[`R-Math`](#r-math)** 

**&nbsp;&nbsp;&nbsp;** **9. R-Strings :** **&nbsp;**  **[`R-Strings`](#r-strings)** 

**&nbsp;&nbsp;&nbsp;** **10. R-Booleans-Logical-Values :** **&nbsp;**  **[`R-Booleans-Logical-Values`](#r-booleans-logical-values)** 

**&nbsp;&nbsp;&nbsp;** **11. R-Operators :** **&nbsp;**  **[`R-Operators`](#r-operators)** 

**&nbsp;&nbsp;&nbsp;** **12. R-If-Else :** **&nbsp;**  **[`R-If-Else`](#r-if-else)** 

**&nbsp;&nbsp;&nbsp;** **13. R-AND-OR-Operators :** **&nbsp;**  **[`R-AND-OR-Operators`](#r-and-or-operators)** 

**&nbsp;&nbsp;&nbsp;** **14. R-While-Loop :** **&nbsp;**  **[`R-While-Loop`](#r-while-loop)** 

**&nbsp;&nbsp;&nbsp;** **15. R-For-Loop :** **&nbsp;**  **[`R-For-Loop`](#r-for-loop)** 

**&nbsp;&nbsp;&nbsp;** **16. R-Functions :** **&nbsp;**  **[`R-Functions`](#r-functions)** 

**&nbsp;&nbsp;&nbsp;** **17. R-Vectors :** **&nbsp;**  **[`R-Vectors`](#r-vectors)** 

**&nbsp;&nbsp;&nbsp;** **18. R-Lists :** **&nbsp;**  **[`R-Lists`](#r-lists)** 

**&nbsp;&nbsp;&nbsp;** **19. R-Matrices :** **&nbsp;**  **[`R-Matrices`](#r-matrices)** 

**&nbsp;&nbsp;&nbsp;** **20. R-Arrays :** **&nbsp;**  **[`R-Arrays`](#r-arrays)** 

**&nbsp;&nbsp;&nbsp;** **21. R-Data-Frames :** **&nbsp;**  **[`R-Data-Frames`](#r-data-frames)** 

**&nbsp;&nbsp;&nbsp;** **22. R-Factors :** **&nbsp;**  **[`R-Factors`](#r-factors)** 

**&nbsp;&nbsp;&nbsp;** **23. R-Plotting :** **&nbsp;**  **[`R-Plotting`](#r-plotting)** 

**&nbsp;&nbsp;&nbsp;** **24. R-Line :** **&nbsp;**  **[`R-Line`](#r-line)** 

**&nbsp;&nbsp;&nbsp;** **25. R-Scatter-Plot :** **&nbsp;**  **[`R-Scatter-Plot`](#r-scatter-plot)** 

**&nbsp;&nbsp;&nbsp;** **26. R-Pie-Charts :** **&nbsp;**  **[`R-Pie-Charts`](#r-pie-charts)** 

**&nbsp;&nbsp;&nbsp;** **27. R-Bar-Charts :** **&nbsp;**  **[`R-Bar-Charts`](#r-bar-charts)** 

**&nbsp;&nbsp;&nbsp;** **28. R-Statistics :** **&nbsp;**  **[`R-Statistics`](#r-statistics)** 

**&nbsp;&nbsp;&nbsp;** **29. R-Percentiles :** **&nbsp;**  **[`R-Percentiles`](#r-percentiles)** 

**&nbsp;&nbsp;&nbsp;** **30. Library :** **&nbsp;**  **[`Library`](#library)** 

**&nbsp;&nbsp;&nbsp;** **31. Stringr-Library :** **&nbsp;**  **[`Stringr-Library`](#stringr-library)** 

**&nbsp;&nbsp;&nbsp;** **32. MASS-Library :** **&nbsp;**  **[`MASS-Library`](#mass-library)** 

**&nbsp;&nbsp;&nbsp;** **33. pracma-Library :** **&nbsp;**  **[`pracma-Library`](#pracma-library)**

**&nbsp;&nbsp;&nbsp;** **34. R-table :** **&nbsp;**  **[`R-table`](#r-table)**

**&nbsp;&nbsp;&nbsp;** **35. purrr-Library :** **&nbsp;**  **[`purrr-Library`](#purrr-library)**

**&nbsp;&nbsp;&nbsp;** **36. Read-file :** **&nbsp;**  **[`Read-file`](#read-file)**

**&nbsp;&nbsp;&nbsp;** **37. write-File :** **&nbsp;**  **[`Write-File`](#write-file)**

R-Syntax
---
```R
"hello world"


# output : "hello world"
```

```R
1


# output : 1
```

```R
5 + 5


# output : 10
```
### print

```R
print("Hello World!")


# output : "Hello World!"
```

```R
for (x in 1:10) {
  print(x)} 


# output :  1
2
3
4
5
6
7
8
9
10
```
**sprintf**
```R
a = 12.3
sprintf("The value of a is: %f", a)


# output : "The value of a is: 12.300000"
```
**paste**

```R
paste("Hello", "World")


# output : "Hello World"
```

```R
text <- "awesome"
paste("R is", text)


# output : "R is awesome"
```
```R
paste("Hello", "World", sep = "-")


# output : "Hello-World"
```

```R
words <- c("apple", "banana", "cherry")
paste(words, collapse = ", ")


# output : "apple, banana, cherry"
```

**past0**

```R
paste0("Hello", "World")


# output : "HelloWorld"
```

**cbind**

```R
a <- c(1, 2, 3)
b <- c(4, 5, 6)
cbind(a, b)


# output : 
     a b
[1,] 1 4
[2,] 2 5
[3,] 3 6
```

```R
x <- c(10, 20, 30)
y <- c(40, 50, 60)
z <- c(70, 80, 90)
result <- cbind(x, y, z)
print(result)


# output : 
     x  y  z
[1,] 10 40 70
[2,] 20 50 80
[3,] 30 60 90
```

```R
mat1 <- matrix(1:6, nrow = 3, ncol = 2)
mat2 <- matrix(7:12, nrow = 3, ncol = 2)
cbind(mat1, mat2)


# output : 
     [,1] [,2] [,3] [,4]
[1,]    1    4    7   10
[2,]    2    5    8   11
[3,]    3    6    9   12
```

```R
gender <- factor(c("Male", "Female", "Male"))
age <- c(25, 30, 22)
result <- cbind(gender, age)
print(result)


# output : 
     gender age 
[1,] "Male"   "25"  
[2,] "Female" "30"  
[3,] "Male"   "22"
```


R-Comments
---
```R
"Hello World!" # This is a comment 


# output : "Hello World!"
```

R-Variables
---
```R
name <- "John"
age <- 40
name
age


# output : "John"
# output : 40
```

```R
name <- "John Doe"
print(name)


# output : "John Doe"
```

### R Multiple Variables

```R
var1 <- var2 <- var3 <- "Orange"
var1
var2
var3 


# output : "Orange"
# output : "Orange"
# output : "Orange"
```

### R Variable Names (Identifiers)
Legal variable names:
```R 
myvar <- "John"
my_var <- "John"
myVar <- "John"
MYVAR <- "John"
myvar2 <- "John"
.myvar <- "John"
```
Illegal variable names:
```R 
2myvar <- "John"
my-var <- "John"
my var <- "John"
_my_var <- "John"
my_v@ar <- "John"
TRUE <- "John"
```

R-Data-Types
---
```R
my_var <- 30                # my_var is type of numeric
my_var <- "Sally"           # my_var is now of type character (aka string) 
```

**Basic Data Types :**

numeric

```R
x <- 10.5
class(x)


# output : "numeric"
```
```R
a <- NaN
class(a)


# output : "numeric"
```

integer

```R
x <- 1000L
class(x)


# output : "integer"
```
complex
```R 
x <- 9i + 3
class(x)


# output :  "complex"
```
character/string
```R 
x <- "R is exciting"
class(x)


# output :  "character"
```
logical/boolean
```R 
x <- TRUE
class(x) 


# output :  "logical"
```
**Logical Data Types**
```R 
a <- 2
is.numeric(a)


# output :  TRUE
```
```R 
a <- 2
is.integer(a)


# output :  FALSE
```
```R 
a <- 2
is.double(a)


# output :  TRUE
```
```R 
a <- 2
is.character(b)


# output :  TRUE
```

What-is-Data-Type
---
**mode()**
```R 
a <- 3.14
b <- "Hello"
c <- TRUE
d <- list(1, 2, 3)
mode(a)
mode(b)
mode(c)
mode(d)


# output :  "numeric"
# output :  "character"
# output :  "logical"
# output :  "list"
```
**class()**
```R 
a <- 3.14
b <- "Hello"
c <- TRUE
d <- list(1, 2, 3)
class(a)
class(b)
class(c)
class(d)


# output :  "numeric"
# output :  "character"
# output :  "logical"
# output :  "list"
```
**typeof()**

```R 
a <- 3.14
b <- "Hello"
c <- TRUE
d <- list(1, 2, 3)
typeof(a)
typeof(b)
typeof(c)
typeof(d)


# output :  "double"
# output :  "character"
# output :  "logical"
# output :  "list"
```

Type-Conversion
---
You can convert from one type to another with the following functions:

* **as.numeric()**
* **as.integer()**
* **as.complex()**
```R 
x <- 1L          # integer
y <- 2           # numeric
a <- as.numeric(x)            # convert from integer to numeric:
b <- as.integer(y)            # convert from numeric to integer:

print(x)
print(y)

# output :  1
# output :  2

class(a)
class(b) 

# output :  "numeric"
# output :  "integer"
```
```R 
a <- 10
b <- as.double(a)
print(b)


# output : 10
```
```R 
b <- "gggggg"
b <- as.character(b)
print(b)


# output :  "gggggg"
```

R-Input
---
**readline()**
```R 
f <- readline()
print(f)


# outpu : "anything you write"
```
**scan()**

```R 
f <- scan()
1: 10 20 30 40
print(f)


# output : 10 20 30
```
```R 
f <- scan(what = character())
1: spsps spsps spsps
print(f)


# output : "spsps" "spsps" "spsps"
```

R-Math
---
`x + y`  Addition

`x - y` Subtraction

`x * y` Multiplication

`x / y`  Division

`x ^ y`  Exponent

`x %% y` Modulus (Remainder from division)

`x %/% y` Integer Division
```R 
10 + 5


# output : 15
```
```R 
10 - 5


# output : 5
```
```R 
max(5, 10, 15)
min(5, 10, 15) 


# output : 15
# output : 5
```
```R 
sqrt(16)


# output : 4
```
```R 
abs(-4.7) 


# output : 4.7
```
```R 
ceiling(1.4)          # number upwards to its nearest integer


# output : 2
```
```R 
floor(1.4)           # ounds a number downwards to its nearest integer


# output : 1
```
```R 
pi()


# output : 3.141593
```
```R 
x <- 2
exp(x)


# output : 7.389056     # formoul is  exp(x) = e^x
```
```R 
x <- 10
log(x)
log(x, base = 10)


# output : 2.302585    # formoul is  log(x) = ln(x)
# output : 1
```
```R 
a <- 10
sin(a)
cos(a)
tan(a)


# output : -0.8390715
# output : -0.5440211
# output : 0.6483608
```
```R 
#Inverse trigonometry
asin(0.5)   
acos(0.5)
atan(1) 


# output : 0.5235988
# output : 1.047197
# output : 0.7853982
```
```R 
x <- c(1, 3, 6, 10)
diff(x)


# output : 2 3 4
```
3 - 1 = 2

6 - 3 = 3

10 - 6 = 4

```R 
x <- c(1, 3, 6, 10)
cumsum(x)


# output : 1  4 10 20
```
1

1 + 3 = 4

4 + 6 = 10

10 + 10 = 20
```R 
x <- c(1, 3, 6, 10)
prod(x)


# output : 180
```
1 * 3 * 6 * 10 = 180
```R 
x <- c(1, 2, 3, 4, 5)
sum(x)


# output : 15
```
1 + 2 + 3 + 4 + 5 = 15

R-Strings
---
```R 
"hello"
'hello'

# output : "hello"
# output : "hello"
```
```R 
str <- "Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."
str


# output : "Lorem ipsum dolor sit amet,\nconsectetur adipiscing elit,\nsed do eiusmod tempor incididunt\nut labore et dolore magna aliqua."
```
**String Length**
```R 
str <- "Hello World!"
nchar(str)


# output : 12
```
**Check in String**
```R 
str <- "Hello World!"
grepl("H", str)
grepl("Hello", str)
grepl("X", str) 

# output : TRUE
# output : TRUE
# output : FALSE
```
### R Escape Characters
```R 
str <- "We are the so-called "Vikings", from the north."
str

# output : Error: unexpected symbol in "str <- "We are the so-called "Vikings"
```
```R 
str <- "We are the so-called \"Vikings\", from the north."
str
cat(str)

# output : "We are the so-called \"Vikings\", from the north."
# output : we are the so-called "Vikings", from the north.
```
Other escape characters in R:

`\\` Backslash

`\n` New Line

`\r` Carriage Return

`\t` Tab

`\b` Backspace


R-Booleans-Logical-Values
---
```R 
10 > 9    # TRUE because 10 is greater than 9
10 == 9   # FALSE because 10 is not equal to 9
10 < 9    # FALSE because 10 is greater than 9 


# output : TRUE
# output : FALSE
# output : FALSE
```
```R 
a <- 10
b <- 9
a > b 


# output : TRUE
```
```R 
a <- 200
b <- 33

if (b > a) {
  print ("b is greater than a")
} else {
  print("b is not greater than a")} 


# output : "b < a"
```

R-Operators
---
### R Assignment Operators
```R 
my_var <- 3
my_var

# output : 3
```
```R 
my_var <<- 3      # global assigner
my_var

# output : 3
```
```R 
3 -> my_var       # x <- 3 is equal to 3 -> x
my_var

# output : 3
```
```R 
3 ->> my_var      # my_var <<- 3 is equal to 3 ->> my_var
my_var

# output : 3
```
### R Comparison Operators
`x == y` Equal

`x != y` Not equal

`x > y` Greater than

`x < y` Less than

`x >= y`  Greater than or equal to

`x <= y` Less than or equal to
### R Logical Operators
`&`	Element-wise Logical AND operator. Returns TRUE if both elements are TRUE

`&&` 	Logical AND operator - Returns TRUE if both statements are TRUE

`|` 	Elementwise- Logical OR operator. Returns TRUE if one of the statements is TRUE

`||` 	Logical OR operator. Returns TRUE if one of the statements is TRUE

`! `	Logical NOT - Returns FALSE if statement is TRUE
### R Miscellaneous Operators
`:`	Creates a series of numbers in a sequence 	`x <- 1:10`

`%in%`	Find out if an element belongs to a vector 	`x %in% y`

`%*%`	Matrix Multiplication 	`x <- Matrix1 %*% Matrix2`


R-If-Else
---
```R 
a <- 33
b <- 200

if (b > a) {
  print("b is greater than a")} 


# output : "b is greater than a"
```
```R 
a <- 33
b <- 200

if (b > a) {
  print("b is greater than a")
} else if (a == b) {
  print ("a and b are equal")} 


# output : "b is greater than a"
```
```R 
a <- 200
b <- 33

if (b > a) {
  print("b is greater than a")
} else if (a == b) {
  print("a and b are equal")
} else {
  print("a is greater than b")}


# output : "a is greater than b"
```
```R 
a <- 200
b <- 33

if (b > a) {
  print("b is greater than a")
} else {
  print("b is not greater than a")} 


# output : "b is not greater than a"
```
```R 
x <- 41

if (x > 10) {
  print("Above ten")
  if (x > 20) {
    print("and also above 20!")
  } else {
    print("but not above 20.")}
} else {
  print("below 10.")} 


# output : "Above ten"
# output : "and also above 20!"
```

R-AND-OR-Operators
---
```R 
a <- 200
b <- 33
c <- 500

if (a > b & c > a) {
  print("Both conditions are true")}


# output : "Both conditions are true"
```
```R 
a <- 200
b <- 33
c <- 500

if (a > b | a > c) {
  print("At least one of the conditions is true")}


# output : "At least one of the conditions is true"
```
```R 
(1 < 2) && (2 >= 3)     # AND , If the first condition is false, the other conditions are not checked.
!(1 > 2)                # Used to invert the result of a logical expression
(1 < 2) & (2 >= 3)      # AND
(1 < 2) || (2 >= 3)     # OR , If the first condition is true, the second condition is stopped.
(1 < 2) | (2 >= 3)      # OR
xor(1, 1)               # This function returns TRUE only if one of the two conditions is true, but not both.


# output : TRUE
# output : FALSE
# output : FALSE
# output : TRUE
# output : TRUE
# output : FALSE
```

R-While-Loop
---
```R 
i <- 1
while (i < 6) {
  print(i)
  i <- i + 1} 


# output : 1
# output : 2
# output : 3
# output : 4
# output : 5
```
```R 
i <- 1
while (i < 6) {
  print(i)
  i <- i + 1
  if (i == 4) {
    break}} 


# output : 1
# output : 2
# output : 3
```
```R 
i <- 0
while (i < 6) {
  i <- i + 1
  if (i == 3) {
    next}
  print(i)} 


# output : 1
# output : 2
# output : 4
# output : 5
# output : 6
```
```R 
dice <- 1
while (dice <= 6) {
  if (dice < 6) {
    print("No Yahtzee")
  } else {
    print("Yahtzee!")}
  dice <- dice + 1}


# output : "No Yahtzee"
# output : "No Yahtzee"
# output : "No Yahtzee"
# output : "No Yahtzee"
# output : "No Yahtzee"
# output : "Yahtzee!"
```

R-For-Loop
---
```R 
for (x in 1:10) {
  print(x)} 


# output : 1
# output : 2
# output : 3
# output : 4
# output : 5
# output : 6
# output : 7
# output : 8
# output : 9
# output : 10
```
```R 
fruits <- list("apple", "banana", "cherry")
for (x in fruits) {
  print(x)} 


# output : "apple"
# output : "banana"
# output : "cherry"
```

```R 
dice <- c(1, 2, 3, 4, 5, 6)

for (x in dice) {
  print(x)}


# output : 1
# output : 2
# output : 3
# output : 4
# output : 5
# output : 6
```
```R 
fruits <- list("apple", "banana", "cherry")

for (x in fruits) {
  if (x == "cherry") {
    break}
  print(x)} 


# output : "apple"
# output : "banana"
```
```R
fruits <- list("apple", "banana", "cherry")

for (x in fruits) {
  if (x == "banana") {
    next}
  print(x)} 


# output : "apple"
# output : "cherry"
```
```R 
dice <- 1:6

for(x in dice) {
  if (x == 6) {
    print(paste("The dice number is", x, "Yahtzee!"))
  } else {
    print(paste("The dice number is", x, "Not Yahtzee"))}} 


# output : "The dice number is 1 Not Yahtzee"
# output : "The dice number is 2 Not Yahtzee"
# output : "The dice number is 3 Not Yahtzee"
# output : "The dice number is 4 Not Yahtzee"
# output : "The dice number is 5 Not Yahtzee"
# output : "The dice number is 6 Yahtzee!"
```
```R 
adj <- list("red", "big", "tasty")

fruits <- list("apple", "banana", "cherry")
  for (x in adj) {
    for (y in fruits) {
      print(paste(x, y))}} 


# output : "red apple"
# output : "red banana"
# output : "red cherry"
# output : "big apple"
# output : "big banana"
# output : "big cherry"
# output : "tasty apple"
# output : "tasty banana"
# output : "tasty cherry"
```

R-Functions
---
```R 
my_function <- function() { 
  print("Hello World!")} 
my_function() 


# output : "Hello World!"
```
```R 
my_function <- function(fname) {
  paste(fname, "Griffin")}

my_function("Peter")
my_function("Lois")
my_function("Stewie") 


# output : "Peter Griffin"
# output : "Lois Griffin"
# output : "Stewie Griffin"
```
```R 
my_function <- function(fname, lname) {
  paste(fname, lname)}

my_function("Peter", "Griffin") 


# output : "Peter Griffin"
```
```R 
my_function <- function(country = "Norway") {
  paste("I am from", country)}

my_function("Sweden")
my_function("India")
my_function() # will get the default value, which is Norway
my_function("USA") 


# output : "I am from Sweden"
# output : "I am from India"
# output : "I am from Norway"
# output : "I am from USA"
```
```R 
my_function <- function(x) {
  return (5 * x)}

print(my_function(3))
print(my_function(5))
print(my_function(9)) 


# output : 15
# output : 25
# output : 45
```

### Nested Functions
```R 
Nested_function <- function(x, y) {
  a <- x + y
  return(a)}

Nested_function(Nested_function(2,2), Nested_function(3,3)) 


# output : 10
```
```R 
Outer_func <- function(x) {
  Inner_func <- function(y) {
    a <- x + y
    return(a)}
  return (Inner_func)}

output <- Outer_func(3) # To call the Outer_func
output(5) 


# output : 8
```
You cannot directly call the function because the Inner_func has been defined (nested) inside the Outer_func.

We need to call Outer_func first in order to call Inner_func as a second step.

We need to create a new variable called output and give it a value, which is 3 here.

We then print the output with the desired value of "y", which in this case is 5.

The output is therefore 8 (3 + 5).

### R Function Recursion
```R 
tri_recursion <- function(k) {
  if (k > 0) {
    result <- k + tri_recursion(k - 1)
    print(result)
  } else {
    result = 0
    return(result)}}
    
tri_recursion(6)
```
```Python
def tri_recursion(k):
  if k > 0:
    result = k + tri_recursion(k - 1)
    print(result)
  else:
    result = 0
  return result 
tri_recursion(6)

# output :
1
3
6
10
15
21
```
fun 1 : 6 + ?

fun 2 : 5 + ?

fun 3 : 4 + ?

fun 4 : 3 + ?

fun 5 : 2 + ?

fun 6 : 1 + ?

fun 7 : answer is 0

👇
fun 1 : 6 + 15 , answer is 21

fun 2 : 5 + 10 , answer is 15

fun 3 : 4 + 6 , answer is 10

fun 4 : 3 + 3 , answer is 6

fun 5 : 2 + 1 , answer is 3

fun 6 : 1 + 0 , answer is 1

fun 7 : answer is 0
### R Global Variables
```R 
txt <- "awesome"
my_function <- function() {
  paste("R is", txt)}

my_function() 


# output : "R is awesome"
```
```R 
txt <- "global variable"
my_function <- function() {
  txt = "fantastic"
  paste("R is", txt)}

my_function()
print(txt)


# output : "R is fantastic"
# output : "global variable"
```
```R 
txt <- "awesome"
my_function <- function() {
  txt <<- "fantastic"
  paste("R is", txt)}

my_function()
paste("R is", txt) 


# output : "R is fantastic"
# output : "R is fantastic"
```

R-Vectors
---
A vector is simply a list of items that are of the same type.

To combine the list of items to a vector, use the c() function and separate the items by a comma.
```R 
fruits <- c("banana", "apple", "orange")    # Vector of strings
fruits 


# output : "banana" "apple"  "orange"
```
```R 
numbers <- c(1, 2, 3)      # Vector of numerical values
numbers 


# output : 1 2 3
```
```R 
numbers <- 1:10        # Vector with numerical values in a sequence
numbers 


# output : 1  2  3  4  5  6  7  8  9 10
```
```R 
numbers1 <- 1.5:6.5
numbers1


# output : 1.5 2.5 3.5 4.5 5.5 6.5
```
```R 
log_values <- c(TRUE, FALSE, TRUE, FALSE)  # Vector of logical values
log_values


# output : TRUE FALSE  TRUE FALSE
```
**Vector Length**
```R 
fruits <- c("banana", "apple", "orange")
length(fruits) 


# output : 3
```
**Sort a Vector**
```R 
fruits <- c("banana", "apple", "orange", "mango", "lemon")
numbers <- c(13, 3, 5, 7, 20, 2)

sort(fruits)  # Sort a string
sort(numbers) # Sort numbers 


# output : "apple"  "banana" "lemon"  "mango"  "orange"
# output :  2  3  5  7 13 20
```
**Access Vectors**
```R 
fruits <- c("banana", "apple", "orange")
fruits[1] 


# output : "banana"
```
```R 
fruits <- c("banana", "apple", "orange", "mango", "lemon")
fruits[c(1, 3)]  # Access the first and third item (banana and orange)


# output : "banana" "orange"
```
```R 
fruits <- c("banana", "apple", "orange", "mango", "lemon")
fruits[c(-1)]  # Access all items except for the first item


# output : "apple"  "orange" "mango"  "lemon" 
```
```R 
a <- 10
a[length(a)-2+1]


# output : 9
```
```R 
a <- 10
a[1:9]


# output : 1 2 3 4 5 6 7 8 9
```
```R 
x <- c(3, 5, 2, 8, 5, 7)
which(x == 5)
which(x > 4)


# output : 2 5
# output : 2 4 5 6
```
```R 
y <- c(0, 3, 0, 4, 0, 5)
which(y != 0)


# output : 2 4 6
```
```R 
a <- 10
a[seq(1,10,2)] # Select odd indices of vector


# output : 1 3 5 7 9
```
```R 
a <- 10
a[a > 0.8 | a <= 0.1]


# output : 1  2  3  4  5  6  7  8  9 10
```
**Change an Item**
```R 
fruits <- c("banana", "apple", "orange", "mango", "lemon")

fruits[1] <- "pear"     # Change "banana" to "pear"
fruits                  # Print fruits


# output : "pear"   "apple"  "orange" "mango"  "lemon"
```
**Repeat Vectors**
```R 
repeat_each <- rep(c(1,2,3), each = 3)
repeat_each 


# output : 1 1 1 2 2 2 3 3 3
```
```R 
repeat_times <- rep(c(1,2,3), times = 3)
repeat_times 


# output : 1 2 3 1 2 3 1 2 3
```
```R 
repeat_indepent <- rep(c(1,2,3), times = c(5,2,1))
repeat_indepent 


# output : 1 1 1 1 1 2 2 3
```
```R 
rep(1:3, times = 2)


# output : 1 2 3 1 2 3
```
```R 
rep(1:3, each = 2)


# output : 1 1 2 2 3 3
```
```R 
rep(1:3, length.out = 7)


# output : 1 2 3 1 2 3 1
```
**Generating Sequenced Vectors**
`seq(from = ,to = ,by = ,length.out = )`

```R 
numbers <- 1:10
numbers 


# output : 1  2  3  4  5  6  7  8  9 10
```
```R 
numbers <- seq(from = 0, to = 100, by = 20)
numbers 


# output : 0  20  40  60  80 100
```
```R 
seq(from = 1, to = 10, by = 2)


# output : 1 3 5 7 9
```
```R 
seq(from = 1, to = 10, length.out = 5)


# output : 1.0 3.25 5.5 7.75 10.0
```
```R 
seq(from = 1, to = 10, length.out = 4)


# output : 1.0 3.0 5.0 7.0 9.0
```
```R 
seq(from = 10, to = 1, by = -2)


# output : 10 8 6 4 2
```

R-Lists
---
A list in R can contain many different data types inside it. A list is a collection of data which is ordered and changeable.

```R 
thislist <- list("apple", "banana", "cherry")  # List of strings
thislist 


# output : 
"apple"

"banana"

"cherry"
```
**Access Lists**
```R 
thislist <- list("apple", "banana", "cherry")
thislist[1]


# output : "apple"
```
**Change Item Value**
```R 
thislist <- list("apple", "banana", "cherry")
thislist[1] <- "blackcurrant"
thislist 


# output : "blackcurrant"
# output : "banana"
# output : "cherry"
```
**List Length**
```R 
thislist <- list("apple", "banana", "cherry")
length(thislist)


# output : 3
```
**Check if Item Exists**
```R 
thislist <- list("apple", "banana", "cherry")
"apple" %in% thislist


# output : TRUE
```
**Add List Items**
```R 
thislist <- list("apple", "banana", "cherry")
append(thislist, "orange") 



# output : "apple"
# output : "banana"
# output : "cherry"
# output : "orange"
```
```R 
thislist <- list("apple", "banana", "cherry")
append(thislist, "orange", after = 2) 


# output : "apple"
# output : "banana"
# output : "orange"
# output : "cherry"
```
**Remove List Items**
```R 
thislist <- list("apple", "banana", "cherry")
newlist <- thislist[-1]
newlist 
thislist


# output : "banana"
# output : "cherry"


# output : "apple"
# output : "banana"
# output : "cherry"
```
**Range of Indexes**
```R 
thislist <- list("apple", "banana", "cherry", "orange", "kiwi", "melon", "mango")
(thislist)[2:5] 



# output : "banana"
# output : "cherry"
# output : "orange"
# output : "kiwi"
```
**Loop Through a List**
```R 
thislist <- list("apple", "banana", "cherry")

for (x in thislist) {
  print(x)}


# output : "apple"
# output : "banana"
# output : "cherry"
```
**Join Two Lists**
```R 
list1 <- list("a", "b", "c")
list2 <- list(1,2,3)
list3 <- c(list1,list2)
list3 


# output : "a"
# output : "b"
# output : "c"
# output : 1
# output : 2
# output : 3
```

R-Matrices
---
A matrix is a two dimensional data set with columns and rows.

A column is a vertical representation of data, while a row is a horizontal representation of data.

A matrix can be created with the matrix() function. Specify the nrow and ncol parameters to get the amount of rows and columns:

```R
thismatrix <- matrix(c(1,2,3,4,5,6), nrow = 3, ncol = 2)
thismatrix 


# output :
     [,1] [,2]
[1,]    1    4
[2,]    2    5
[3,]    3    6
```
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange"), nrow = 2, ncol = 2)
thismatrix 


# output :
     [,1]     [,2]    
[1,] "apple"  "cherry"
[2,] "banana" "orange"
```
**Access Matrix Items**
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange"), nrow = 2, ncol = 2)
thismatrix[1, 2]  #[nrow, ncol]


# output : "cherry"
```
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange"), nrow = 2, ncol = 2)
thismatrix[2,]


# output : "banana" "orange"
```
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange"), nrow = 2, ncol = 2)
thismatrix[,2]


# output : "cherry" "orange"
```
**Access More Than One Row**
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange","grape", "pineapple", "pear", "melon", "fig"), nrow = 3, ncol = 3)
thismatrix
thismatrix[c(1,2),] 
thismatrix[c(1,2)] 


# output : 
     [,1]     [,2]        [,3]   
[1,] "apple"  "orange"    "pear"
[2,] "banana" "grape"     "melon"
[3,] "cherry" "pineapple" "fig"


     [,1]     [,2]     [,3]   
[1,] "apple"  "orange" "pear"
[2,] "banana" "grape"  "melon"


[1] "apple"  "banana"
```
**Access More Than One Column**
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange","grape", "pineapple", "pear", "melon", "fig"), nrow = 3, ncol = 3)
thismatrix[, c(1,2)] 


# output : 
     [,1]     [,2]       
[1,] "apple"  "orange"
[2,] "banana" "grape"
[3,] "cherry" "pineapple"
```
**Access More Than One Column anfd Row**
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange","grape", "pineapple", "pear", "melon", "fig"), nrow = 3, ncol = 3)
thismatrix[c(1,2), c(1,2)] 


# output : 
     [,1]     [,2]    
[1,] "apple"  "orange"
[2,] "banana" "grape"
```
**Add Rows and Columns**

```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange","grape", "pineapple", "pear", "melon", "fig"), nrow = 3, ncol = 3)
newmatrix <- cbind(thismatrix, c("strawberry", "blueberry", "raspberry"))
newmatrix 


# output : 
     [,1]     [,2]        [,3]    [,4]        
[1,] "apple"  "orange"    "pear"  "strawberry"
[2,] "banana" "grape"     "melon" "blueberry"
[3,] "cherry" "pineapple" "fig"   "raspberry"
```
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange","grape", "pineapple", "pear", "melon", "fig"), nrow = 3, ncol = 3)
newmatrix <- rbind(thismatrix, c("strawberry", "blueberry", "raspberry"))
newmatrix 


# output : 
     [,1]         [,2]        [,3]       
[1,] "apple"      "orange"    "pear"
[2,] "banana"     "grape"     "melon"    
[3,] "cherry"     "pineapple" "fig"
[4,] "strawberry" "blueberry" "raspberry"
```
**Remove Rows and Columns**
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange", "mango", "pineapple"), nrow = 3, ncol =2)
thismatrix
thismatrix <- thismatrix[-c(1), -c(1)]   # Remove the first row and the first column
thismatrix 


# output : 
     [,1]     [,2]
[1,] "apple"  "orange"
[2,] "banana" "mango"
[3,] "cherry" "pineapple"


# output : 
[1] "mango"     "pineapple"
```
**Check if an Item Exists**
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange"), nrow = 2, ncol = 2)
"apple" %in% thismatrix 


# output : TRUE
```
**Number of Rows and Columns**
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange"), nrow = 2, ncol = 2)
dim(thismatrix) 


# output : 2 2
```
**Matrix Length**
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange"), nrow = 2, ncol = 2)
length(thismatrix)


# output : 4
```
**Loop Through a MatrixLoop Through a Matrix**
```R
thismatrix <- matrix(c("apple", "banana", "cherry", "orange"), nrow = 2, ncol = 2)
thismatrix

for (rows in 1:nrow(thismatrix)) {
  for (columns in 1:ncol(thismatrix)) {
    print(thismatrix[rows, columns])}} 


# output : 
     [,1]     [,2]    
[1,] "apple"  "cherry"
[2,] "banana" "orange"


# output : 
[1] "apple"
[1] "cherry"
[1] "banana"
[1] "orange"
```
**Combine two Matrices**

```R
#Combine matrices
Matrix1 <- matrix(c("apple", "banana", "cherry", "grape"), nrow = 2, ncol = 2)
Matrix2 <- matrix(c("orange", "mango", "pineapple", "watermelon"), nrow = 2, ncol = 2)

#Adding it as a rows
Matrix_Combined <- rbind(Matrix1, Matrix2)
Matrix_Combined

#Adding it as a columns
Matrix_Combined <- cbind(Matrix1, Matrix2)
Matrix_Combined 


# output : 
     [,1]     [,2]        
[1,] "apple"  "cherry"
[2,] "banana" "grape"
[3,] "orange" "pineapple"
[4,] "mango"  "watermelon"


# output : 
     [,1]     [,2]     [,3]     [,4]        
[1,] "apple"  "cherry" "orange" "pineapple" 
[2,] "banana" "grape"  "mango"  "watermelon"
```

R-Arrays
---
Compared to matrices, arrays can have more than two dimensions.
We can use the array() function to create an array, and the dim parameter to specify the dimensions:

```R
```R
#An array with one dimension with values ranging from 1 to 24
thisarray <- c(1:24)
thisarray


# output :  1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24

#An array with more than one dimension
multiarray <- array(thisarray, dim = c(4, 3, 2))       # c(Row, Column, Number of tables)
multiarray 


# output :
, , 1

     [,1] [,2] [,3]
[1,]    1    5    9
[2,]    2    6   10
[3,]    3    7   11
[4,]    4    8   12

, , 2

     [,1] [,2] [,3]
[1,]   13   17   21
[2,]   14   18   22
[3,]   15   19   23
[4,]   16   20   24
```
**Access Array Items**
```R
thisarray <- c(1:24)
multiarray <- array(thisarray, dim = c(4, 3, 2))     # array[row position, column position, matrix level]
multiarray[2, 3, 2] 
```
```R
thisarray <- c(1:24)

#Access all the items from the first row from matrix one
multiarray <- array(thisarray, dim = c(4, 3, 2))
multiarray[c(1),,1]

#Access all the items from the first column from matrix one
multiarray <- array(thisarray, dim = c(4, 3, 2))
multiarray[,c(1),1] 


# output :
[1] 1 5 9
[1] 1 2 3 4
```
**Check if an Item Exists**
```R
thisarray <- c(1:24)
multiarray <- array(thisarray, dim = c(4, 3, 2))
2 %in% multiarray 

# output : TRUE
```
**Amount of Rows and Columns**
```R
thisarray <- c(1:24)
multiarray <- array(thisarray, dim = c(4, 3, 2))
dim(multiarray) 

# output : 4 3 2
```
**Array Length**

```R
thisarray <- c(1:24)
multiarray <- array(thisarray, dim = c(4, 3, 2))
length(multiarray) 


# output : 24
```
**Loop Through an Array**
```R
thisarray <- c(1:24)
multiarray <- array(thisarray, dim = c(4, 3, 2))

for(x in multiarray){
  print(x)} 


# output :
[1] 1
[1] 2
[1] 3
[1] 4
[1] 5
[1] 6
[1] 7
[1] 8
[1] 9
[1] 10
[1] 11
[1] 12
[1] 13
[1] 14
[1] 15
[1] 16
[1] 17
[1] 18
[1] 19
[1] 20
[1] 21
[1] 22
[1] 23
[1] 24
```

R-Data-Frames
---
Data Frames are data displayed in a format as a table.

Data Frames can have different types of data inside it. While the first column can be character, the second and third can be numeric or logical. However, each column should have the same type of data.
```R
#Create a data frame
Data_Frame <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))
print(Data_Frame)


# output :
  Training Pulse Duration
1 Strength   100       60
2  Stamina   150       30
3    Other   120       45
```
**Summarize the Data**
```R
Data_Frame <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))
print(Data_Frame)
summary(Data_Frame)


# output :
  Training Pulse Duration
1 Strength   100       60
2  Stamina   150       30
3    Other   120       45


   Training             Pulse          Duration   
 Length:3           Min.   :100.0   Min.   :30.0
 Class :character   1st Qu.:110.0   1st Qu.:37.5  
 Mode  :character   Median :120.0   Median :45.0
                    Mean   :123.3   Mean   :45.0  
                    3rd Qu.:135.0   3rd Qu.:52.5
                    Max.   :150.0   Max.   :60.0
```
**Access Items**

```R
Data_Frame <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))

Data_Frame[1]
Data_Frame[["Training"]]
Data_Frame$Training 


# output :
  Training
1 Strength
2  Stamina
3    Other


# output : "Strength" "Stamina"  "Other"


# output : "Strength" "Stamina"  "Other"
```
**Add Rows**
```R
Data_Frame <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))

#Add a new row
New_row_DF <- rbind(Data_Frame, c("Strength", 110, 110))

#Print the new row
New_row_DF 


# output :
  Training Pulse Duration
1 Strength   100       60
2  Stamina   150       30
3    Other   120       45
4 Strength   110      110
```
**Add Columns**

```R
Data_Frame <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))

#Add a new column
New_col_DF <- cbind(Data_Frame, Steps = c(1000, 6000, 2000))

#Print the new column
New_col_DF 


# output :
  Training Pulse Duration Steps
1 Strength   100       60  1000
2  Stamina   150       30  6000
3    Other   120       45  2000
```
**Remove Rows and Columns**
```R
Data_Frame <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))

#remove the first row and column
Data_Frame_New <- Data_Frame[-c(1), -c(1)]

#Print the new data frame
Data_Frame_New 
Data_Frame


# output :
  Pulse Duration
2   150       30
3   120       45


# output :
  Training Pulse Duration
1 Strength   100       60
2  Stamina   150       30
3    Other   120       45
```
**Amount of Rows and Columns**
```R
Data_Frame <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))

dim(Data_Frame) 
Data_Frame


# output : 3 3


# output :
  Training Pulse Duration
1 Strength   100       60
2  Stamina   150       30
3    Other   120       45
```
```R
Data_Frame <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))

ncol(Data_Frame)
nrow(Data_Frame) 


# output : 3
# output : 3
```
**Data Frame Length**
```R
Data_Frame <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))

length(Data_Frame) 


# output : 3
```
**Combining Data Frames**
```R
Data_Frame1 <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))

Data_Frame2 <- data.frame (
  Training = c("Stamina", "Stamina", "Strength"),
  Pulse = c(140, 150, 160),
  Duration = c(30, 30, 20))

New_Data_Frame <- rbind(Data_Frame1, Data_Frame2)
New_Data_Frame 


# output :
  Training Pulse Duration
1 Strength   100       60
2  Stamina   150       30
3    Other   120       45
4  Stamina   140       30
5  Stamina   150       30
6 Strength   160       20
```
```R
Data_Frame3 <- data.frame (
  Training = c("Strength", "Stamina", "Other"),
  Pulse = c(100, 150, 120),
  Duration = c(60, 30, 45))

Data_Frame4 <- data.frame (
  Steps = c(3000, 6000, 2000),
  Calories = c(300, 400, 300))

New_Data_Frame1 <- cbind(Data_Frame3, Data_Frame4)
New_Data_Frame1 


# output :
  Training Pulse Duration Steps Calories
1 Strength   100       60  3000      300
2  Stamina   150       30  6000      400
3    Other   120       45  2000      300
```
**Matrix to Data frames**
```R
a = matrix(1:9, nrow=3, byrow=TRUE)
print(a)
b = data.frame(a)
print(b)
colnames(b) = c('c1', 'c2', 'c3')
print(b)
b$c1


# output :
     [,1] [,2] [,3]
[1,]    1    2    3
[2,]    4    5    6
[3,]    7    8    9

  X1 X2 X3
1  1  2  3
2  4  5  6
3  7  8  9

  c1 c2 c3
1  1  2  3
2  4  5  6
3  7  8  9

[1] 1 4 7
```

R-Factors
---

Factors are used to categorize data. Examples of factors are:

* **Demography: Male/Female**
* **Music: Rock, Pop, Classic, Jazz**
* **Training: Strength, Stamina**

```R
#Create a factor
music_genre <- factor(c("Jazz", "Rock", "Classic", "Classic", "Pop", "Jazz", "Rock", "Jazz"))
music_genre 


# output :
[1] Jazz    Rock    Classic Classc Pop     Jazz    Rock    Jazz   
Levels: Classic Jazz Pop Rock
```
```R
music_genre <- factor(c("Jazz", "Rock", "Classic", "Classic", "Pop", "Jazz", "Rock", "Jazz"))
levels(music_genre) 


# output :
[1] "Classic" "Jazz"    "Pop"     "Rock" 
```
```R
music_genre <- factor(c("Jazz", "Rock", "Classic", "Classic", "Pop", "Jazz", "Rock", "Jazz"), levels = c("Classic", "Jazz", "Pop", "Rock", "Other"))
levels(music_genre)


# output :
[1] "Classic" "Jazz"    "Pop"     "Rock"    "Other"
```
**Factor Length**

```R
music_genre <- factor(c("Jazz", "Rock", "Classic", "Classic", "Pop", "Jazz", "Rock", "Jazz"))
length(music_genre) 


# output :
[1] 8
```
**Access Factors**
```R
music_genre <- factor(c("Jazz", "Rock", "Classic", "Classic", "Pop", "Jazz", "Rock", "Jazz"))
music_genre[3] 


# output :
[1] Classic
Levels: Classic Jazz Pop Rock
```
**Change Item Value**
```R
music_genre <- factor(c("Jazz", "Rock", "Classic", "Classic", "Pop", "Jazz", "Rock", "Jazz"))
music_genre[3] <- "Pop"
music_genre[3]


# output :
[1] Pop
Levels: Classic Jazz Pop Rock
```
```R
music_genre <- factor(c("Jazz", "Rock", "Classic", "Classic", "Pop", "Jazz", "Rock", "Jazz"), levels = c("Classic", "Jazz", "Pop", "Rock", "Opera"))
music_genre[3] <- "Opera"
music_genre[3]


# output :
[1] Opera
Levels: Classic Jazz Pop Rock Opera
```

R-Plotting
---
The plot() function is used to draw points (markers) in a diagram.

The function takes parameters for specifying points in the diagram.

* **Parameter 1 specifies points on the x-axis.**

* **Parameter 2 specifies points on the y-axis.**

```R
plot(1, 3)
```
![720daceb-93ad-4a94-ab5b-03c4ba8f7eff](https://github.com/user-attachments/assets/2e30704a-9708-40d3-833f-ae63773a3308)
```R
plot(c(1, 8), c(3, 10))
```
![ad881a62-9f21-4873-954d-5f3669a3e089](https://github.com/user-attachments/assets/d0300125-91d6-4f94-b1b6-e561fe4327cb)
**Multiple Points**
```R
plot(c(1, 2, 3, 4, 5), c(3, 7, 8, 9, 12))
```
![ef79ea99-79ce-415f-be8a-6cc02d9d4d0c](https://github.com/user-attachments/assets/a30b013c-edb8-490b-967e-e1e8b1d40fee)
```R
x <- c(1, 2, 3, 4, 5)
y <- c(3, 7, 8, 9, 12)

plot(x, y)
```
![8f7c367c-37a9-4135-8d61-d88d913fcd0b](https://github.com/user-attachments/assets/033c4e1c-ff96-4096-80ad-e101efb49707)
**Sequences of Points**
```R
plot(1:10)
```
![8659e72b-217e-43d4-a6b3-6863d151d4a5](https://github.com/user-attachments/assets/49486e88-0a81-48c1-ad64-5e8f5784c798)
**Draw a Line**
```R
plot(1:10, type="l")
```
![11523d62-6120-487b-9e3e-fbd1f7a4561d](https://github.com/user-attachments/assets/7e11eac4-53c9-483c-b100-0da651386915)
**Plot Labels**
```R
plot(1:10, main="My Graph", xlab="The x-axis", ylab="The y axis")
```
![ff2454c3-90a8-4976-b89d-6d0b8015ff98](https://github.com/user-attachments/assets/1fdae650-493f-4275-8cdf-3d1a7a7f10f8)
**Colors**

```R
plot(1:10, col="red")
```
![f63bf6e6-5429-4924-a1bc-cd2496df8718](https://github.com/user-attachments/assets/35fa91bf-212c-4e60-ba0b-6e930f5be755)
**Size**
```R
plot(1:10, cex=2)
```
![4b876860-fc37-4d07-9c85-a5d9b53f67db](https://github.com/user-attachments/assets/b40ebe32-b5b7-4708-b569-813b8f599c39)

**Point Shape**
```R
plot(1:10, pch=25, cex=2)    # pch can change the shape
```
![b1ad81ce-dddf-49dc-90fe-c29337a71f89](https://github.com/user-attachments/assets/51a018b5-883c-44e2-8565-f590988c1e61)

pch parameter ranges :

![download](https://github.com/user-attachments/assets/c0f48c63-591a-44fa-8485-883a03d40729)

R-Line
---
```R
plot(1:10, type="l")
```
![2351a310-f29a-43f8-85f0-0a3ca76dca54](https://github.com/user-attachments/assets/aa793c57-d010-4dd9-a47c-a8321a30e684)
**Line Color**
```R
plot(1:10, type="l", col="blue")
```
![ce1d8c76-1fce-425d-a8d7-c4a0dd3fa4a0](https://github.com/user-attachments/assets/1015d60e-77c6-4a46-8f9b-d95a386bf7bb)

**Line Width**
```R
plot(1:10, type="l", lwd=2)
```
![43011e81-9e18-4adb-8743-9c7fbfc22667](https://github.com/user-attachments/assets/1930a3c3-8c65-4e04-9338-57dfc9b1297e)
**Line Styles**

```R
plot(1:10, type="l", lwd=5, lty=3) 
```
![f3de059d-d4f1-4006-8c9d-32213f890e75](https://github.com/user-attachments/assets/1eca4626-57bf-4f19-ae3c-f5e6676570ea)
* 0 removes the line

* 1 displays a solid line

* 2 displays a dashed line

* 3 displays a dotted line

* 4 displays a "dot dashed" line

* 5 displays a "long dashed" line

* 6 displays a "two dashed" line

**Multiple Lines**
```R
line1 <- c(1,2,3,4,5,10)
line2 <- c(2,5,7,8,9,10)

plot(line1, type = "l", col = "blue")
lines(line2, type="l", col = "red")
```
![c4634149-3eb1-44c1-b35f-fa9ec7e8618b](https://github.com/user-attachments/assets/bcf19fee-4d5a-4dd4-abd5-0142c96d30de)

R-Scatter-Plot
---
```R
x <- c(5,7,8,7,2,2,9,4,11,12,9,6)
y <- c(99,86,87,88,111,103,87,94,78,77,85,86)

plot(x, y)
```
![737feb9a-ef5b-4896-8014-8f25d80c9bb3](https://github.com/user-attachments/assets/778a01aa-fe74-4f1f-ad33-3f0552214160)
```R
x <- c(5,7,8,7,2,2,9,4,11,12,9,6)
y <- c(99,86,87,88,111,103,87,94,78,77,85,86)

plot(x, y, main="Observation of Cars", xlab="Car age", ylab="Car speed")
```
![3f979146-04be-4e6d-ae5f-ce34a421d283](https://github.com/user-attachments/assets/4f89a85d-af6a-4ca6-a045-756bdf8bd393)

**Compare Plots**
To compare the plot with another plot, use the points() function:
```R
x1 <- c(5,7,8,7,2,2,9,4,11,12,9,6)
y1 <- c(99,86,87,88,111,103,87,94,78,77,85,86)

x2 <- c(2,2,8,1,15,8,12,9,7,3,11,4,7,14,12)
y2 <- c(100,105,84,105,90,99,90,95,94,100,79,112,91,80,85)

plot(x1, y1, main="Observation of Cars", xlab="Car age", ylab="Car speed", col="red", cex=2)
points(x2, y2, col="blue", cex=2)
```
![ac26935b-1a8d-4c0e-be53-90d29ecbbed7](https://github.com/user-attachments/assets/906df658-588c-46c2-a6af-bce5384072c5)


R-Pie-Charts
---
```R
x <- c(10,20,30,40)
pie(x)
```
![b94b4597-e52f-4026-855b-499e489645f0](https://github.com/user-attachments/assets/c695464d-0bb1-4cf8-9241-5572342e6665)
```R
x <- c(10,20,30,40)
pie(x, init.angle = 90)
```
![085569c5-e990-4380-8e54-68681609fc88](https://github.com/user-attachments/assets/c87288bf-9610-421d-963b-d5b36adb3605)

**Labels and Header**
```R
x <- c(10,20,30,40)

mylabel <- c("Apples", "Bananas", "Cherries", "Dates")

pie(x, label = mylabel, main = "Fruits")
```
![db0eca36-3164-4174-be3a-909c48dfc431](https://github.com/user-attachments/assets/187150cd-7422-4523-8099-10cab59a918c)
**Colors**
```R
x <- c(10,20,30,40)

colors <- c("blue", "yellow", "green", "black")

pie(x, label = mylabel, main = "Fruits", col = colors)
```
![ccf66236-9940-4537-b0a7-03e6a9b2a946](https://github.com/user-attachments/assets/6e43cd61-8902-4534-a6d9-2ad2a4045df9)
**Legend**

```R
x <- c(10,20,30,40)

mylabel <- c("Apples", "Bananas", "Cherries", "Dates")

#Create a vector of colors
colors <- c("blue", "yellow", "green", "black")

#Display the pie chart with colors
pie(x, label = mylabel, main = "Pie Chart", col = colors)

#Display the explanation box
legend("bottomright", mylabel, fill = colors)
```
![fc3c5344-3d88-45a2-b2be-abe4ebbff8a7](https://github.com/user-attachments/assets/cde26b4b-3589-47c5-bed5-8a6f6506041e)
The legend can be positioned as either:

`bottomright, bottom, bottomleft, left, topleft, top, topright, right, center `

R-Bar-Charts
---
```R
#x-axis values
x <- c("A", "B", "C", "D")

#y-axis values
y <- c(2, 4, 6, 8)

barplot(y, names.arg = x)
```
![3bd859b8-3b5e-459d-aedd-e42fda9a6042](https://github.com/user-attachments/assets/071ec7dd-3e5c-4649-863d-6cacd78a4f56)
* The x variable represents values in the x-axis (A,B,C,D)

* The y variable represents values in the y-axis (2,4,6,8)

* Then we use the barplot() function to create a bar chart of the values

* `names.arg` defines the names of each observation in the x-axis (under the bar)

**Bar Color**
```R
x <- c("A", "B", "C", "D")
y <- c(2, 4, 6, 8)

barplot(y, names.arg = x, col = "red")
```
![ed65b0f4-317d-4f9f-95a2-ae9ca9ed13f0](https://github.com/user-attachments/assets/224f7a94-fb15-45a4-900f-4914858000cd)
```R
child = c(0,1,1,0,3,2,2,1,0,0,2,2,2,3,0,4,0,1,0,3)
barplot(table(child), col = rainbow(5))
```
![b5cd2507-6cb1-4832-b114-3795f5fb141b](https://github.com/user-attachments/assets/04d3e098-0244-4f0d-b49a-ec3af7a7d6fd)

**Density / Bar Texture**
```R
x <- c("A", "B", "C", "D")
y <- c(2, 4, 6, 8)

barplot(y, names.arg = x, density = 10)
```
![52297301-130f-4f07-8d57-fd764c6d43be](https://github.com/user-attachments/assets/6a5294e2-40d0-41f4-a64d-fa0e738c3ee3)

**Bar Width**

```R
x <- c("A", "B", "C", "D")
y <- c(2, 4, 6, 8)

barplot(y, names.arg = x, width = c(1,2,3,4))
```

![4eaa56d2-d196-448b-86fd-b3f026f89c04](https://github.com/user-attachments/assets/644b67db-640a-4494-a6ba-e49a2ac13f2b)

**Horizontal Bars**
```R
x <- c("A", "B", "C", "D")
y <- c(2, 4, 6, 8)

barplot(y, names.arg = x, horiz = TRUE)
```
![43923e02-f855-45f1-9f0e-3121467d2ad3](https://github.com/user-attachments/assets/bcd07bc3-b19e-4537-8503-8999a2ae51a5)


R-Statistics
---
* Mean, median and mode
* Minimum and maximum value
* Percentiles
* Variance and Standard Devation
* Covariance and Correlation
* Probability distributions

### R Data Set
A data set is a collection of data, often presented in a table.

There is a popular built-in data set in R called "mtcars" (Motor Trend Car Road Tests), which is retrieved from the 1974 Motor Trend US Magazine.

```R
print(mtcars)


# output :
                     mpg cyl  disp  hp drat    wt  qsec vs am gear carb
Mazda RX4           21.0   6 160.0 110 3.90 2.620 16.46  0  1    4    4
Mazda RX4 Wag       21.0   6 160.0 110 3.90 2.875 17.02  0  1    4    4
Datsun 710          22.8   4 108.0  93 3.85 2.320 18.61  1  1    4    1
Hornet 4 Drive      21.4   6 258.0 110 3.08 3.215 19.44  1  0    3    1
Hornet Sportabout   18.7   8 360.0 175 3.15 3.440 17.02  0  0    3    2
Valiant             18.1   6 225.0 105 2.76 3.460 20.22  1  0    3    1
Duster 360          14.3   8 360.0 245 3.21 3.570 15.84  0  0    3    4
Merc 240D           24.4   4 146.7  62 3.69 3.190 20.00  1  0    4    2
Merc 230            22.8   4 140.8  95 3.92 3.150 22.90  1  0    4    2
Merc 280            19.2   6 167.6 123 3.92 3.440 18.30  1  0    4    4
Merc 280C           17.8   6 167.6 123 3.92 3.440 18.90  1  0    4    4
Merc 450SE          16.4   8 275.8 180 3.07 4.070 17.40  0  0    3    3
Merc 450SL          17.3   8 275.8 180 3.07 3.730 17.60  0  0    3    3
Merc 450SLC         15.2   8 275.8 180 3.07 3.780 18.00  0  0    3    3
Cadillac Fleetwood  10.4   8 472.0 205 2.93 5.250 17.98  0  0    3    4
Lincoln Continental 10.4   8 460.0 215 3.00 5.424 17.82  0  0    3    4
Chrysler Imperial   14.7   8 440.0 230 3.23 5.345 17.42  0  0    3    4
Fiat 128            32.4   4  78.7  66 4.08 2.200 19.47  1  1    4    1
Honda Civic         30.4   4  75.7  52 4.93 1.615 18.52  1  1    4    2
Toyota Corolla      33.9   4  71.1  65 4.22 1.835 19.90  1  1    4    1
Toyota Corona       21.5   4 120.1  97 3.70 2.465 20.01  1  0    3    1
Dodge Challenger    15.5   8 318.0 150 2.76 3.520 16.87  0  0    3    2
AMC Javelin         15.2   8 304.0 150 3.15 3.435 17.30  0  0    3    2
Camaro Z28          13.3   8 350.0 245 3.73 3.840 15.41  0  0    3    4
Pontiac Firebird    19.2   8 400.0 175 3.08 3.845 17.05  0  0    3    2
Fiat X1-9           27.3   4  79.0  66 4.08 1.935 18.90  1  1    4    1
Porsche 914-2       26.0   4 120.3  91 4.43 2.140 16.70  0  1    5    2
Lotus Europa        30.4   4  95.1 113 3.77 1.513 16.90  1  1    5    2
Ford Pantera L      15.8   8 351.0 264 4.22 3.170 14.50  0  1    5    4
Ferrari Dino        19.7   6 145.0 175 3.62 2.770 15.50  0  1    5    6
Maserati Bora       15.0   8 301.0 335 3.54 3.570 14.60  0  1    5    8
Volvo 142E          21.4   4 121.0 109 4.11 2.780 18.60  1  1    4    2
```

**Information About the Data Set**
```R
?mtcars
```
**Get Information**
```R
Data_Cars <- mtcars     # create a variable of the mtcars data set for better organization
dim(Data_Cars)          # Use dim() to find the dimension of the data set 
names(Data_Cars)        # Use names() to find the names of the variables from the data set


# output :
[1] 32 11

[1] "mpg"  "cyl"  "disp" "hp"   "drat" "wt"   "qsec" "vs"   "am"   "gear"
[11] "carb"
```
```R
Data_Cars <- mtcars
rownames(Data_Cars)    # Use the rownames() function to get the name of each row in the first column, which is the name of each car:


 [1] "Mazda RX4"           "Mazda RX4 Wag"       "Datsun 710"         
 [4] "Hornet 4 Drive"      "Hornet Sportabout"   "Valiant"            
 [7] "Duster 360"          "Merc 240D"           "Merc 230"           
[10] "Merc 280"            "Merc 280C"           "Merc 450SE"         
[13] "Merc 450SL"          "Merc 450SLC"         "Cadillac Fleetwood" 
[16] "Lincoln Continental" "Chrysler Imperial"   "Fiat 128"           
[19] "Honda Civic"         "Toyota Corolla"      "Toyota Corona"      
[22] "Dodge Challenger"    "AMC Javelin"         "Camaro Z28"         
[25] "Pontiac Firebird"    "Fiat X1-9"           "Porsche 914-2"      
[28] "Lotus Europa"        "Ford Pantera L"      "Ferrari Dino"       
[31] "Maserati Bora"       "Volvo 142E"
```

From the examples above, we have found out that the data set has 32 observations (Mazda RX4, Mazda RX4 Wag, Datsun 710, etc) and 11 variables (mpg, cyl, disp, etc).

A variable is defined as something that can be measured or counted.

Here is a brief explanation of the variables from the mtcars data set:


* Variable Name : Description

* mpg : Miles/(US) Gallon

* cyl : Number of cylinders

* disp : Displacement

* hp : Gross horsepower

* drat : Rear axle ratio

* wt : Weight (1000 lbs)

* qsec : 1/4 mile time

* vs : Engine (0 = V-shaped, 1 = straight)

* am : Transmission (0 = automatic, 1 = manual)

* gear : Number of forward gears

* carb : Number of carburetors


**Print Variable Values**

If you want to print all values that belong to a variable, access the data frame by using the $ sign, and the name of the variable (for example cyl (cylinders)):

```R
Data_Cars <- mtcars
Data_Cars$cyl


# output :
[1] 6 6 4 6 8 6 8 4 4 6 6 8 8 8 8 8 8 4 4 4 4 8 8 8 8 4 4 4 8 6 8 4
```
**Sort Variable Values**
```R
Data_Cars <- mtcars
sort(Data_Cars$cyl) 


# output :
[1] 4 4 4 4 4 4 4 4 4 4 4 6 6 6 6 6 6 6 8 8 8 8 8 8 8 8 8 8 8 8 8 8
```
**Analyzing the Data**

```R
Data_Cars <- mtcars
summary(Data_Cars) 


# output :
      mpg             cyl             disp             hp       
 Min.   :10.40   Min.   :4.000   Min.   : 71.1   Min.   : 52.0  
 1st Qu.:15.43   1st Qu.:4.000   1st Qu.:120.8   1st Qu.: 96.5  
 Median :19.20   Median :6.000   Median :196.3   Median :123.0  
 Mean   :20.09   Mean   :6.188   Mean   :230.7   Mean   :146.7  
 3rd Qu.:22.80   3rd Qu.:8.000   3rd Qu.:326.0   3rd Qu.:180.0  
 Max.   :33.90   Max.   :8.000   Max.   :472.0   Max.   :335.0  
      drat             wt             qsec             vs        
 Min.   :2.760   Min.   :1.513   Min.   :14.50   Min.   :0.0000  
 1st Qu.:3.080   1st Qu.:2.581   1st Qu.:16.89   1st Qu.:0.0000  
 Median :3.695   Median :3.325   Median :17.71   Median :0.0000  
 Mean   :3.597   Mean   :3.217   Mean   :17.85   Mean   :0.4375  
 3rd Qu.:3.920   3rd Qu.:3.610   3rd Qu.:18.90   3rd Qu.:1.0000  
 Max.   :4.930   Max.   :5.424   Max.   :22.90   Max.   :1.0000  
       am              gear            carb      
 Min.   :0.0000   Min.   :3.000   Min.   :1.000  
 1st Qu.:0.0000   1st Qu.:3.000   1st Qu.:2.000  
 Median :0.0000   Median :4.000   Median :2.000  
 Mean   :0.4062   Mean   :3.688   Mean   :2.812  
 3rd Qu.:1.0000   3rd Qu.:4.000   3rd Qu.:4.000  
 Max.   :1.0000   Max.   :5.000   Max.   :8.000
```
### R Max and Min
```R
Data_Cars <- mtcars
max(Data_Cars$hp)
min(Data_Cars$hp)


# output :
[1] 335
[1] 52
```
we can use the which.max() and which.min() functions to find the index position of the max and min value in the table:
```R
Data_Cars <- mtcars
which.max(Data_Cars$hp)
which.min(Data_Cars$hp) 


# output :
[1] 31
[1] 19 
```
Or even better, combine which.max() and which.min() with the rownames() function to get the name of the car with the largest and smallest horsepower:
```R
Data_Cars <- mtcars
rownames(Data_Cars)[which.max(Data_Cars$hp)]
rownames(Data_Cars)[which.min(Data_Cars$hp)] 


# output :
[1] "Maserati Bora"
[1] "Honda Civic"
```
### R Mean, Median, Mode

**R Mean**

To calculate the average value (mean) of a variable from the mtcars data set, find the sum of all values, and divide the sum by the number of values.
| 1.513 |	1.615 | 	1.835 | 	1.935 | 	2.140 | 	2.200 | 	2.320 | 	2.465 |
| -------- | ------- | -------- | ------- | -------- | ------- | -------- | -------  
| 2.620 | 	2.770 | 	2.780 | 	2.875 | 	3.150 | 	3.170 | 	3.190 | 	3.215 |
| 3.435 | 	3.440 | 	3.440 | 	3.440 | 	3.460 | 	3.520 | 	3.570 | 	3.570 |
| 3.730 | 	3.780 | 	3.840 | 	3.845 | 	4.070 | 	5.250 |  	5.345 | 	5.424 |

```R
Data_Cars <- mtcars
mean(Data_Cars$wt)

# output :
[1] 3.21725
```
**R Median**

The median value is the value in the middle, after you have sorted all the values.

If we take a look at the values of the wt variable (from the mtcars data set), we will see that there are two numbers in the middle: 

Note: If there are two numbers in the middle, you must divide the sum of those numbers by two, to find the median.

Luckily, R has a function that does all of that for you: Just use the median() function to find the middle value:
```R
Data_Cars <- mtcars
median(Data_Cars$wt)


# output :
[1] 3.325
```
**R Mode**

The mode value is the value that appears the most number of times.

R does not have a function to calculate the mode. However, we can create our own function to find it.

If we take a look at the values of the wt variable (from the mtcars data set), we will see that the numbers 3.440 are often shown:

```R
Data_Cars <- mtcars
names(sort(-table(Data_Cars$wt)))[1]


# output :
[1] "3.44"
```

R-Percentiles
---
Percentiles are used in statistics to give you a number that describes the value that a given percent of the values are lower than.

If we take a look at the values of the wt (weight) variable from the mtcars data set:

What is the 75. percentile of the weight of the cars? The answer is 3.61 or 3 610 lbs, meaning that 75% or the cars weight 3 610 lbs or less:
```R
Data_Cars <- mtcars
quantile(Data_Cars$wt, c(0.75))   # c() specifies which percentile you 


# output :
75% 
3.61
```
If you run the quantile() function without specifying the c() parameter, you will get the percentiles of 0, 25, 50, 75 and 100:
```R
Data_Cars <- mtcars
quantile(Data_Cars$wt) 


# output :
     0%     25%     50%     75%    100% 
1.51300 2.58125 3.32500 3.61000 5.42400
```
Quartiles are data divided into four parts, when sorted in an ascending order:

* The value of the first quartile cuts off the first 25% of the data
* The value of the second quartile cuts off the first 50% of the data
* The value of the third quartile cuts off the first 75% of the data
* The value of the fourth quartile cuts off the 100% of the data


Library
---
install library
```R
install.packages("x")
```
install more than 1 library At the same time
```R
install.packages(c("x", "y", "z"))
```
call library
```R
library(ggplot2)
```

Stringr-Library
---
```R
library(stringr)
a <- "hafez"
str_to_upper(a)   
str_to_lower(a)    
str_to_title(a)   
str_to_sentence(a) 


#output :  "HAFEZ"

#output :  "hafez"

#output :  "Hafez"

#output :  "Hafez"
```

MASS-Library
---
```R
library(MASS)
x <- 3.75
as.integer(x)


#output :  3
```
```R
library(MASS)
x <- 3.14159
round(x, 2)


#output :  3.14
```
```R
library(MASS)
x <- 5
as.double(x)


#output :  5
```
```R
library(MASS)
x <- 3.75
floor(x)


#output :  3
```
```R
library(MASS)
x <- 0.75
fractions(x)


#output :  3/4
```

pracma-Library
---
```R
#Calculations with degrees
Library(pracma)
a <- 90
sind(a)
cosd(a)
tand(a)


# output :
[1] 1
[1] 0
[1] Inf
```
```R
library(pracma)
a <- c(1, 2, 3)
b <- c(4, 5, 6)
cross(a, b)       # The cross product is the product of two three-dimensional vectors.


# output :
[1] -3  6 -3
```

R-table
---

```R
x <- c("A", "B", "A", "C", "B", "A", "C", "C")
table(x)


# output :
x
A B C 
3 2 3 
```
```R
y <- c(1, 2, 2, 3, 1, 1, 3, 2, 3, 3, 3)
table(y)


# output :
y
1 2 3 
3 3 5 
```
```R
gender <- c("Male", "Female", "Male", "Female", "Female", "Male", "Male")
passed <- c("Yes", "No", "Yes", "Yes", "No", "No", "Yes")
table(gender, passed)


# output :
       passed
gender  No Yes
Female  2   1
Male    1   3
```

purrr-Library
---
```R
library(purrr)
nested_list <- list(1, 2, list(3, 4, list(5, 6)))
flatten(nested_list)


# output :
[1] 1 2 3 4 5 6
```
```R
list_of_vectors <- list(c(1, 2), c(3, 4), c(5, 6))
flatten(list_of_vectors)


# output :
[1] 1 2 3 4 5 6
```

Read-file
---
### read.table

`read.table(file, header = TRUE/FALSE, sep = "", dec = ".", stringsAsFactors = FALSE)`

`file` → Address of the text file you want to read (e.g. `"data.txt"` or `"C:/Users/YourName/data.csv"`).

`header = TRUE/FALSE` → Specifies whether the file has the first row as column names:

* `TRUE` → The first row is the column names.

* `FALSE` → The first row is also considered as data.

`sep` → Separator between data:

* `""` (default) → Whitespace

* `","` → Comma (for CSV)

* `"\t"` → Tab (for TSV files)

`dec` → Decimal symbol (`"."` or `","` depending on the data format).

`stringsAsFactors = FALSE` → Prevents conversion of strings into `factors`.

```R
data <- read.table("data.txt", header = TRUE)

data <- read.table("data.csv", header = TRUE, sep = ",")

data <- read.table("data.tsv", header = TRUE, sep = "\t")
```
if your file is too big (csv) use this one :

```R
library(data.table)
data <- fread("data.csv")
```
### readLines

`readLines(con, n = -1, encoding = "UTF-8", warn = TRUE)`

`con` → Address of the text file you want to read (e.g. `"data.txt"` or `"C:/Users/YourName/data.txt"`).

`n` → Number of lines to read:

* `-1` (default) → The entire file is read.

* A specific number such as `n = 10` → Only the first 10 lines are read.

`encoding` → Specifies the encoding type (e.g. `"UTF-8"` or `"latin1"`).

`warn` → If `TRUE`, displays a warning if there are problems such as incomplete files.

read all in file :
```R
lines <- readLines("data.txt")
print(lines)
```
read just 5 line :
```R
lines <- readLines("data.txt", n = 5)
```
read data from URL :
```R
lines <- readLines("https://example.com/data.txt")
```
### read.csv
`read.csv(file, header = TRUE/FALSE, sep = ",", stringsAsFactors = FALSE)`

`file` → CSV file address (e.g. `"data.csv"` or `"C:/Users/YourName/data.csv"`).

`header = TRUE/FALSE` → Specifies whether the first row is the column names:

* `TRUE` (default) → The first row is treated as the column names.

* `FALSE` → The first row is also treated as data.

`sep = ","` → Specifies that the separator between values ​​is a comma (`,`).

`stringsAsFactors = FALSE` → To prevent strings (`character`) from being converted to factors (`factor`).

```R
data <- read.csv("data.csv", header = TRUE)

data <- read.csv("data.csv", header = FALSE)

data <- read.csv("data.csv", sep = ";", header = TRUE)

data <- read.csv("data.csv", header = TRUE, stringsAsFactors = FALSE)

data <- read.csv("data.csv", header = TRUE, nrows = 10)
```
### scan
`scan(file, what = list(type1, type2, ...), skip = 0, sep = "", quiet = FALSE)`

`file` → Address of the input file (e.g. `"data.txt"`). If the value is `""`, the data is read from the standard input (`stdin`).

`what` → The type of data to be read:

`numeric (0)` → numeric

`character ("")` → string

`integer (0L)` → integer

`logical (TRUE/FALSE)` → Boolean value

`list(0, "")` → A list of several data types

`skip = n` → Specifies how many lines of the first file to skip.

`sep = " "` → Specifies what the data separator is (e.g. `,` or `\t`).

`quiet = TRUE/FALSE` → If `TRUE`, the data reading messages are not displayed.

```R
data <- scan("numbers.txt")
print(data)
```

```R
data <- scan("words.txt", what = "")
print(data)
```

```R
data <- scan("mixed.txt", what = list(0, ""))
print(data)
```

```R
data <- scan("data.txt", what = "", skip = 2)     # The first 2 lines of the file are ignored.
```

```R
data <- scan("data.txt", what = "", sep = ",")
```

Write-File
---
### write.table
`write.table(x, file, sep = " ", row.names = TRUE, col.names = TRUE, quote = TRUE)`

`x` → The data to be saved (such as `data.frame` or `matrix`).

`file` → The path to the file where the data will be saved (e.g. "D:/data/output.txt").

`sep = " "` → The separator between values ​​(`" "` = space, `","` = comma for CSV, `"\t"` = tab for TSV).

`row.names = TRUE/FALSE` → Specifies whether to save row numbers.

`col.names = TRUE/FALSE` → Specifies whether to save column names.

`quote = TRUE/FALSE` → Specifies whether to enclose text values ​​in quotes (`" "`).

```R
write.table(women, "D:/data/women.txt", row.names = FALSE, col.names = TRUE)      # women is a built-in dataset in R that contains height and weight.
```
```R
write.table(women, "D:/data/women.csv", sep = ",", row.names = FALSE, col.names = TRUE)
```
### write.csv

`write.csv(x, file, row.names = TRUE, col.names = NA, quote = TRUE)`

`x` → The data set (`data.frame`) to be saved.

`file` → The address of the file where the data is saved (e.g. `"D:/data/output.csv"`).

`row.names = TRUE/FALSE` → Whether to save row numbers or not? Default is `TRUE`.

`quote = TRUE/FALSE `→ Whether to enclose text values ​​in quotes (`" "`)? Default is `TRUE`.

`col.names = NA` → In standard CSV, the first column is the row number by default. If `row.names = FALSE`, do not change the value of `NA`.

```R
write.csv(women, "D:/data/women.csv", row.names = FALSE)
```

```R
write.csv(women, "D:/data/women_with_rows.csv", row.names = TRUE)
```

```R
write.csv(women, "D:/data/women_no_quotes.csv", row.names = FALSE, quote = FALSE)
```



