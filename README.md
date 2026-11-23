# Hotel-Bookings-EDA-and-Preprocessing

## About the Project

This project is based on the Hotel Booking Demand dataset. Our main goal is to explore the dataset, understand the patterns behind hotel bookings and cancellations, and prepare the data for a Machine Learning classification task.

We have worked on different stages of data preprocessing, starting from understanding and cleaning the data to encoding, scaling, handling class imbalance, and selecting relevant features.

The project is divided into five sections, with each team member responsible for a particular part of the workflow.

## What We Worked On

### 1. Data Understanding & Exploratory Data Analysis (EDA)
**Ashmi Fathima S**

- Loading the dataset and understanding its structure.
- Checking columns, data types, and basic statistical information.
- Identifying and handling missing values.
- Checking and removing duplicate records.
- Performing univariate and bivariate analysis.
- Creating visualizations to understand patterns and relationships.
- Identifying the target variable.

### 2. Feature Separation & Train-Test Split
**Gokul R.S**

- Separating independent features (X) and the target variable (y).
- Preparing the dataset for training and testing.
- Splitting the data into training and testing sets.
- Using stratification to maintain the target variable's class distribution.
- Separating numerical and categorical features for further preprocessing.

### 3. Numerical Feature Preprocessing
**Harisanker S Paleri**

- Handling missing values in numerical columns.
- Identifying outliers using boxplots and the IQR method.
- Treating outliers using clipping.
- Applying StandardScaler to numerical features.
- Making sure the scaling process is fitted on training data and applied to testing data.

### 4. Categorical Encoding
**Arya R.B**

- Identifying categorical features.
- Applying One-Hot Encoding to categorical columns.
- Handling unknown categories.
- Encoding the target variable using Label Encoding.
- Combining the processed numerical and categorical features.

### 5. Class Imbalance & Feature Selection
**Mahadevan M**

- Checking the distribution of the target variable.
- Handling class imbalance using SMOTE.
- Performing correlation analysis.
- Checking feature importance using Mutual Information.
- Selecting relevant features.
- Verifying the final processed datasets.

## Tools & Libraries Used

We used Python and the following libraries throughout the project:

- **Pandas** – For working with and analysing the dataset.
- **NumPy** – For numerical operations.
- **Matplotlib** – For creating visualizations.
- **Seaborn** – For statistical plots and data visualization.
- **Scikit-learn** – For data splitting and preprocessing.
- **Imbalanced-learn** – For handling class imbalance using SMOTE.
- **Google Colab** – For writing and executing the notebook.
- **GitHub** – For maintaining the project and collaborating as a team.

## Dataset

We used the Hotel Booking Demand dataset, which contains information about hotel reservations, including booking details, customer information, length of stay, arrival dates, distribution channels, and cancellation status.

Our target column is `is_canceled`:

- `0` – Booking was not canceled.
- `1` – Booking was canceled.

## Project Workflow

Our preprocessing workflow follows this order:

1. Load and understand the dataset.
2. Perform data cleaning and exploratory data analysis.
3. Separate features and target variable.
4. Split the data into training and testing sets.
5. Handle missing numerical values and outliers.
6. Scale numerical features.
7. Encode categorical features.
8. Handle class imbalance using SMOTE.
9. Perform correlation analysis and feature selection.
10. Verify the final processed data.

## Team Members

This project was completed through the combined efforts of five members:

| No. | Name | Responsibility |
|---|---|---|
| 1 | Ashmi Fathima S | Data Understanding & EDA |
| 2 | Gokul R.S | Feature Separation & Train-Test Split |
| 3 | Harisanker S Paleri | Numerical Preprocessing |
| 4 | Arya R.B | Categorical Encoding |
| 5 | Mahadevan M | Class Imbalance & Feature Selection |

## How to Run

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

3. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.
4. Make sure the dataset is available and update its file path if required.
5. Run the notebook cells in order.

## Current Project Status

We have completed the data analysis and preprocessing stages. The final notebook brings together the work done by all five team members.

The focus of this project is on preparing the dataset for a Machine Learning classification task. Model training and evaluation are outside the scope of this current notebook.

---

**A collaborative Machine Learning project by Team.**
