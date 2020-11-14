# Housing_Price_prediction_model
Thousands of houses are sold everyday. There are some questions every buyer asks himself like: What is the actual price that this house deserves?
Am I paying a fair price?

### I have Build a machine learning model to predict a house price based on Bangaluru Dataset.

Dataset: https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data

This Dataset has 9 attributes.

          1. area type: The area size mentioned in totals is “Built-up Area”,” Super built-up Area”, Plot Area” or “Carpet Area”
          
          2. availability: By when it will be ready
          
          3. location: Where is it located in Bengaluru
          
          4. size: in BHK
          
          5. Society: Name of society which it is part of
          
          6. total: area in square feet
          
          7. bath: Number of bathrooms
          
          8. balcony: Number of Balconies
          
          9. price: cost of property in lakhs
          
Data Cleaning on  Dataset.

          1. Drop Columns of 'area_type','availability','society' and 'balcony'.
          
          2. Drop NULL value row and row of size columns which are not in sqft.
          
          3. Some of the “Size” are in range form; we convert it into float form.
          
          4. Change the string form of the “Size “feature to float form.
          
          5. We assume If Count of unique location is Less than equal 10, we treat it as “Other” Location. In this technique we reduce no of features.
          
          6. Drop that rows whose total_sqft/BHK Less 300 . Assume it as a Threshold for 1 BHK
          
          7. Drop that row in which Number of Bathroom is greater then number of BHK+2.
          
Train Model on these Supervised Regression model

          ❑ Linear Regression
          
          ❑ Ridge Regression 
          
          ❑ Lasso Regression
          
          ❑ Polynomial Regression 
          
          ❑ Support Vector Regression
          
          ❑ Decision Tree Regression 
          
          ❑ Random Forest Regression
          
we take input from the user as “Location”,” total_sqft”,” bath” and “bhk” and corresponding our model
predict the price of the house. 

   Prediction : 1

       location = “2nd Phase Judicial Layout”

       sqft = 1000

       bathroom = 2

       BHK = 2

      Pass above input to Estimated_price function we get – 29.51 Lakhs Only

  Prediction : 2

       location = “1st Block Jayanagar”

       sqft = 1850

       bathroom = 10

       BHK = 10

       Pass above input to Estimated_price function we get – 269.6 Lakhs Only
       
 After Model development we make Front-End for ml model using HTML,CSS,Javascript and server using Flask
 
                       
 
