# 🏠 Bangalore Home Price Prediction
A full-stack machine learning project to predict real estate prices in Bangalore, India, based on area (sqft), number of bedrooms (BHK), bathrooms, and location.

This project includes:
- A **machine learning model** trained using real estate data
- A **Flask API backend** to serve predictions
- A responsive **HTML/CSS/JavaScript frontend**
- All developed and tested using **PyCharm IDE**

---

## 📌 Project Highlights

- 🔧 Developed in **PyCharm**
- 🧠 Machine learning model using **scikit-learn**
- 🌐 RESTful API built with **Flask**
- 🖥️ Frontend built using **HTML**, **CSS**, and **JavaScript**
- 🏙️ Location-based dynamic prediction
- 📦 Modular file structure for easy maintainability

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Bangalore-Home-Price-Prediction.git
cd Bangalore-Home-Price-Prediction

2. Open in PyCharm

    Open the project folder (BHP/) in PyCharm

    Set up a virtual environment (PyCharm usually prompts you)

    Configure the server folder as a Python package (mark as "Sources Root" if needed)

3. Install Dependencies

Inside the PyCharm terminal or your venv:

pip install -r requirements.txt

🧠 Training the Model (Optional)

The trained model (.pickle) is already included in the artifacts/ folder.

But if you want to build it yourself:

1. Open model/bangalore_home_prices_model_building.ipynb in Jupyter or PyCharm's Scientific Mode

2. Run the cells to train and export:

3. banglore_home_prices_model.pickle

4. columns.json

🖥️ Running the App
1. Start the Flask Backend

cd server
python server.py

You should see:

Starting Python Flask Server For Home Price Prediction...
loading saved artifacts...done

2. Open Frontend in Browser

Open the file:

client/app.html

Double-click it or right-click → Open in Browser from PyCharm.
📁 Project Structure

Bangalore-Home-Price-Prediction/
│
├── client/             # Frontend (HTML/CSS/JavaScript)
│   ├── app.html
│   ├── app.css
│   ├── app.js
│   └── home_bg.jpg
│
├── server/             # Backend (Flask)
│   ├── server.py
│   └── util.py
│
├── artifacts/          # Model + metadata
│   ├── banglore_home_prices_model.pickle
│   └── columns.json
│
├── model/              # (Optional) Jupyter notebook for training
│   └── bangalore_home_prices_model_building.ipynb
│
├── requirements.txt    # Python dependencies
├── README.md
└── .gitignore


### please go to this url in your browser to see the result >> https://github.com/user-attachments/assets/56fafb8e-f542-47a3-9e9f-c37b755693fe     
