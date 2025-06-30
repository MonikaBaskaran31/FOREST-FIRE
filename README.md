# 🔥 Forest Fire Burned Area Prediction

This project uses machine learning models to predict the **burned area of forest fires** in the northeast region of Portugal, based on meteorological and environmental data.

---

Project Overview:

The goal is to develop and evaluate regression models that can predict the extent of area burned in forest fires using a real-world dataset. The models used include:

- Random Forest Regressor
- Linear Regression
- Neural Network (Keras Sequential Model)

The project also compares model performance using metrics and REC (Regression Error Characteristic) curves.

---

Dataset:

- Source: UCI Machine Learning Repository – Forest Fires Dataset  
  https://archive.ics.uci.edu/ml/datasets/Forest+Fires

- Features include:
  - `X`, `Y`: spatial coordinates
  - `month`, `day`: temporal data
  - `FFMC`, `DMC`, `DC`, `ISI`: fire weather indexes
  - `temp`: temperature
  - `RH`: relative humidity
  - `wind`: wind speed
  - `rain`: rainfall
  - `area`: burned area (target variable)

---

Workflow:

1. Load and explore the dataset
2. Preprocess and normalize data
3. Train three models: Linear Regression, Random Forest, Neural Network
4. Predict and evaluate burned area
5. Plot REC curves to compare performance

---

Technologies Used:

- Python
- Pandas, NumPy
- Scikit-learn
- Keras (with TensorFlow backend)
- Matplotlib, Seaborn
- Jupyter Notebook

---

How to Run:

1. Clone the repository:
   git clone https://github.com/your-username/forestfire-prediction.git  
   cd forestfire-prediction

2. Install dependencies:
   pip install -r requirements.txt

3. Run the notebook:
   jupyter notebook ForestFire.ipynb

---

Future Improvements:

- Tune hyperparameters using GridSearchCV
- Try more complex models (e.g., Gradient Boosting)
- Visualize predictions geographically
- Export model for use in a web app or API

---

License:

This project is licensed under the MIT License.
