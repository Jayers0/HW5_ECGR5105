
# HW 5 

## ECGR 5105 - Summer 2024

#### Joshua Ayers

#### SID: 801083470

#### Professor: Vinit Katariya

#### Github: https://github.com/Jayers0/HW5_ECGR5105

## Problem 1

1-A 
I genuinely dont remeber seeing this in the lecture and didnt see it in the notes. maybe i am dumb but i defined the model and filled is with random normally distributed data.

``` python
# Define the model
def model(t_u, w1, w2, b):
    return w2 * t_u *t_u + w1 * t_u + b
```

## Problem 2

### 2-A
I loaded the data and didnt need to do any meaningfull data manitpulation as all the data was numerical rather than categorical. I used the sklearn toolkit to standard scaler on the data before using the sklearn traning and test split.

### 2-B
I used the inbuilt Stocastic gradient decent tool to deal with 

### 2-C
at the best performing learning rate which was 0.0001


## Problem 3



### 3-A
I used sklearn tools to auto classify the categorical data called the OneHotEncoder for also the 

### 3-B


### 3-C