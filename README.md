# RealEstatePricePredictor :)
![Screenshot (188)](https://github.com/user-attachments/assets/6df39a09-6e03-4ca4-b204-1883582d829e)

# Real Estate Price Prediction Website

This project demonstrates building a real estate price prediction website using Bangalore home prices dataset from Kaggle. The project includes three main components: model building, Python Flask server, and a frontend website.

## Technologies and Tools Used
- Python
- Numpy and Pandas for data cleaning
- Matplotlib for data visualization
- Sklearn for model building
- Jupyter Notebook, Visual Studio Code, and PyCharm as IDEs
- Python Flask for HTTP server
- HTML/CSS/JavaScript for UI

## Step-by-Step Process

### Step 1: Model Building using Sklearn and Linear Regression

1. **Data Loading and Cleaning**
   - Load the dataset and perform data cleaning to handle missing values and remove duplicates.

2. **Feature Engineering**
   - Extract relevant features and convert categorical variables into numerical values using one-hot encoding.

3. **Outlier Detection and Removal**
   - Identify and remove outliers to improve model accuracy.

4. **Model Training**
   - Split the dataset into training and test sets.
   - Train a Linear Regression model using Sklearn.

5. **Model Evaluation**
   - Evaluate the model using metrics like R-squared and Mean Squared Error.

6. **Hyperparameter Tuning**
   - Use GridSearchCV to find the best hyperparameters for the model.

7. **Cross-Validation**
   - Perform K-Fold Cross-Validation to validate the model's performance.

8. **Save the Model**
   - Save the trained model for future use.

### Step 2: Building a Python Flask Server

1. **Setup Flask Server**
   - Install Flask and create a basic server to handle HTTP requests.
   - Load the saved model and set up an endpoint for predictions.

### Step 3: Building the Website

1. **Setup the Frontend**
   - Create an HTML form to accept user inputs for home features (e.g., square footage, bedrooms, bathrooms, location).
   - Use JavaScript to send a POST request to the Flask server and display the predicted price.

## How to Run the Project

1. **Model Building**
   - Run the Jupyter Notebook to build and save the model.

2. **Flask Server**
   - Run the Flask server to handle predictions.

3. **Frontend Website**
   - Open the HTML file in a web browser to interact with the prediction model.

## Conclusion

This project covers the end-to-end process of building a real estate price prediction website, demonstrating key data science and web development concepts.

## Additional Tip
** If u want to host the website,you can use aws Ec2 instance for final deployment ,using nginx server  :)
