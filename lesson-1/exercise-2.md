## Exercise 2: Simple arithmetic

### Step 1:
Define a tensorflow constant with value 2 and assign it to variable **x** ([documentation](https://www.tensorflow.org/versions/r0.10/api_docs/python/constant_op/constant_value_tensors#constant)).

### Step 2:
Define a second constant with value 3 and assign it to variable **y**.

### Step 3:
Multiply x and y and store the result in z. Use the conventional * operator for multiplication.

### Step 4:
Take a look at what’s stored in each Python variable. You can do this by typing the variable name and pressing enter or using the print function. What is the information stored in x, y, and z?

### Step 5:
As you can see, we don’t have the result of 2 * 3 yet. In order to evaluate the expression, we need to run the graph. Use the same approach from Exercise 1 to run the graph. What should you use as the fetch value?

### Step 6:
The * operator is translated into the tensorflow multiply operation. Perform the same multiplication as you did in Step 3, but do so using the multiply operation explicitly ([documentation](https://www.tensorflow.org/api_docs/python/tf/multiply)). Note that you can give the operation a name.

### Step 7:
Run the graph again as you did in **Step 5** to verify the result.