# multiple-regression-air-pollution
 The train data consists of five feature columns and one target column.All the feature columns are numeric and target value is also numeric.
 multiple regression is supervised learning technique.
 in this we have diffrent features with one goal ot the target values
 in our dataset we have diffrent types of things present in air
 we are going to predict the air contanimation of the test data according to the train data with its target values
 model will give the target values based on learning for testing data
 Goal-best values if the parameters(features)
 h(x)=sum(theta[i]*x[i]) in range(i=1 to n)
 loss function - Mean squared error 
  (1/2)*sum(h[x(i)]-y(i))**2 in range(i=1 to n)
 Goal-to minimize the loss using gradient descent
 theta=theta-n*(d(J[theta])/d[theta])- (diffrentiation method)
 (d(J[theta])/d[theta])=(h[theta(x)]-y)*x[j]
 n=learning rate
