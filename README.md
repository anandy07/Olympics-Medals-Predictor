# 🏅 Olympics Medals Predictor

A data-driven machine learning project to **predict Olympic medal counts** for countries using historical performance, number of athletes, and other relevant features.

Built with **Python**, **Pandas**, **Scikit-learn**, and **Seaborn**, this project provides insights and predictions based on Olympic data.

---

## 🚀 Features

✅ Predicts medal counts based on historical data  
✅ Uses Linear Regression with visualizations  
✅ Clean train-test split based on year (pre/post 2012)  
✅ Supports filtering/predicting for a single country  
✅ Jupyter Notebook with full EDA + model workflow  

---

## 🛠️ Tech Stack

* **Language**: Python  
* **Environment**: Jupyter Notebook  
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
* **Model**: Linear Regression  

---

## 🧠 How It Works

### Jupyter Notebook (`Olympics medals predictor.ipynb`)

* Loads and processes Olympic dataset
* Performs Exploratory Data Analysis (EDA)
* Splits data into training (before 2012) and test (2012+)
* Trains a Linear Regression model
* Predicts and visualizes medal counts
* Allows querying medals by country name

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/olympics-medals-predictor.git
cd olympics-medals-predictor
2️⃣ Create a Virtual Environment (Optional)
bash
Copy
Edit
python -m venv env
source env/bin/activate  # For Windows: env\Scripts\activate
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
Once open, run each cell step-by-step to:

Explore the dataset

Train the model

Predict medal counts

Filter predictions for any country using:

python
Copy
Edit
test[test["team"] == "IND"]
📁 File Structure
bash
Copy
Edit
.
├── Olympics medals predictor.ipynb  # Jupyter Notebook with code + visualizations
├── dataset/                         # (Optional) Folder containing CSVs
├── requirements.txt                # List of dependencies
└── README.md                       # Project documentation
✨ Future Improvements
Add more predictive features (GDP, funding, training resources)

Improve accuracy with ensemble models

Streamlit dashboard for real-time predictions

Country flag/poster integration using API

🧑‍💻 Author
Developed by Anand Yadav
GitHub: @anandy07

📜 License
This project is licensed under the MIT License.

⭐ Contribute & Support
If you found this useful, consider giving it a star ⭐ on GitHub!
Pull requests, feature suggestions, and forks are always welcome.



