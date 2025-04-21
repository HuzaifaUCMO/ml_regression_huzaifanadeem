# Final Project: Regression Analysis – Predicting Fuel Efficiency

**Author:** Huzaifa Nadeem  
**Date:** April 21, 2025

This project explores regression techniques to predict a car’s fuel efficiency (measured in MPG) based on numerical features like weight, horsepower, displacement, and more. Using the Auto MPG dataset from the UCI Machine Learning Repository, I trained multiple regression models and evaluated them using metrics like R² and RMSE. I also implemented and compared pipelines including polynomial regression.

---

## 📘 Project Files

- 📓 [Final Notebook (`regression_huzaifanadeem.ipynb`)](https://github.com/HuzaifaUCMO/ml_regression_huzaifanadeem/blob/master/regression_huzaifanadeem.ipynb)  
- 📝 [Peer Review (`peer_review.md`)](https://github.com/HuzaifaUCMO/ml_regression_huzaifanadeem/blob/master/peer_review.md)

---

## 🧪 How to Run Locally

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/HuzaifaUCMO/ml_regression_huzaifanadeem.git
   cd ml_regression_huzaifanadeem
   ```

2. **Set Up a Virtual Environment:**

   ```bash
   python -m venv .venv
   ```

3. **Activate the Virtual Environment:**

   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - On Mac/Linux:
     ```bash
     source .venv/bin/activate
     ```

4. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Notebook:**

   ```bash
   jupyter notebook
   ```

   Open `regression_huzaifanadeem.ipynb` in your browser and run the notebook.

---

## 📂 Dataset

The Auto MPG dataset is stored in the `data` folder. It includes features such as:

- Cylinders  
- Displacement  
- Horsepower  
- Weight  
- Acceleration  
- Model Year  
- Origin  

**Target variable:** `mpg`
