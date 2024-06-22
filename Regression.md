### Linear Regression : Fitting a straight line to your data.
![image](https://github.com/iamsohel/machine-learning/assets/9135426/40ff3a42-a2d2-4c4a-a473-2a35edf2c26c)
![image](https://github.com/iamsohel/machine-learning/assets/9135426/eea1a4a2-6544-4081-b4fd-f2cd1ed8323a)

- x = input variable or feature

- y = output variable or target variable

- m = number of training examples

- (x,y)  = single training  example
- training set(features + targets) -> learning algorithm ->
- x -> f(model)-> y^
- for house price, size will input f is the model and price (estimation ) will be the output
- but how f will calculate. for now it will straight line
- how to representt f? fw,b(X) = wx +b or f(x)
- Linear regression with one variable(single features x or size)
- ![image](https://github.com/iamsohel/machine-learning/assets/9135426/b244c442-9188-4546-a63e-bb888434f809)
- In order to implement linear regression the first key step is first to define something called a cost function.
- **The cost function will tell us how well the model is doing so that we can try to get it to do better.**
- ![image](https://github.com/iamsohel/machine-learning/assets/9135426/8ae0094c-23dc-4d9b-b23f-89cd99f440d2)
- ![image](https://github.com/iamsohel/machine-learning/assets/9135426/fbd731ed-b54b-483b-b109-1ae76faa32bf)
- for linear regression, squared error cost function is mostly used
- ![image](https://github.com/iamsohel/machine-learning/assets/9135426/acd45127-6873-447d-be14-8ca78ee5c2f7)
- The cost function can be used to find the best parameters for your model
- ![image](https://github.com/iamsohel/machine-learning/assets/9135426/c1d4cbc2-2077-46a6-bbce-982a47083e03)
- ![image](https://github.com/iamsohel/machine-learning/assets/9135426/93ce8751-9bd1-4a7a-b8d6-1e9aad6dd26c)
- ![image](https://github.com/iamsohel/machine-learning/assets/9135426/64917089-b9aa-4642-9469-754924aa1ace)
- ![image](https://github.com/iamsohel/machine-learning/assets/9135426/6ef2211c-e8b1-44bc-bac0-33a6babc7d54)
- The goal of linear regression is to find the parameters w or w and b that results in the smallest possible value for the cost function J







