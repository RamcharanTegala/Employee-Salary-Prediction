# Employee-Salary-Prediction
A machine learning project that predicts employee salary levels through an interactive web interface.
# 💼 Employee Salary Prediction Web App

This project predicts whether an employee's annual income exceeds $50K based on census data. It includes a complete workflow from data cleaning and model training in a Jupyter Notebook to an interactive web application built with Streamlit.

---

### ✨ Features
- **Income Prediction:** Classifies salary into two categories: `>50K` or `<=50K`.
- **Interactive UI:** A user-friendly web interface built with Streamlit to input employee data and get instant predictions.
- **Model Comparison:** The project evaluates 5 different classification models, with **Gradient Boosting** selected as the best performer.
- **Data Analysis:** A comprehensive Jupyter Notebook (`employee_salary_prediction.ipynb`) details the entire process of data cleaning, exploratory data analysis (EDA), and model training.

---

### 📸 Demo

Here's a look at the Streamlit web application interface:

*To add your own screenshot, take a picture of your running app, add it to your repository, and change the link below.*
[!(link_to_your_screenshot.png)
](https://github.com/RamcharanTegala/Employee-Salary-Prediction/tree/0b633c36264d0683fa5158ad53a73ada71f33da9/Screenshots)
---

### 🛠️ Technology Stack
- **Language:** Python 3
- **Data Analysis:** Pandas, Matplotlib
- **Machine Learning:** Scikit-learn
- **Web Framework:** Streamlit
- **Model Persistence:** Joblib

---

### 🚀 How to Run This Project Locally

Follow these steps to get the project running on your own machine.

**1. Clone the Repository**
```bash
git clone [https://github.com/RamcharanTegala/Employee-Salary-Prediction.git](https://github.com/RamcharnTegala/Employee-Salary-Prediction.git)
cd Employee-Salary-Prediction
```

**2. Create a Virtual Environment**
It's recommended to create a virtual environment to keep dependencies isolated.
```bash
# For Mac/Linux
python3 -m venv venv
source venv/bin/activate

# For Windows
python -m venv venv
venv\Scripts\activate
```

**3. Install Dependencies**
Install all the necessary libraries from the `requirements.txt` file.
```bash
pip install -r requirements.txt
```

**4. Run the Streamlit App**
Launch the application using the following command:
```bash
streamlit run app.py
```
The app should now be open and running in your web browser!

---

### 📂 Project File Structure
- `app.py`: The main script for the Streamlit web application.
- `best_model.pkl`: The pre-trained Gradient Boosting classifier model saved using joblib.
- `employee_salary_prediction.ipynb`: The Jupyter Notebook containing all the data analysis, preprocessing, and model training steps.
- `requirements.txt`: A list of all Python libraries required to run the project.
- `adult 3.csv`: The dataset used for training and evaluation.
