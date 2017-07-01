---
title       : Problem Set 1 - Introduction to R
description : Insert the chapter description here


--- type:NormalExercise lang:r xp:100 skills:1 key:581d904f7c
## Warm up and vectors

Have a look at Task 1 a) from Problem Set 1. 

*** =instructions
Compute the following numbers with the corresponding R commands and store the results in the associated vector.

*** =hint
Und das steht unter hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}
# Calculate the square root of 798 and store the result in i
i <- 

# Calculate the absolute amount of - 9 and store the result in ii
ii <- 

# Calculate ten to the power of three and store the result in iii
iii <- 

# Calculate the square root of the log of 43 and store the result in iv
iv <- 
```

*** =solution
```{r}
# Calculate the square root of 798 and store the result in i
i <- sqrt(798)

# Calculate the absolute amount of - 9 and store the result in ii
ii <- abs(-9)

# Calculate ten to the power of three and store the result in iii
iii <- 10^3

# Calculate the square root of the log of 43 and store the result in iv
iv <- sqrt(log(43))
```

*** =sct
```{r}
# Test objects
test_object("i", incorrect_msg = "Something is wrong with the squared root of 798. Did you use the correct command?")
test_object("ii", incorrect_msg = "Something is wrong with the absolute amount of - 9. Did you use the correct command?")
test_object("iii", incorrect_msg = "Something is wrong with ten to the power of three. Did you use the correct command?")
test_object("iv", incorrect_msg = "Something is wrong with the squared root of the log of 43. Did you use the correct commands?")
success_msg("Nice work!")
```


--- type:NormalExercise lang:r xp:100 skills:1 key:c8ba91913a
## Warm up and vectors
Have a look at Task 1 b) from Problem Set 1. 

*** =instructions
Generate the variables with the corresponding variable names from the Task 1 b)


*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}
# Generate the variable u which contains 10.5
u

# Generate the variable v which contains 2
v 

# Generate w 


# Generate x 


# Generate y 


# Generate z


#####################################
check <- u + v + w + x + y + z


```

*** =solution
```{r}
check <- 207.0171
```

*** =sct
```{r}
# Test objects
test_object("check", incorrect_msg = "Something is wrong with the squared root of 798. Did you use the correct command?")
success_msg("Nice work!")
```
