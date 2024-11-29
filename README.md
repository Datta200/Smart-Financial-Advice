
# 💼 Smart Financial Advice

A **financial planning tool** built using **Streamlit** that helps users manage their finances effectively by balancing savings, investments, expenses, and taxes. The app also features **SIP calculation** and **financial goal tracking** to assist in better financial planning.

## 🎯 Features
- **Savings & Investments Predictions**: Uses **Linear Regression** and **Decision Tree models** to predict savings, investment, and tax rates.
- **Dynamic Financial Planning**: Adjusts savings, investments, and expenses based on income, tax regime, and family size.
- **SIP Calculator**: Helps users project the future value of systematic investments.
- **Financial Goals Tracker**: Assists in planning monthly savings to achieve specific financial goals.
- **Monthly/Yearly View**: Allows switching between monthly and yearly financial breakdowns.

---

## 🚀 How to Run Locally

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- `pip` (Python package installer)

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/smart-financial-advice.git
cd smart-financial-advice
```

### Step 2: Install Dependencies
```bash
pip install streamlit numpy scikit-learn matplotlib
```

### Step 3: Run the App
```bash
streamlit run app.py
```

---

## 🌐 Live Demo
Access the app online at:  
[Smart Financial Advice](https://finance-bzqwojndskvzwu585feyw2.streamlit.app)

---

## 📂 Project Structure
```
smart-financial-advice/
│
├── app.py                 # Main application code
├── README.md              # Project documentation
└── requirements.txt       # List of dependencies
```

---

## 🛠 Dependencies
- **Streamlit**: For building the interactive web app.
- **NumPy**: For numerical operations.
- **Matplotlib**: For visualizing savings and investment rates.
- **Scikit-learn**: For training ML models (Linear Regression & Decision Tree).

---

## 📈 How It Works
1. **Input your monthly salary** and **select the number of family members**.
2. **Choose the tax regime** (currently supports only the new regime).
3. Get a **financial breakdown** of savings, investments, taxes, and expenses.
4. Use the **SIP calculator** to forecast your investments.
5. Track **financial goals** by calculating the required monthly savings.

---

## 🧩 Future Improvements
- Add support for **old tax regime**.
- Integrate **more ML models** for enhanced predictions.
- Improve the **design and UI** for a better user experience.

---

## 👨‍💻 Contributing
Feel free to contribute!  
1. Fork the repository.
2. Create a new branch (`feature/your-feature`).
3. Commit your changes.
4. Open a pull request.

---

## 🙌 Acknowledgements
- **Streamlit Community** for documentation and support.
- **Scikit-learn** developers for providing easy-to-use ML tools.

---

## 🖥️ Demo
Run the app locally using:
```bash
streamlit run app.py
```
