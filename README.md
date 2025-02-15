Yellow Taxi Trip Data Analysis - 2017
Project Overview
This project analyzes New York City's Yellow Taxi trip data from 2017 to uncover insights into trip distances, fares, passenger behaviors, and payment trends.

Using Python and popular data analysis libraries, we explore key patterns in taxi operations and customer behavior.

Dataset
The dataset used is 2017_Yellow_Taxi_Trip_Data, which contains records of taxi trips, including:

Trip details (distance, duration)
Fare components (total fare, tips, surcharges)
Payment methods
Passenger count
Key Variables in the Dataset
trip_distance → Distance traveled in miles

total_amount → Total fare paid, including tip and surcharges

payment_type → Encoded payment method:

1 = Credit card
2 = Cash
3 = No charge
4 = Dispute
5 = Unknown
6 = Voided trip
passenger_count → Number of passengers

tip_amount → Tip given by passengers

VendorID → Taxi company providing the trip

Project Goals & Analysis
1️⃣ Investigate Trip Distance & Total Amount

Sort trip_distance from highest to lowest and check if values are reasonable.
Sort total_amount and identify unusual values.
Compare both sorted results to analyze similarities or differences.
2️⃣ Analyze Payment Methods

Count how many trips used each payment_type.
Calculate the average tip for credit card and cash payments.
3️⃣ Vendor Performance Analysis

Count how many trips belong to each VendorID.
Compute the average total fare per vendor.
4️⃣ Passenger & Tip Behavior (Credit Card Payments Only)

Filter trips where payment_type = 1 (credit card).
Analyze passenger count vs. tip amount trends.
Technologies & Libraries Used
🔹 Python (Pandas, NumPy, Matplotlib, Seaborn)
🔹 Jupyter Notebook / Google Colab
🔹 SQL (Optional for advanced queries)

How to Run the Project
1️⃣ Download the dataset (2017_Yellow_Taxi_Trip_Data.csv).

2️⃣ Open Jupyter Notebook or Google Colab.

3️⃣ Load the dataset using Pandas:

python
Copy
Edit
import pandas as pd

df = pd.read_csv("2017_Yellow_Taxi_Trip_Data.csv")
4️⃣ Perform data cleaning and exploratory analysis.

5️⃣ Run the analysis scripts to generate insights.

Expected Insights
✅ Identify trends in trip distances and fare amounts.
✅ Understand customer behavior across different payment methods.
✅ Analyze tipping patterns based on passenger count.
✅ Evaluate vendor performance based on trip and fare data.
