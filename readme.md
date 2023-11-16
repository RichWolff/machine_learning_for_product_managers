# Predicting the electrical energy output of a Combined Cycle Power Plant

What is a combined cycle power plant?: [Combined Cycle Power Plant Wikipedia Page](https://en.wikipedia.org/wiki/Combined_cycle_power_plant)

## Project Information

We have a set of 9568 hourly average ambient environmental readings from sensors at the power plant which we will use in our model.

The columns in the data consist of hourly average ambient variables:

- Temperature (T) in the range 1.81°C to 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in the range 25.36-81.56 cm Hg
- Net hourly electrical energy output (PE) 420.26-495.76 MW (Target we are trying to predict)

## Guidelines for the project

To complete the project, you must complete each of the below steps in the modeling process.  

1. For the problem described in the Project Topic section above, determine what type of machine learning approach is needed and select an appropriate output metric to evaluate performance in accomplishing the task.
2. Determine which possible features we may want to use in the model, and identify the different algorithms we might consider.
3. Split your data to create a test set to evaluate the performance of your final model.  Then, using your training set, determine a validation strategy for comparing different models - a fixed validation set or cross-validation.  Depending on whether you are using Excel, Python or AutoML for your model building, you may need to manually split your data to create the test set and validation set / cross validation folds.
4. Use your validation approach to compare at least two different models (which may be either 1) different algorithms, 2) the same algorithm with different combinations of features, or 3) the same algorithm and features with different values for hyperparameters).  From among the models you compare, select the model with the best performance on your validation set as your final model.
5. Evaluate the performance of your final model using the output metric you defined earlier.  

Once you have completed all steps, create and record a brief (5 minutes maximum) presentation video describing your approach to each step.  Your video must include a quick demo or screenshot of the final model you have created.  In your video, be sure to clearly address the 4 elements on which your presentation will be evaluated.
