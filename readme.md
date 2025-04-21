Final Project: Regression Analysis – Predicting Fuel Efficiency
Author: Huzaifa Nadeem
Date: April 21, 2025

This project explores regression techniques to predict a car’s fuel efficiency (measured in MPG) based on other numerical features like weight, horsepower, displacement, and more. Using the Auto MPG dataset from the UCI Machine Learning Repository, I trained multiple regression models and evaluated them using performance metrics like R² and RMSE. I also implemented and compared pipelines including polynomial regression.

📘 Project Files
📓 Final Notebook (regression_huzaifanadeem.ipynb)

📝 Peer Review

🧪 How to Run Locally
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/HuzaifaUCMO/ml_regression_huzaifanadeem.git
cd ml_regression_huzaifanadeem
Set Up a Virtual Environment:

bash
Copy
Edit
python -m venv .venv
Activate the Virtual Environment:

On Windows:

bash
Copy
Edit
.venv\Scripts\activate
On Mac/Linux:

bash
Copy
Edit
source .venv/bin/activate
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Notebook:

bash
Copy
Edit
jupyter notebook
Open regression_huzaifanadeem.ipynb in your browser and run the notebook.

📂 Dataset
The Auto MPG dataset is stored in the data folder. It includes features like:

Cylinders

Displacement

Horsepower

Weight

Acceleration

Model Year

Origin

Target variable: mpg