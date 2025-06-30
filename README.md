**Predicting Home Appliance Energy Use with Deep Learning**
Ever wonder how much power your appliances consume based on your home environment? This project tackles that exact question by analyzing time-series sensor data to forecast energy usage.

What's Inside
We're working with a synthetic dataset that mimics real-world home conditions:

Covers 5 months of 10-minute interval readings (Jan-May 2016)

Tracks appliance energy use (in Wh) alongside:

Temperature & humidity readings

Light levels

Weather data (windspeed, pressure)

Time-based patterns

Getting Started
Setup
Grab the code and install what you need:

bash
git clone [repo-url]
pip install -r requirements.txt
Run It
Fire up Jupyter or use Colab for zero-hassle testing:

bash
jupyter notebook Appliance_Energy_Prediction.ipynb
How I Approach the Problem
*First, I Explore

Clean up missing data

Spot trends with heatmaps and time plots

Understand how features relate to energy use

*Then We Engineer

Extract useful time patterns (hourly/daily cycles)

Select the most impactful features

*Finally, I Predict
Test three approaches:

Straightforward Linear Regression

Robust Random Forest

Sophisticated LSTM Neural Network

I measured success using:

MAE (how close our guesses are)

RMSE (penalizing big errors)

R² (how well i explain usage patterns)

What You'll Get
A working energy prediction model

Clear comparisons of different techniques

Visual explanations of how well each method performs

Questions?
Reach out to me at:
[Navindu Balasooriya]
[navindukb@gmail.com]

Let's chat about saving energy with smart tech!