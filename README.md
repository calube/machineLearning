Machine Learning
================

Definition of Machine Learning by Tom Mitchell

"A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E."

- Supervised Learning = teach the computer how to learn
    + "right answers" are given for each example in data
	+ classification probelem = predict discrete valued output
	+ regression = predict continuous/real-valued valued output 
	+ support vector machine allows an infinite number of features to be given as the "right answer"

    + Learning Regression in 1 variable with training set
        - m = number of training examples
        - x's = "input" variable/feature
        - y's = "output" variable/target variable
        - (x,y) = one training example
        - (x^(i),y^(i)) = ith training example

- Unsupervised Learning = let the computer learn by itself
    + no "right answers" are given for each example in data
    + clustoring of data
    + ex. clocktail party algorithm [W,s,v] = svd((repmat(sum(x.*x,1),size(x,1),1).*x)*x');

- TODO: Reinforcement Learning
- TODO: Recommender Systems