# What is machine learning
- Field of study that gives computers the ability to learn without  being explicitly programmed

## Machine learning Algorithm:
### Supervised Learning
- Learn from data labeled with the right answers
- Used most in real-world problem
- Supervised learning refers to the algorithm that learns x -> y or input to output mappings
- The key characteristic of supervised learning is you give your learning algorithm examples to learn from that include the right answer, the right answer means the correct label y for given input x
- Learn from being given the "right answer"
- When you give a new data, it will predict from the learning

  Input(X)        |       Output(Y)             |        Application
  
  email           |        spam?(0/1)           |        spam filtering
  
  audio            |       text transcripts      |       speech recognition
  
  add, user info   |       click?(0/1)            |       online advertising

- *Two Major Types of Supervised Learning*:
  - **Regression**(Predict a number from infinitely many possible outputs): Housing price prediction:
    - We can predict a housing price that has the dataset-like size in sqft and price in
  - **Classification**(predict category or class): Breast Cancer Detection
    - small finite number of possible outputs like 0,1 or 2 but not all like 1.2 or 1.6
    - two or more inputs
- Regression vs Classification?
### Unsupervised Learning
- Find something interesting in unlabeled data
- data with input x but not with output y
- No right answer will provide
- find some pattern /structure
- we call it unsupervised cause we don't supervise it with the correct data
- *Types of Unsupervised Learning*
  - **clustering**: Google News, DNA Microarray, Grouping customers
    - take the data without labels and try to group them into clusters
  - **Anomaly detection**: Find unusual data point like fraud detection in transaction
  - **Dimensionality reduction**: compress data using fewer numbers
#### Recommender systems
### Reinforcement learning
