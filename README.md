# ADL22

## 1. Introduction
### What is your MSE/MAE with linreg vs tuned network? 

### What happens to your train and test results if you add 5 hidden layers with 128 neurons each? 


## 2. Intro to Convolution Operations: Padding
### What is a response layer? (Give a brief, 1-sentence description)
A response layer is the resulting image from a filter.

### Given the filter shape of (26, 26, 32), what does each number represent?
The numbers represent the width and height of each filter, and number of filters, respectively.

### Given 6x6 input and filter of (3,3): what is the response shape that we get? 
The response shape is (4, 4).

### Given (33, 33, 1) input and filter of (2,2): what is the response shape that we get?
The response shape is (32, 32).

### What is the difference between ‘valid’ and ‘same’ padding? Given 6x6 input and filter of (3,3), what are the response shapes for both options? 
"Valid" padding is the default of no padding, whereas "same" padding automatically adds the amount of padding such that the response shape is the same as the input shape. For a 6x6 input and filter of (3, 3), the response shapes would be (4, 4) with "valid" padding" and (6, 6) with "same" padding.


## 3. Convolution Parameters: Stride and Pooling
### What is max pooling? (Give a brief, 1-sentence description)
Max pooling is a type of down-sampling wherein the output is the maximum of the applied filter.

### If I apply pooling of 2 (2,2 window with a stride of 2) to a (6,6) array, what is the resulting size?
The resulting size is (5, 5).


## 4. ConvNet Architectures, Layers
### Define I, O, F, S, P as used in this lecture (Give a brief, 1-sentence description)
I, O, F, S, and P represent the architecture of a CNN and stand for Input volume, Output, Filter, Stride, and Padding, respectively. The size of the output is based on the other elements listed.

### What is my output size if Input = (100, 100), kernel size=(2, 2), the stride of 1, and no pooling?
The output size is (99, 99).

### How many weights do I have if I have 24 such filters stacked (conv2_24)?


### Solve for the padding (P), in terms of I, F, and S, if we want the input and output size to remain the same. 


## 5. Practical Patterns
### What can we use the ImageDataGenerator for? What can it help us fight? (Give a brief, 1-sentence description)

### What is a better idea: To use one larger kernel (8,8) or multiple stacked smaller ones, 4x(2,2)? Why? Show the number of weights for each option. 

