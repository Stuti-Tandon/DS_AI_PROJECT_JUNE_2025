<h1>What is CloudxLab?</h1>
-CloudxLab is an online, cloud-based learning platform/virtual lab designed for hands-on practice in technologies 
 like Big Data, Linux, Git, Data Science, and Data Engineering., Machine Learning, Deep Learning, DevOps.

 <h1>What is Data Science?</h1>
 - An interdisciplinary[field of study that combines knowledge, methods, and tools from multiple subjects to solve complex problems or understand topics more deeply.] field that uses 
1. Scientific methods  
2. Processes  
3. Algorithm  
4. Systems
   to extract knowledge and insights from many structured and unstructured data.
 - It involves the entire process of:
   1. Collecting data (from databases, APIs, sensors, etc.)
   2. Cleaning and preparing data (handling missing values, formatting)
   3. Analyzing data (using statistical models or algorithms)
   4. Visualizing results (graphs, dashboards, reports)
   5. Making predictions or decisions (using machine learning models)
- Data scientists use tools like Python, R, SQL, and platforms like Jupyter, Pandas, and scikit-learn to do this work.
- The goal is often to help businesses or organizations make better, data-driven decisions.

 <img width="586" height="545" alt="image" src="https://github.com/user-attachments/assets/e9a7ccdc-670a-4e70-94ba-a056237ac753" />

 
 <h1>What is Machine Learning?</h1>
 - A field in which you make a machine learn by itself using the data.
 - Field of study that gives "computers the ability to learn without being explicitly programmed."
- Basic Terms in Machine Learning:
1. Model: A mathematical function or algorithm that learns from data and makes predictions/decisions. It defines the relationship between input data (features) and the output (prediction).
2. Training Phase: When the model learns from data. During this phase, the model adjusts its internal parameters (like weights and biases) to minimize the difference between its predicted outputs and the actual values (minimize error).
     - Goal: The goal during training is to find the best values for the weights and biases that make the model's predictions as accurate as possible.
     - How it works: The model is provided with input-output pairs (training data). It tries to predict output for given input, calculates the error (the difference between predicted and actual and then adjusts its weights and biases to reduce this error.
3. Inference Phase: It happens after training. The model uses the learned parameters (weights and biases) to make predictions on new, unseen data.
4. Weights (W): Weights determine how strongly each input feature influences the output. Higher weights mean the feature has a stronger influence on the prediction.
5. Bias (b): Bias helps the model make predictions even when the input is zero. It allows the model to shift the output, making the model more flexible and accurate.
<br>
Example:
### 🔢 Given Data (Training Examples):
 x = 1, y = 3
 x = 3, y = 5
 Goal: Predict y when x = 5
1. Model
The model assumes a linear relationship between x and y:
y = W.x + b
This is the equation the model tries to learn.

2. Training Phase
We want to find values of W (weight) and b (bias) that best fit the training data.
#### Step 1: Use two known points
* Point A: (x_1 = 1, y_1 = 3)
* Point B: (x_2 = 3, y_2 = 5)
#### Step 2: Find slope (W)
W =(y_2 - y_1)/(x_2 - x_1) = {5 - 3}/{3 - 1} = 1
#### Step 3: Plug one point into the equation to find b
Using y = W.x + b and point A:
b= 2
### ✅ Learned Model:
y = 1.x + 2
### 3. Inference Phase
Now we use the learned model to predict y for a new x:
x = 5 ,y=7
### 4. Weights (W)
* W = 1: Each unit increase in x increases y by 1.
### 5. Bias (b)
* b = 2: Even if x = 0, the model predicts y = 2

 
