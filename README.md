🏠 Predicting Home Appliance Energy Use with Deep Learning

Ever wonder how much power your appliances consume based on your home environment?
I tackled that exact question by analyzing time-series sensor data to forecast energy usage using deep learning and traditional ML methods.

📊 Dataset Overview
I worked with a synthetic dataset that mimics real-world home conditions:

5 months of 10-minute interval readings (Jan–May 2016)
Tracks appliance energy use (in Wh) alongside:

Temperature & humidity readings

Light levels

Weather data (windspeed, pressure)

Time-based patterns

🚀 Getting Started
🔧 Setup
Clone the repo and install dependencies:

bash
Copy
Edit
git clone https://github.com/NavinduKojitha/EnergyPredic.git
cd EnergyPredic
pip install -r requirements.txt
📂 Run the Notebook
You can use Jupyter or Google Colab:

bash
Copy
Edit
jupyter notebook Appliance_Energy_Prediction.ipynb
🔍 My Approach
1. Explore
Cleaned up missing data

Spotted trends using heatmaps and time plots

Understood how features relate to energy usage

2. Engineer
Extracted time-based patterns (hourly/daily cycles)

Selected the most important features

3. Predict
Tested three models:

Linear Regression – simple and interpretable

Random Forest – robust and non-linear

LSTM Neural Network – deep learning for sequential patterns

📈 Evaluation Metrics
MAE – Mean Absolute Error

RMSE – Root Mean Squared Error

R² Score – how well I explained energy usage variance

🧠 What You’ll Learn
Build a practical time-series prediction pipeline

Compare ML and DL models on real-world problems

Visualize and interpret prediction accuracy

📬 Contact
Navindu Balasooriya
📧 navindukb@gmail.com

Let’s connect and talk about energy efficiency through smart technology!
