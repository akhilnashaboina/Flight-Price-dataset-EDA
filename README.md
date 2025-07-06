## ✈️ Flight Price Dataset – Exploratory Data Analysis (EDA)
This project explores a real-world flight price dataset to understand the key factors that influence airline ticket pricing. The goal is to perform detailed data cleaning, feature engineering, and visual analysis to uncover actionable insights that could be useful for travelers, airlines, or future machine learning models.

### 📂 Dataset Overview
The dataset contains various features related to flight bookings, including:

- Airline (e.g., IndiGo, Jet Airways)
- Date_of_Journey
- Source and Destination
- Route, Dep_Time, Arrival_Time
- Duration, Total_Stops, and Price

### 🛠️ Tools & Libraries Used
- Python (Jupyter Notebook)
- Pandas & NumPy – data manipulation
- Matplotlib & Seaborn – data visualization
- Scikit-learn (LabelEncoder) – categorical encoding

### 🔧 Key Steps Performed
#### Data Cleaning & Preprocessing
- Converted time/date strings into proper components (day, month, hour, minute).
- Handled missing values and inconsistent formatting.
- Standardized duration values and split into Duration_hour and Duration_min.

#### Feature Engineering
- Extracted meaningful numerical features from text-based fields:
-- Departure_hour, Arrival_hour, Duration_minutes, etc.
- Encoded categorical variables like Airline, Source, and Destination.

#### Exploratory Data Analysis (EDA)
- Visualized the distribution of prices and relationships with features like stops, duration, airline, and timing.
- Used correlation and group-by aggregations to identify influential factors.

### 📊 Key Insights
Airline Matters: Premium airlines like Jet Airways have higher average prices, while budget carriers like IndiGo and Air Asia are cheaper.

Stops Increase Cost: More layovers generally lead to higher prices; non-stop flights are cheaper.

Duration Affects Price: Longer flights tend to cost more, especially on multi-stop routes.

Timing Impacts Pricing: Early morning and late-night departures are generally cheaper. Mid-day and evening flights are more expensive.

Routes & Cities Influence Fare: Popular routes are more competitive and show more variation in pricing.

Date & Seasonality: Travel on weekends or holidays shows a noticeable price hike.

Additional Info Column: Rare values like “In-flight meal included” slightly raise ticket prices compared to “No info.”
