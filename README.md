Predicting Home Appliance Energy Use with Deep Learning
Ever wonder how much power your appliances consume based on your home environment? I tackled that exact question by analyzing time-series sensor data to forecast energy usage.

What's Inside
I worked with a synthetic dataset that mimics real-world home conditions:

Covers 5 months of 10-minute interval readings (Jan–May 2016)

Tracks appliance energy use (in Wh) alongside:

Temperature & humidity readings

Light levels

Weather data (windspeed, pressure)

Time-based patterns

Getting Started
Setup
Grab the code and install what you need:

bash
Copy
Edit
git clone https://github.com/NavinduKojitha/EnergyPredic.git  
pip install -r requirements.txt  
Run It
Fire up Jupyter or use Colab for zero-hassle testing:

bash
Copy
Edit
jupyter notebook Appliance_Energy_Prediction.ipynb
How I Approached the Problem
First, I Explored:

Cleaned up missing data

Spotted trends with heatmaps and time plots

Understood how features relate to energy use

Then, I Engineered:

Extracted useful time patterns (hourly/daily cycles)

Selected the most impactful features

Finally, I Predicted:
I tested three approaches:

Straightforward Linear Regression

Robust Random Forest

Sophisticated LSTM Neural Network

I measured success using:

MAE (how close my predictions were)

RMSE (penalizing big errors)

R² (how well I explained usage patterns)

What You’ll Get
A working energy prediction model

Clear comparisons of different techniques

Visual explanations of how well each method performs

Questions?
Reach out to me at:
Navindu Balasooriya
📧 navindukb@gmail.com

Let’s chat about saving energy with smart tech!
