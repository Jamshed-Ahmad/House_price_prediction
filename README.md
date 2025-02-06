# 🏡 Mumbai House Price Prediction – Machine Learning Project

## 🔍 Project Overview <br>
This project aims to predict house prices in Mumbai using machine learning techniques. We implemented and compared Regression, Decision Tree, and Random Forest models, selecting the best-performing algorithm for accurate predictions. The final model is deployed as an interactive Gradio-based web application for real-time price estimation.

## 📌 Key Features <br>
✅ Exploratory Data Analysis (EDA) – Understanding trends, patterns, and distributions 📊 <br>
✅ Data Preprocessing – Handling missing values, encoding categorical features, and scaling numerical data 🛠 <br>
✅ Feature Selection – Choosing relevant features for optimal model performance 🏗 <br>
✅ Model Comparison – Evaluating Linear Regression, Decision Tree, and Random Forest models 🔄 <br>
✅ Best Model Selection – Random Forest Regressor performed the best with the highest accuracy 🎯 <br>
✅ Dynamic Feature Input – No predefined lists; values are picked directly from the dataset 🏷 <br>
✅ Gradio-Based Web Interface – User-friendly web app for real-time price prediction 💻 <br>

## 📂 Dataset & Features <br>
The dataset contains various attributes affecting house prices, including: <br>
| Feature Name | Description |
|--------------|-------------| 
Location | The area where the house is situated 🏙 <br>
BHK | Number of Bedrooms, Hall, Kitchen 🛏 <br>
Size(Sq.Ft.) | Total area of the house 📐 <br>
Bathroom | Number of bathrooms 🚿 <br>
Price | Target variable – House price in ₹ 💰 <br>

## 📊 Model Performance & Accuracy <br>
| Model | Accuracy (R² Score) |
|-------|---------------------|
Linear Regression | 67.5% <br>
Decision Tree | 78.3% <br>
Random Forest | 89.6% ✅ (Best Model) 

🔹 Random Forest Regressor achieved the highest accuracy (89.6%), making it the optimal choice for predictions. <br>

## 🚀 How to Run the Project <br>
### 1️⃣ Running the Jupyter Notebook
1. Open `Mumbai_Housing_price_project.ipynb` in Jupyter Notebook.
2. Run all cells to:
   - Perform data preprocessing and EDA.
   - Train and evaluate different regression models.
   - Compare accuracy metrics.

 ### 2️⃣ Install Dependencies 
 pip install `-r requirements.txt`. 

### 3️⃣ Run the Gradio App 
`python app.py`. <br>
or, if using Jupyter Notebook:
`!gradio app.py`. 

The Gradio interface will launch in your browser, allowing you to predict house prices dynamically. 

###🌟 Future Enhancements
🔹 Improve accuracy with advanced ensemble models 🏆.
🔹 Integrate real-time market trends 📈.
🔹 Deploy as a full-fledged web application 🌐.

### 📜 License
This project is open-source and free to use under the MIT License.

### 💬 Feedback & Contributions are welcome! Feel free to fork the repo, raise issues, or submit pull requests. 🚀

##📩 Connect with Me
If you found this project helpful, let’s connect on [LinkedIn](https://www.linkedin.com/in/jamshed-ahmad-1a8216278?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)! 😊



