# R-HandBook

## R Syntax

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


## R Comments

```R
"Hello World!" # This is a comment 


# output : "Hello World!"
```

## R Variables

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

## R Data Types

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
## What is Data Type
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
## Type Conversion
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
## R Input
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
## R Math
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
## R Strings
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

## R Booleans / Logical Values

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
## R Operators
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

## R If ... Else
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
## R - AND OR Operators
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
## R While Loop
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
## R For Loop

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
## R Functions
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
## R Vectors
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
## R Lists
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
## R Matrices
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





