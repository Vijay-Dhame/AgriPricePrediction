My project is about predict the price of the commidate of india. In that we use the National Agricultural Market .
# Agricultural Commodity Price Prediction

## **Project Overview**
This project analyzes the price trends of agricultural commodities in India and predicts future prices using Machine Learning.

---

## **Project Setup**
### Steps to Run the Project:
1. **Clone the Repository (if applicable)**:
   ```bash
   git clone <https://github.com/Vijay-Dhame/AgriPricePrediction>
   cd <AgriPricePrediction>
   ```
2. **Install Dependencies**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. **Download the Dataset** (if not included):
   - The dataset contains agricultural commodity prices across Indian states.
   - Ensure the file `farm.csv` is placed in the project folder.

4. **Run the Python Script**:
   ```bash
   python agri_price_prediction.py
   ```

---

## **Datasets Used**
- **Source:** Agricultural Market Price Data (eNAM Portal) – National Agricultural Market 
- **File Name:** `Price_Agriculture_commodities_Week.csv.zip`
- **Key Features:**
  - `State`, `District`, `Market`, `Commodity`, `Arrival Date`, `Min Price`, `Max Price`, `Modal Price`.

---

## **Tools & Technologies**
- **Programming Language:** Python
- **Libraries Used:**
  - `pandas`, `numpy` → Data processing
  - `matplotlib`, `seaborn` → Data visualization
  - `scikit-learn` → Machine learning
- **IDE:** Google Colab / Jupyter Notebook / VS Code

---

## **Execution Instructions**
1. **Exploratory Data Analysis (EDA)**:
   - Run `agri_price_prediction.py` to generate visualizations.
   - Check for trends, correlations, and missing values.

2. **Train the Predictive Model**:
   - Uses **Linear Regression** to predict **modal prices**.
   - Splits dataset into **train & test sets**.

3. **Make Predictions**:
   - Enter **Min & Max Prices** as input.
   - The model predicts **Modal Price**.

4. **View Results**:
   - Model accuracy displayed using **Mean Absolute Error (MAE)** and **Root Mean Square Error (RMSE)**.
   - A scatter plot shows **actual vs predicted prices**.

---

## **Future Enhancements**
- Implement **LSTM (Deep Learning)** for better time-series predictions.
- Develop a **real-time API** for price prediction.
- Create a **mobile app** for farmers to access insights easily.

**🚀 This project helps farmers and traders make informed decisions using AI!**


