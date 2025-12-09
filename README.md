# Customer-Shopping-Behaviour-Analysis
I recently completed a detailed Customer Shopping Behaviour Analysis project using Python and Pandas, where I explored a dataset of 3,900+ customer records to understand purchasing trends, preferences, and spending patterns.  I’m excited to continue building more projects like this and would love your feedback or suggestions!
📘 README.md (with image/graph placeholders)

You can directly paste this into your GitHub repository.

📊 Customer Shopping Behaviour Analysis

A complete end-to-end Data Cleaning, Feature Engineering & EDA Project


(optional — replace with your own banner image)

📁 Project Overview

This project analyzes a dataset of 3,900 customer shopping records to uncover insights into demographics, purchasing behaviors, spending trends, and customer review patterns.

The dataset contains details like:

Customer age, gender, location

Items purchased & categories

Purchase amount

Review ratings

Shipping type & discount usage

Payment method

Purchase frequency

The project involves:
✔ Data Cleaning
✔ Handling Missing Values
✔ Feature Engineering
✔ Exploratory Data Analysis (EDA)

🧹 1. Data Cleaning

Cleaned messy column names such as
_c_u_s_t_o_m_e_r___i_d_ → customer_id

Converted all column names to snake_case

Identified and corrected anomalies in frequency values

Removed redundant column (promo_code_used)

Handled inconsistent purchase frequency representations

🛠 2. Handling Missing Values

Only one column, Review Rating, had 37 missing values.
These were imputed using:

Category-wise median

Category-wise mean (to smooth distribution)

Final dataset → 0 missing values

⚙️ 3. Feature Engineering
🔹 Age Group

Created age segments using quantile-based binning:

Young Adult | Adult | Middle-aged | Senior

🔹 Purchase Frequency (Days)

Mapped text frequencies to numeric values:

Weekly → 7

Fortnightly → 14

Annually → 365

Every 3 Months → 90

This enabled numeric analysis of purchase cycles.

📈 4. Exploratory Data Analysis (EDA)

Below are samples of graphs you can include (replace file names):

🧮 Category Distribution

⭐ Review Rating Distribution

🧑‍🤝‍🧑 Age Group vs Purchase Amount

🌈 Color Popularity

🚚 Shipping Type Usage

🔍 Key Insights

✔ Clothing is the most purchased category
✔ Review Ratings mostly fall between 3.0 and 4.4
✔ PayPal is the most frequently used payment method
✔ Discount usage is present in all promo code cases
✔ Young Adults & Middle-aged groups dominate purchases
✔ Shipping preference varies widely across customers

📂 Final Dataset Columns
customer_id
age
gender
item_purchased
category
purchase_amount
location
size
color
season
review_rating
subscription_status
shipping_type
discount_applied
previous_purchases
payment_method
frequency_of_purchases
age_group
purchase_frequency_days

🧰 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/<your-username>/customer-shopping-analysis


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook

🙌 Feedback & Contributions

Feel free to suggest improvements, report issues, or open pull requests.
I’m actively learning and improving my data analysis skills!

✔ GitHub Project Description (Short)

Customer Shopping Behaviour Analysis using Python
A complete EDA project involving data cleaning, missing value imputation, feature engineering (Age Groups & Purchase Frequency Days), and detailed visual analysis of customer purchase trends.

🏷 Recommended GitHub Tags
python
pandas
data-analysis
exploratory-data-analysis
eda
feature-engineering
data-cleaning
machine-learning
retail-analytics
customer-behavior
visualization
jupyter-notebook

💬 Commit Message (for your final version)
Added complete data cleaning, feature engineering (age groups & purchase frequency), fixed column na
