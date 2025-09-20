# 📊 CORD-19 Data Explorer

This project explores the **CORD-19 metadata dataset**, focusing on COVID-19 related research papers.  
The workflow includes **data loading, cleaning, analysis, visualization, and building a simple Streamlit app**.

---

## 🚀 Project Workflow

### **Part 1: Data Loading & Exploration**
- Load `metadata.csv` into a Pandas DataFrame  
- Explore dataset shape, column info, and missing values  
- Generate basic statistics for numerical columns  

### **Part 2: Data Cleaning & Preparation**
- Handle missing values (drop or fill)  
- Convert `publish_time` to datetime format  
- Extract publication year  
- Create additional features (e.g., abstract word count)  

### **Part 3: Data Analysis & Visualization**
- Count publications by year  
- Identify top publishing journals  
- Analyze frequent words in paper titles  
- Visualizations:
  - 📈 Publications by year  
  - 📊 Top journals  
  - ☁️ Word cloud of paper titles  
  - 📦 Distribution of papers by source  

### **Part 4: Streamlit Application**
- Interactive interface for exploring the dataset  
- Features:
  - Year range slider  
  - Filtered visualizations  
  - Sample data preview  
  - Word cloud of paper titles  

### **Part 5: Documentation & Reflection**
- Comments added in all code  
- Short report included with:
  - Key findings  
  - Challenges  
  - Lessons learned  

---

## 🛠️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/your-username/cord19-explorer.git
cd cord19-explorer

2. Install Dependencies

pip install -r requirements.txt

3. Run Jupyter Notebook

jupyter notebook CORD19_Analysis.ipynb

4. Run Streamlit App

streamlit run app.py


---

📂 Project Structure

CORD19-Explorer/
│
├── data/
│   └── metadata.csv        # Downloaded CORD-19 metadata file
│
├── CORD19_Analysis.ipynb   # Jupyter notebook for analysis
├── app.py                  # Streamlit app
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── report.md               # Findings & reflection


---

📦 Dependencies

pandas

matplotlib

seaborn

wordcloud

streamlit


Install via:

pip install pandas matplotlib seaborn wordcloud streamlit
