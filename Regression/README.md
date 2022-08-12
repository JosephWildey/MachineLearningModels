# Models
## Simple Linear Regression
This model uses a single input to inferan outcome value based on a given value. For example, using the weight alone to determine the MPG of a car.
## Multiple Linear Regression
This model uses multiple inputs to infer an outcome value based on several given values. For example, use all of the physical features to determine the MPG of a car. Much more robust than single linear regression, but aside from considering more features is very similar mathematically.
## Polynomial Linear Regression
This model can use a single or multiple inputs to determine a likely result based on one or multiple values. In my experience this model tends to be pretty accurate when it is an n-degree model, where n is equal to the number of features. If the number of features is greater than 6, then you're probably safest sticking with a 6-degree polynomial to ensure it'll finish.
## Support Vector Regression
This model is similar to the first two, but ignores "errors" near the line of best fit. It can use a single input or multiple inputs to predict a final outcome value. 
## Decision Tree Regression
This model works best with multiple features to determine a single output. It is similar in structure to a binary search tree, and can be very accurate. However, it can also be very computationally intense to visualize.
## Random Forest Regression
This model also works best with multiple features to determine an output. It employs ensemble learning which is the idea of combining models and averaging out the results from those models on a random subset of inputs. It can also be very accurate.
# Metrics
## Adjusted R-Squared Score
This is the adjusted correlation of coefficient, and the closer it is to 1 the more accurate the model.
