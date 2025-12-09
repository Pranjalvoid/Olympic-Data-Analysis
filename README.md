# Olympics Data Analysis Web App 🏅

A Streamlit-based web application for analyzing 120 years of Olympic data. This app allows you to explore historical athlete and event data, visualize trends, and gain insights about Olympic history.  

## ✅ Info About This Project

- Provides an interactive and visual way to analyze Olympics data over a century.  
- Lets users explore medal trends, country-wise performance, gender statistics, and more.  
- Built with easy-to-use tools (Python + Streamlit), making it accessible to beginners and data-enthusiasts alike.  

## 📚 Dataset

The data is sourced from the Kaggle dataset:  
[“120 years of Olympic history: athletes and results”](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)  

## 🚀 Live Demo

You can try the app live at:  
[https://olympic-data-analysis-pranjaldtu.streamlit.app/]

---

## 🛠️ Built With / Tech Stack

- Python  
- Streamlit — for building the web UI  
- pandas / numpy  — for data analysis  
- matplotlib , seaborn , plotly - for visualization

## 🧑‍💻 Getting Started — Run Locally

### Prerequisites

Make sure you have Python (3.x) installed.  

### Setup Steps

```bash
# 1. Clone the repo
git clone https://github.com/<your-username>/olympics-data-analysis-web-app.git
cd olympics-data-analysis-web-app

# 2. (Optional) create virtual environment
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. (If needed) run setup script
bash setup.sh   # or skip if not required

# 5. Start the app
streamlit run app.py
