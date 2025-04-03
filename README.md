# ReCell-Supervised-Learning-Foundations-Project

### Business Context

Buying and selling used phones and tablets used to be something that happened on a handful of `online marketplace sites`. But the market has grown considerably over the past decade, and a new IDC (International Data Corporation) forecast predicts that the used phone market would be worth \\$52.7bn by 2023 with a compound `annual growth rate (CAGR) of 13.6% from 2018 to 2023`. This growth can be attributed to an uptick in demand for used phones and tablets that offer considerable savings compared with new models.
**`Refurbished and used devices`** continue to provide `cost-effective alternatives` to both consumers and businesses that are looking to save money when purchasing one. There are plenty of other benefits associated with the used device market. Used and refurbished devices can be sold with warranties and can also be insured with proof of purchase. Third-party vendors/platforms, such as Verizon, Amazon, etc., provide attractive offers to customers for refurbished devices. Maximizing the longevity of devices through second-hand trade also reduces their environmental impact and helps in recycling and reducing waste. The impact of the COVID-19 outbreak may further boost this segment as consumers cut back on discretionary spending and buy phones and tablets only for immediate needs.

**`ReCell, a startup company`** in `Refurbished and used devices` aiming to tap the potential in this market by providing cost-effective alternatives to it's consumers.
The dataset we have analyzed here consists of **`approx 3500 used device details`**. They contains informations about `screen size, brand, os ,rear and selfie camera, ram , internal memory , device age(number of days used by consumer), release year, weight, type of network support (4g or 5g) , normalized used and new price` of used phones/tablets. 

### Objective

The growing demand and untapped potential of this emerging market highlight the need for an `ML-driven solution` to develop a `dynamic pricing strategy` for `used and refurbished devices`.
This project focuses on analyzing the provided data and **`building a linear regression model`** to **`predict the price of used phones and tablets`**, while identifying key factors that significantly impact pricing

### Model Building Approach
As a Data Scientist,
1. I explored the dataset to understand its **`shape, size, data types, missing values, duplicates, and statistical summary`**.
2. Conducted **`Exploratory Data Analysis (EDA)`** to identify patterns and correlations among features influencing the price of used phones and tablets.
3. `Data Preprocessing:` Cleaned and processed data by handling `missing values, outliers, and feature scaling` to ensure high-quality input for model training.
4. `Model Building:` Built a **`Linear Regression model`** to predict device prices, employing techniques to select relevant features and improve model accuracy.
5. `Model Evaluation: `The model explained **`~84% of the variance`** in the data and showed a **`4.5% normalized error on test data`**, proving its effectiveness for both prediction and inference purposes.
6.  Provided actionable insights on factors significantly impacting device pricing and recommendation to the business to `optimizing pricing strategies` to boost their revenue.

### Data Description

The data contains the different attributes of used/refurbished phones and tablets. The data was collected in the year 2021. The detailed data dictionary is given below.

- `brand_name:` Name of manufacturing brand
- `os:` OS on which the device runs
- `screen_size:` Size of the screen in cm
- `4g:` Whether 4G is available or not
- `5g:` Whether 5G is available or not
- `main_camera_mp:` Resolution of the rear camera in megapixels
- `selfie_camera_mp:` Resolution of the front camera in megapixels
- `int_memory:` Amount of internal memory (ROM) in GB
- `ram:` Amount of RAM in GB
- `battery:` Energy capacity of the device battery in mAh
- `weight:` Weight of the device in grams
- `release_year:` Year when the device model was released
- `days_used:` Number of days the used/refurbished device has been used
- `normalized_new_price:` Normalized price of a new device of the same model in euros
- `normalized_used_price:` Normalized price of the used/refurbished device in euros
