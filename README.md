# IPL-PREDICTION
# 🏏 IPL Score Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-orange)
![Status](https://img.shields.io/badge/Project%20Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-blueviolet)
![Platform](https://img.shields.io/badge/Platform-Jupyter%20Notebook-yellow)

This project predicts the **final innings score** of an IPL cricket match using real-time match inputs. It leverages machine learning, encoded data, and an interactive user interface built using `ipywidgets`.

---

## 🚀 Features

✔️ Predicts final score based on current match context  
✔️ Encodes teams, venue, batsman, and bowler using saved LabelEncoders  
✔️ Scales input features for accurate predictions  
✔️ Interactive UI created using `ipywidgets`  
✔️ Uses a trained ML regression model for score forecasting  

---

## 🧠 Tech Stack

| Component       | Technology Used      |
|----------------|----------------------|
| Programming     | Python               |
| Machine Learning| Scikit-Learn         |
| UI Framework    | ipywidgets           |
| Data Processing | Pandas, NumPy        |
| Model Storage   | Joblib               |

---

## 📁 Project Structure
📦 IPL-Score-Prediction
│
├── README.md               # Complete documentation of the project
│
├── Untitled.ipynb          # Temporary / experimental notebook (optional)
│
├── ipl prediction.ipynb    # Main notebook containing UI, model loading & score prediction
│
└── ipl_data.csv            # Dataset used for training and feature engineering

---


---

## 📁 Dataset

The file **`ipl_data.csv`** contains IPL ball-by-ball level data including:

- Venue  
- Batting team  
- Bowling team  
- Batsman, Bowler  
- Overs, Runs, Wickets  

This dataset is preprocessed to train the score prediction model.

---

## 🔧 How It Works

1️⃣ User selects: Venue, Batting team, Bowling team, Striker, Bowler, Runs, Wickets, Overs  
2️⃣ Inputs are label-encoded and scaled using saved encoders & scaler  
3️⃣ ML model predicts the **final total score** for the innings  

---

## ▶️ How to Run

Install dependencies:

```bash
pip install -r requirements.txt
🏁 Sample Output

After selecting the match details and clicking Predict Score, the output appears like:

Predicted Total Runs: 183
🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and raise a pull request.

⭐ Support

If you found this project useful, please give it a ⭐ star on GitHub — it really helps!

👤 Author

Manjunadh S
Machine Learning & Cricket Analytics Enthusiast

📜 License

Licensed under the MIT License.
