# 🔍 Crime Rate Predictor - Unlock Safety: Reduce Crime Rate Together

![Crime Rate Prediction Banner](https://github.com/karthikprogr/Crime-Rate-Predictor/blob/main/static/images/Screenshot%202025-06-05%20115011.png)

Crime Rate Predictor is a machine learning-based web application that forecasts crime trends across 19 Indian metropolitan cities. The project aims to help law enforcement agencies allocate resources effectively and enhance public safety through data-driven predictions.

---

## 📌 Project Overview

- **Objective**: Predict crime rate based on city, year, and crime type.
- **Dataset Source**: Manually compiled from NCRB (2014–2021).
- **Model Used**: Random Forest Regression with 93.20% accuracy.
- **Tech Stack**: Python, Flask, scikit-learn, NumPy, Matplotlib, Pickle.

---

## 💡 Key Features

- Predicts crime trends for 10+ major crime categories.
- Visualizes future crime rates with graphs.
- User-friendly web interface.
- Fast predictions using a pre-trained model (`.pkl` file).
- Graphical insights for better interpretation.

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/karthikprogr/Crime-Rate-Predictor.git
cd Crime-Rate-Prediction

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```
---

## 🧪 Usage

1. Launch the web app in your browser.
2. Select a city, crime category, and year.
3. Click **Predict** to view predicted crime rates and a graph.

---

## 📊 ML Methodology

- **Preprocessing**: Label encoding, missing value handling.
- **Algorithms Tested**: SVM, KNN, Decision Tree, Neural Network, Random Forest.
- **Best Model**: Random Forest Regression (selected based on highest accuracy).
- **Evaluation Metrics**: Accuracy score, RMSE.

---

## 📂 Project Modules

- **Flask**: Web app framework
- **Pickle**: Loads ML model
- **NumPy**: Numerical operations
- **Matplotlib**: Visualizes data
- **Math**: Rounding and calculations
- **OS**: Handles graph files

---

## 📈 Architecture Overview

```text
User Input → Flask Backend → Trained Model (.pkl) → Prediction → Result Display + Graph Generation
```
---

## 🙌 Contributing

Contributions are welcome! 🚀

To contribute:

1. Fork the repository 🍴
2. Create a new branch for your feature or bug fix 🌿
3. Commit your changes with clear messages 💬
4. Push to your fork 🔼
5. Open a pull request 📥

---

## 📬 Contact

For any queries or suggestions, feel free to reach out:

**Email**: [seelamkarthik2006@gmail.com](mailto:seelamkarthik2006@gmail.com)
---

> 🔐 Let’s harness AI to create safer communities by understanding and predicting crime before it happens.
