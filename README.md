# HorizonHome 🏡🔮

HorizonHome is a **machine learning-powered house price prediction** web application. This project uses a trained model to estimate California housing prices based on key features such as median income, house age, average rooms, and location coordinates.

---

## 🚀 Features
- **Predict House Prices** 📊 - Input housing features and get an estimated price.
- **Machine Learning Model** 🤖 - Uses a trained regression model.
- **Flask API Backend** 🏗️ - Handles predictions and serves the frontend.
- **User-Friendly Web Interface** 🎨 - Built with Bootstrap for a clean design.

---

## 📂 Project Structure
```
HorizonHome/
│-- static/          # Static files (CSS, JS)
│-- templates/       # HTML files (Frontend UI)
│-- best_model.pkl   # Trained ML model
│-- scaler.pkl       # Data scaler for preprocessing
│-- app.py           # Flask backend API
│-- model.ipynb      # Jupyter notebook for training
│-- README.md        # Project documentation
```

---

## 🛠️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ad1lhasan/HorizonHome.git
cd HorizonHome
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 🚦 Usage

### ▶️ Run the Flask App
```bash
python app.py
```
The app will start on **http://127.0.0.1:5000/**.

---

## 🔬 How It Works
1. The user enters housing features into the web form.
2. The data is **scaled using a pre-trained scaler**.
3. The machine learning model predicts the house price.
4. The predicted price is displayed on the screen.

---

## 📊 Model Details
- **Trained on:** California Housing Dataset 📍
- **Algorithm:** Linear Regression / Random Forest (mention which one you used)
- **Preprocessing:** Feature scaling using `scaler.pkl`

---

## 🤝 Contributing
Feel free to fork this repo, create a feature branch, and submit a pull request. Suggestions and improvements are always welcome! 🚀

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 📬 Contact
For any queries, reach out via:
📧 Email: muhammedadilhasan@gmail.com    

---

🚀 **Happy Coding & Predicting!**

