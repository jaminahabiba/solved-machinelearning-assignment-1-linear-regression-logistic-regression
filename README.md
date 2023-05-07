Download Link: https://assignmentchef.com/product/solved-machinelearning-assignment-1-linear-regression-logistic-regression
<br>
<strong>Assignment 1 – Linear Regression &amp; Logistic Regression </strong>

<strong><u>Part A:</u></strong><strong>  </strong>

The attached dataset <strong><em>“house_data.csv”</em></strong> contains 21613 records of house sale prices. It includes homes sold between May 2014 and May 2015.

<ul>

 <li>Apply Simple Linear regression with gradient descent to predict the <strong>price</strong> based on <strong>sqft_living</strong> (Square footage of the apartments interior living space).</li>

</ul>

Given the hypothesis function: <strong>Y = C<sub>1</sub> + C<sub>2</sub> X</strong>

<ul>

 <li><strong>(target variable) = Price, X (predictor) = sqft_living, C<sub>1 </sub>and C<sub>2</sub> are the parameters of the function. </strong></li>

</ul>




<ul>

 <li>Apply Multiple Linear regression with gradient descent to predict <strong>price</strong> based on <strong>5 predictors (grade, bathrooms, lat, sqft_living, view)</strong>.</li>

</ul>

Given the hypothesis function: <strong>Y = C<sub>1</sub> + C<sub>2</sub> X<sub>2</sub> + C<sub>3</sub> X<sub>3</sub> + C<sub>4</sub> X<sub>4</sub> + C<sub>5</sub> X<sub>5</sub> + C<sub>6</sub> X<sub>6</sub></strong>

<ul>

 <li><strong>(target variable) = Price, X (predictor) = </strong><strong>(grade, bathrooms, lat, sqft_living, view)</strong><strong>, C<sub>1</sub>, C<sub>2, </sub>C<sub>3,</sub> C<sub>4, </sub>C<sub>5 </sub>and C<sub>6</sub> are the parameters of the function.</strong></li>

</ul>

<ol>

 <li>Implement the gradient descent function to optimize parameters of the function.</li>

 <li>Calculate error function to see how the error of the hypothesis function changes with every iteration of gradient descent (hint: you will need to calculate error in every iteration) .</li>

 <li>Use optimized hypothesis function to make predictions on new data.</li>

 <li>Try different values of learning rate and see how this changes the accuracy of the model.</li>

</ol>




<strong><u>Part B:</u></strong><strong>  </strong>

The attached dataset <strong>“heart.csv”</strong> contain 303 records of patients have heart disease or not according to features in it. You are required to build <strong>Logistic Regression</strong> model using <strong>gradient descent</strong> to predict whether patient have heart disease or not <strong>(target) based on 4 predictors (trestbps, chol,  thalach, oldpeak). </strong>




<ol>

 <li>Implement the gradient descent function to optimize parameters of the function.</li>

 <li>Calculate error function to see how the error of the hypothesis function changes with every iteration of gradient descent(hint: you will need to calculate error in every iteration). c) Use optimized hypothesis function to make predictions on new data.</li>

 <li>d) Try different values of learning rate and see how this changes the accuracy of the model.</li>

</ol>

Machine Learning – [Fall 2020]




<strong><u>Important Notes:</u></strong>

<ul>

 <li>You can only use “pandas”, “numpy” and “matplotlib” libraries. <strong><em>(Don’t use “sklearn”)</em></strong></li>

 <li>The maximum number of students in a team is 3 and the minimum is 2.</li>

 <li>No late submission is allowed.</li>

 <li>Cheating students will take negative grades and no excuses will be accepted.</li>

</ul>


