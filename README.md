## 🚗 Car Price Prediction App using Streamlit and Machine Learning

This project predicts the **price of a used car** based on various input features using a machine learning model and provides an **interactive web app interface** built with Streamlit.

---

### 🧾 Features

* Trained on real-world used car data
* Interactive user input via Streamlit
* Model caching for efficient loading
* Real-time prediction of car price
* Automatically handles one-hot encoded features

---

### 📊 Dataset Info

* **Source:** `car details v4.csv`
* **Columns Used:**

  * `Year`
  * `Price` (target variable)
  * `Kilometer`
  * `FuelType`
  * `SellerType`
  * `Transmission`
  * `Owner`

Categorical columns are handled via One-Hot Encoding (`get_dummies`).

---

### 🛠️ Technologies Used

* Python 🐍
* Streamlit
* Pandas, NumPy
* Scikit-learn
* Joblib

---

### 🚀 How to Run the App

#### 📌 Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
```

#### 📌 Step 2: Run the App

```bash
streamlit run app.py

### 🧠 How It Works

* Loads the dataset and performs data preprocessing
* Trains a **Linear Regression** model
* Saves the model and feature columns using Joblib
* Takes user input through the web interface
* Converts input to a valid format for prediction
* Outputs the estimated car price

---

### 🖼️ Sample Output

> ✅ *Estimated Car Price: ₹ 4,75,000*

---

### 🧰 Future Enhancements

* Add more regression models (XGBoost, Ridge, Lasso)
* Deploy to cloud (Streamlit Cloud, Heroku)
* Add image upload for car detection
* Improve UI/UX with CSS and layout tweaks

---

### 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

### 📬 Contact

**Author:** Sweta Kumari Jha
**GitHub:** \[https://github.com/Jha-Sweta]
