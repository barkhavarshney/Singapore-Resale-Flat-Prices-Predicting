# Singapore Resale FlatPrices Predicting
Using Data Wrangling, EDA, Model Building, Model Deployment


Introduction: The objective of this project is to develop a robust machine learning model and deploy it as a user-friendly online application to accurately predict the resale values of apartments in Singapore. This predictive model will leverage historical transaction data of resale flats, aiming to provide valuable insights for both prospective buyers and sellers in assessing the market value of a property post-resale. Factors influencing resale prices encompass various aspects such as location, property type, floor area, and lease duration. By furnishing customers with an estimated resale price based on these factors, the predictive model seeks to empower users in making informed decisions amidst the complexities of the real estate market.


**Data source**

Link: https://beta.data.gov.sg/collections/189/view


<details>
<summary>Installation Instructions</summary>

Before running this project, make sure you have the following dependencies installed:

- **Python**: 
  - Python is a high-level programming language widely used for various purposes.
- **pandas**:
  - pandas is a powerful Python library for data manipulation and analysis.
- **numpy**:
  - numpy is a fundamental package for scientific computing with Python, providing support for large multi-dimensional arrays and matrices, along with a collection of mathematical functions.
- **streamlit**:
  - streamlit is a Python framework used for rapidly building and sharing beautiful machine learning and data science web applications. It simplifies the process of creating interactive web apps.
- **scikit-learn**:
  - scikit-learn is a popular machine learning library for the Python programming language. It provides simple and efficient tools for data mining and data analysis, built on top of numpy, scipy, and matplotlib.

To install these dependencies, you can use the following command:

```bash
pip install pandas numpy streamlit scikit-learn
```
</details>

<details>
<summary>Project Workflow</summary>

The following is a fundamental outline of the project:

1. **Data Preparation**:
   - The Resale Flat Prices dataset consists of five distinct CSV files, each representing a specific time period ranging from 1990 to the present.
   - These CSV files need to be merged into a unified dataset to facilitate analysis.

2. **Data Preprocessing**:
   - Convert the data into a format suitable for analysis.
   - Perform any necessary cleaning and preprocessing procedures.
   - Extract relevant features such as town, flat type, storey range, floor area, flat model, and lease commence date.
   - Create any additional features that may enhance prediction accuracy.

3. **Model Construction**:
   - The objective is to construct a machine learning regression model using the decision tree regressor.
   - Train the model using the prepared dataset to accurately forecast the continuous variable 'resale_price'.

4. **Web Application Development**:
   - Develop a Streamlit webpage to serve as the user interface.
   - Allow users to input values for each column (features) and obtain the expected resale price value for flats in Singapore.

</details>

<details>
<summary>Using the application</summary>

**Resale Price Prediction**

To predict the resale price of a Singapore flat, follow these steps:

1. Select the "Predictions" option menu.
2. Fill in the following required information:
   - Street Name
   - Block Number
   - Floor Area (Per Square Meter)
   - Lease Commence Date
   - Storey Range
3. Click the "PREDICT RESALE PRICE" button.

</details>


