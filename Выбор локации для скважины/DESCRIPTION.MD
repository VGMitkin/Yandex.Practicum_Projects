## Project. Search for profitable oil fields.
### Description of the project
The mining company GlavRosGosNeft needs to decide where to drill a new well.

Oil samples were provided in three regions: in each 10,000 fields, where the quality of oil and the volume of its reserves were measured. It is necessary to build a machine learning model that will help determine the region where mining will bring the greatest profit. Analyze possible profits and risks using the *Bootstrap.* technique

#### Steps to choose a location:

- In the selected region, they are looking for deposits, for each, the values of the signs are determined;
- Build a model and estimate the volume of reserves;
- Select the deposits with the highest value estimates. The number of fields depends on the company's budget and the cost of developing one well;
- The profit is equal to the total profit of the selected fields.

#### Conditions of the problem:
  - Only linear regression is suitable for training the model (the rest are not predictable enough).
  - When exploring a region, 500 points are explored.
  - The budget for field development is 10 billion rubles, the cost of drilling one well is 50 million rubles.
  - One barrel of raw materials brings 4,500 rubles of profit.
  - Do not consider regions where the risk of loss is higher than 2.5%. Of the remaining regions, the region with the highest average profit is selected.

### Content of the project
1. Exploring general information about the data
2. Model training for each region:
   2.1. Split the data into training and validation samples in a ratio of 75:25.
   2.2. Train the model and make predictions on the validation set.
   2.3. Preservation of predictions and correct answers on the validation set.
   2.4. Print on the screen the average stock of the predicted raw material and the RMSE of the model.
   2.5. Analyze the results.
3. Preparation for profit calculation:
   3.1. Save all key values for calculations in separate variables.
   3.2. Calculate enough raw materials to break even the development of a new well. Compare the volume of raw materials received with the average stock in each region.
4. Writing a function for calculating profit for selected wells and model predictions:
   4.1. Select wells with maximum prediction values.
   4.2. Sum the target value of the volume of raw materials corresponding to these predictions.
   4.3. Calculate the profit for the received volume of raw materials.
5. Calculate risks and profits for each region:
   5.1. Apply the Bootstrap technique with 1000 samples to find the profit distribution.
   5.2. Find the average profit, 95% confidence interval and risk of loss.
   5.3. Suggest a region for well development.
  
   ### Libraries used in the project:
- pandas
- Numpy
-Scipy
- SKlearn
