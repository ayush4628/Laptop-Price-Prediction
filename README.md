# 💻 Laptop Price Predictor

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)
[![ML](https://img.shields.io/badge/Machine%20Learning-Regression-green)]()
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

A Machine Learning-powered web application to predict laptop prices based on their specifications. Built with Python, trained on real-world laptop data, and deployed using Streamlit.

---

## 📌 Project Highlights

- ⚙️ Developed a regression model to predict laptop prices from key hardware features  
- 🧹 Cleaned and preprocessed real-world dataset for model training  
- 📊 Performed Exploratory Data Analysis (EDA) to find trends  
- 🧠 Engineered features like screen resolution, processor type, etc.  
- 🔍 Trained and evaluated models using scikit-learn pipelines  
- 🌐 Deployed the ML model in an interactive UI using Streamlit  

---

## 🔧 Tech Stack

- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn  
- **Modeling:** Linear Regression pipeline  
- **Deployment:** Streamlit (Web App)  
- **Tools:** Jupyter Notebook  

---

## 📁 Folder Structure

`laptop-price-prediction/` →  
`├── .ipynb_checkpoints/` – Notebook checkpoints  
`├── app.py` – Streamlit frontend  
`├── df.pkl` – Transformed dataframe used in prediction  
`├── pipe.pkl` – Trained model pipeline  
`├── Laptop_Price_Prediction.ipynb` – Model building & EDA notebook  
`├── requirements.txt` – Project dependencies  
`├── .gitignore` – Ignored files  
`├── LICENSE` – License file  
`└── README.md` – You're here!  

---

## 🚀 Run the Project Locally


# 1. Clone the repository
```bash
git clone https://github.com/your-username/laptop-price-prediction.git
cd laptop-price-prediction
```
# 2. Set up virtual environment (optional)
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

```
# 3. Install dependencies  
```bash
pip install -r requirements.txt
```

#  4. Run the Flask app  
```bash
streamlit run app.py
```
# 5. Open in browser or Postman  
Visit: http://localhost:5000/  
Enter laptop specs to get the predicted price.  

# 📊 Sample Input (JSON)  
```bash
{
  "Company": "HP",
  "TypeName": "Gaming",
  "Ram": "8GB",
  "Weight": "2.1",
  "Touchscreen": "No",
  "IPS": "Yes",
  "ScreenSize": "15.6",
  "Resolution": "1920x1080",
  "Cpu": "Intel Core i5",
  "HDD": "1TB",
  "SSD": "0",
  "Gpu": "Nvidia",
  "OpSys": "Windows 10"
}

```

# ✅ Sample Output  
```bash
{
  "predicted_price": "56,000 INR"
}
```

## 📈 Notebook Insights
-> Explore the Jupyter notebook Laptop_Price_Prediction.ipynb for:  
-> Data cleaning and feature transformation  
-> Exploratory Data Analysis (EDA)  
-> Model training and evaluation  
-> Pipeline creation and serialization  

## 🌟 Future Improvements  
->💡 Add model comparison between XGBoost, RandomForest, etc.  
->🌐 Create interactive frontend using Streamlit or React  
->📲 Deploy the app using Render, Vercel, or Heroku  
->🧠 Add explainability (e.g., SHAP values for feature importance)  

## 📜 License
This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details. 

## 🙏 Acknowledgments  
-> Kaggle laptop dataset  
-> scikit-learn documentation  
-> Flask community for deployment tips  

## 📬 Contact
📧 Email: [mauryaayush7377@gmail.com](mailto:mauryaayush7377@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ayush4628)
