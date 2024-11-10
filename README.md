# Customer Churn Prediction

This project is aimed at predicting customer churn for a telecom company using various machine learning algorithms. It provides insights into customer behavior and helps the company reduce churn by identifying at-risk customers.

## Project Overview

The **Customer Churn Prediction** project uses a dataset from a telecom company containing information about customers such as their contract type, services subscribed to, and usage statistics. The goal is to predict whether a customer will churn (i.e., leave the company) based on these features.

### Key Features:
- **CustomerID**: Unique identifier for each customer
- **Gender**: Customer's gender
- **SeniorCitizen**: Whether the customer is a senior citizen (1: Yes, 0: No)
- **Partner**: Whether the customer has a partner (Yes/No)
- **Dependents**: Whether the customer has dependents (Yes/No)
- **Tenure**: Duration of the customer's stay with the company (in months)
- **PhoneService**: Whether the customer has phone service (Yes/No)
- **MultipleLines**: Whether the customer has multiple lines (Yes/No)
- **InternetService**: Type of internet service (DSL/Fiber optic/No)
- **OnlineSecurity**: Whether the customer has online security (Yes/No)
- **OnlineBackup**: Whether the customer has online backup (Yes/No)
- **DeviceProtection**: Whether the customer has device protection (Yes/No)
- **TechSupport**: Whether the customer has tech support (Yes/No)
- **StreamingTV**: Whether the customer has streaming TV (Yes/No)
- **StreamingMovies**: Whether the customer has streaming movies (Yes/No)
- **Contract**: Type of contract (Month-to-month/One year/Two year)
- **PaperlessBilling**: Whether the customer has paperless billing (Yes/No)
- **PaymentMethod**: Payment method used (Electronic check, Mailed check, Bank transfer, Credit card)
- **MonthlyCharges**: Monthly charges for the customer
- **TotalCharges**: Total charges accumulated by the customer
- **Churn**: Whether the customer churned (1: Yes, 0: No)

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/Aikagra-rgb/Customer-Churn-Prediction.git
2. Navigate to the project directory:
bash
Copy code
cd Customer-Churn-Prediction
3. Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Alternatively, you can install the necessary libraries manually:

bash
Copy code
pip install pandas numpy scikit-learn seaborn matplotlib
Usage
1. Load and Preprocess the Data:
The load_and_preprocess() function reads the dataset, fills missing values in the TotalCharges column, and encodes categorical features into numerical values.


data, file_path = load_and_preprocess()
2. Perform Exploratory Data Analysis (EDA):
The perform_eda() function generates the following visualizations:

Churn distribution: Visualizes the number of customers who churned versus those who didn't.
Correlation Matrix: Shows the correlation between numerical features.
Monthly Charges vs Churn: Box plot to show the distribution of MonthlyCharges for churned vs non-churned customers.
Tenure vs Churn: A histogram that shows the tenure distribution based on churn status.

perform_eda(data)
3. Train and Evaluate Models:
This project supports the following machine learning models:

Random Forest
Logistic Regression
Support Vector Machine (SVM)
Gradient Boosting
Each model is trained and evaluated on the dataset. Accuracy and detailed classification reports are displayed for each model.

python
Copy code
train_and_evaluate_model(data)
4. GUI:
A simple graphical user interface (GUI) is provided to interact with the program. It allows users to:

Load and preprocess data
Perform EDA
Train and evaluate models
Run the following code to launch the GUI:


start_gui()
Contributing
Contributions are welcome! If you find any bugs or have ideas for improvements, feel free to fork the repository and create a pull request. Please make sure to write tests for any new features or bug fixes.



Acknowledgements
Thanks to the contributors of the dataset.
Thanks to the authors of the libraries used in this project, including scikit-learn, pandas, seaborn, and matplotlib.



---

### Explanation of Sections in the `README.md`:

1. **Project Overview**: A brief description of the project and its purpose. Mention the dataset and what the model predicts (customer churn).

2. **Features**: A list of features/columns in the dataset to give users insight into the data.

3. **Installation**: Instructions on how to clone the repository, install dependencies, and set up the environment.

4. **Usage**: This section explains how to run different functions of the project:
   - Load and preprocess data
   - Perform Exploratory Data Analysis (EDA)
   - Train and evaluate models
   - Run the GUI

5. **Contributing**: Encouragement for others to contribute to the project, including how to fork the repository and create pull requests.

6. **License**: The project license (e.g., MIT License) and link to the license file.

7. **Acknowledgements**: Thanking contributors or libraries used in the project.

---

### How to Finalize the `README.md`:

1. **Replace placeholders**: Make sure you replace any placeholders like `LICENSE` with actual references to files in your project.
2. **Push to GitHub**: After making these changes, follow the steps for adding, committing, and pushing the changes to GitHub, as outlined earlier.

---

Once you've followed these steps and added this `README.md` to your repository, your GitHub project will be more accessible and understandable to other users and developers!
