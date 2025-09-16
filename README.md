# California-Housing-Regression-Analysis
This project explores how the `test_size` parameter affects the performance of a **Linear Regression model** trained on the **California Housing dataset**.   The work was carried out in Google Colab as part of a homework assignment.  # California House Prices - Effect of Test Size.

## Tools Used
- Google Colab (working environment)
- Scikit-learn (California Housing dataset & Linear Regression model)
- Matplotlib (visualization)

## My Contribution
- Running the code in Google Colab
- Testing the model with different `test_size` values (0.6 and 0.1)
- Recording and comparing the Mean Squared Error (MSE) results
- Generating "Actual vs Predicted" plots
- Writing a short interpretation of the results

## Results
- `test_size=0.6` → MSE ≈ 0.53  
- `test_size=0.1` → MSE ≈ 0.56  

Changing the proportion of the test set leads to small variations in model performance.  
A larger test set provides a more general evaluation of the model, while a smaller test set may result in slightly optimistic error values.

Visuals are in another tab. 
