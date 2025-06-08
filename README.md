# 🏅 Olympics Medals Predictor

An intelligent Olympic medal prediction system built using **Python**, **Jupyter Notebook**, and **scikit-learn**. It forecasts the number of medals a country will win based on historical data, number of athletes, and other features.

---

## 🚀 Features

✅ **Linear Regression Model** for medal prediction  
✅ **Year-wise Train/Test Split** (e.g., pre-2012 vs post-2012)  
✅ **Exploratory Data Analysis** with Seaborn and Matplotlib  
✅ **Country-wise Medal Lookup**  
✅ **Interactive Visualizations** for insights  

---

## 🛠️ Tech Stack

* **Platform**: Jupyter Notebook  
* **Language**: Python  
* **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
* **Modeling**: Linear Regression (with sklearn)  

---

## 🧠 How It Works

### Jupyter Notebook (`Olympics medals predictor.ipynb`)

* Loads Olympic dataset  
* Performs data cleaning and preprocessing  
* Conducts visual exploration (e.g., medals vs. athletes)  
* Splits dataset into training and test based on year  
* Trains a Linear Regression model  
* Predicts and visualizes medal counts  
* Allows user to query predictions by country name

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/anandy07/olympics-medals-predictor.git
cd olympics-medals-predictor
2️⃣ Create a Virtual Environment (optional but recommended)
bash
Copy
Edit
python -m venv env
source env/bin/activate  # or use env\Scripts\activate on Windows
3️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
📌 Usage
To run the notebook:

bash
Copy
Edit
jupyter notebook Olympics\ medals\ predictor.ipynb
You can search for a specific country in the predictions:

python
Copy
Edit
test[test["team"] == "IND"]
This will return the predicted medal count for India.

📁 File Structure
bash
Copy
Edit
.
├── Olympics medals predictor.ipynb  # Jupyter Notebook with model and visualizations
├── dataset/                         # (Optional) Folder containing CSVs
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation
✨ Future Ideas
Include additional predictors like GDP, investment, previous rank

Build a web app using Streamlit for live predictions

Add medal category breakdown (gold/silver/bronze)

Visualize trends over decades

🧑‍💻 Author
Developed by Anand Yadav
GitHub: @anandy07

📜 License
This project is licensed under the MIT License.

⭐ Contribute & Support
If you liked this project, consider giving it a star ⭐ on GitHub!
Pull requests, issues, and suggestions are always welcome.
