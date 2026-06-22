 # Simple Linear Regression: Fertilizer vs. Crop Yield

A beginner-friendly Machine Learning project demonstrating how to build, train, and evaluate a Simple Linear Regression (SLR) model using Python and Scikit-Learn.

##  Project Overview
This project explores the relationship between the amount of fertilizer applied (in Kilograms) and the resulting crop yield (in Tons). Using historical data, we train a linear model to draw a "line of best fit" to predict future crop yields based on fertilizer input.

##  Key Insights & ML Concepts

* **The Scatter Plot:** Used initially to visualize the raw relationship between variables. It shows a strong, positive linear trend.
* **Line of Best Fit:** The goal of our model is to minimize the distance between the actual data points and this prediction line. Closer points mean higher accuracy.
* **R² Score (~0.997):** This metric tells us that over 99% of the variance in crop yield is explained by the fertilizer amount, indicating an exceptionally strong fit.

##  How to Run

**1. Clone this repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/SLR_Model_Fertilizer_vs_CropYield.git](https://github.com/YOUR_USERNAME/SLR_Model_Fertilizer_vs_CropYield.git)

 2. Install dependencies

     pip install -r requirements.txt

 3. Open and run the notebook in Google Colab or Jupiter Notebook.
      notebooks/Simple_Linear_Regression.ipynb.

# 4. Results

*Model Equation:* 
Yield = 0.05018 * FertilizerKg + 0.8000

*Prediction Example:*
For 110 kg of fertilizer, both the Scikit-Learn .predict() function and the manual mathematical formula yield an expected output of 6.32 Tons.

