# RegressionModels
This is a collaboration for 2 diffrent Regression models (Linear regression and logisitc regression) in the Supervised Learning course in FCAI-CU.

## Authors
- Roaa Fathi Nada                 20210140
- Selsabeel Asim Ali Elbagir      20210714

## Assignment Description
This project explores two fundamental regression models:

**1. Linear Regression:**

This section focuses on understanding and implementing linear regression. Here, you'll:

  * Define a univariate linear equation (e.g., Y = WX + C)
  * Select five distinct X values (X1, X2, X3, X4, X5) and calculate their corresponding Y values.
  * Use the calculated X and Y values as training data.
  * Apply the Mean Squared Error (MSE) technique to determine the equation of the best-fit line for the training data. Compare this result to your originally defined equation.
  * Assess the model's suitability by ensuring a positive output for Class 1 and a negative output for Class 2.
  * Repeat the above steps, introducing controlled noise to the equation to simulate real-world data variability.

**2. Logistic Regression (Classification):**

This section delves into logistic regression for classification tasks. Here, you'll:

  * Utilize the Iris dataset, where samples from C2 and C3 will be combined to form a new class, C2.
  * Split the C1 class into two sets: 40 samples for training and 10 samples for testing.
  * Further split the new C2 class into 80 samples for training and 20 samples for testing.
  * Train a logistic classifier using the Mean Squared Error (MSE) technique (note: while MSE is typically used for regression, this might be a placeholder here; consider verifying the appropriate loss function for logistic regression).
  * Define the model's output convention: positive for Class 1 and negative for Class 2.
  * Evaluate the model's performance on the test samples by classifying them as Class 1 or the other class (depending on the actual class distribution).

