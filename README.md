# R-HandBook

## R Syntax

```
"hello world"

[1] "hello world"
```

```
1

[1] 1
```

```
5 + 5

[1] 10
```
### print

```
print("Hello World!")

[1] "Hello World!"
```

```
for (x in 1:10) {
  print(x)} 

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
```
**sprintf**
```
a = 12.3
sprintf("The value of a is: %f", a)


[1] "The value of a is: 12.300000"
```
**paste**

```
paste("Hello", "World")


[1] "Hello World"
```

```
text <- "awesome"
paste("R is", text)

[1] "R is awesome"
```
```
paste("Hello", "World", sep = "-")


[1] "Hello-World"
```

```
words <- c("apple", "banana", "cherry")
paste(words, collapse = ", ")


[1] "apple, banana, cherry"
```

**past0**

```
paste0("Hello", "World")


[1] "HelloWorld"
```

**cbind**

```
a <- c(1, 2, 3)
b <- c(4, 5, 6)
cbind(a, b)


     a b
[1,] 1 4
[2,] 2 5
[3,] 3 6
```

```
x <- c(10, 20, 30)
y <- c(40, 50, 60)
z <- c(70, 80, 90)
result <- cbind(x, y, z)
print(result)


     x  y  z
[1,] 10 40 70
[2,] 20 50 80
[3,] 30 60 90
```

```
mat1 <- matrix(1:6, nrow = 3, ncol = 2)
mat2 <- matrix(7:12, nrow = 3, ncol = 2)
cbind(mat1, mat2)


     [,1] [,2] [,3] [,4]
[1,]    1    4    7   10
[2,]    2    5    8   11
[3,]    3    6    9   12
```

```
gender <- factor(c("Male", "Female", "Male"))
age <- c(25, 30, 22)
result <- cbind(gender, age)
print(result)


     gender age 
[1,] "Male"   "25"  
[2,] "Female" "30"  
[3,] "Male"   "22"
```


## R Comments

```
"Hello World!" # This is a comment 

[1] "Hello World!"
```

## R Variables

```
name <- "John"
age <- 40
name
age

[1] "John"
```

```
name <- "John Doe"
print(name)

[1] "John"
[1] 40
```

### R Multiple Variables

```
var1 <- var2 <- var3 <- "Orange"
var1
var2
var3 

[1] "Orange"
[1] "Orange"
[1] "Orange"
```


## R Data Types

```
my_var <- 30                # my_var is type of numeric
my_var <- "Sally"           # my_var is now of type character (aka string) 
```

**Basic Data Types :**

numeric

```
x <- 10.5
class(x)


[1] "numeric"
```
```
a <- NaN
class(a)


[1] "numeric"
```

integer

```
x <- 1000L
class(x)


[1] "integer"
```

