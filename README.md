# 📊 Advanced Themed EDA Dashboard

An interactive Exploratory Data Analysis (EDA) dashboard built using **Streamlit, Pandas, Plotly, Seaborn, and Matplotlib**.  
This application allows users to upload any CSV file and perform dynamic data analysis and visualization.
<img width="1886" height="940" alt="image" src="https://github.com/user-attachments/assets/17107e87-5088-4ae2-91be-2839e69c55d9" />
<img width="1862" height="916" alt="Screenshot 2026-02-08 132733" src="https://github.com/user-attachments/assets/cfb7e4f9-d238-42e7-8b10-ca2a0f584692" />
<img width="1872" height="952" alt="Screenshot 2026-02-08 132943" src="https://github.com/user-attachments/assets/6cfce6f2-cc51-4253-93eb-2ee3743cb4a6" />
<img width="1057" height="450" alt="newplot" src="https://github.com/user-attachments/assets/65a87c98-acd0-40e2-ad5d-93ffa6bfb5f8" />

---

## 🚀 Project Overview

This project is a web-based dashboard that helps users:

- Upload datasets  
- Preview and explore data  
- Handle missing values  
- Filter data dynamically  
- Generate multiple types of visualizations  
- Perform advanced analytics without writing any code  

It is designed to be user-friendly, interactive, and highly customizable.

---

## 🛠 Technologies Used

- **Python**
- **Streamlit** – Web App Framework  
- **Pandas** – Data Manipulation  
- **Plotly Express** – Interactive Graphs  
- **Seaborn & Matplotlib** – Statistical Visualizations  

---

## ✨ Features

### 1. Themed Interface  
- Light and Dark theme toggle  
- Clean and modern UI  

### 2. CSV File Upload  
- Upload any dataset in CSV format  
- Automatic data loading  

### 3. Dataset Preview  
- View first few rows  
- Statistical summary using `.describe()`  

### 4. Dataset Summary Metrics  
- Total Rows  
- Total Columns  
- Total Missing Values  

### 5. Missing Value Handler  
User can handle missing values using:

- Drop rows  
- Fill with Mean  
- Fill with Median  

### 6. Dynamic Data Filtering  

- Select any numeric column  
- Use range slider  
- View filtered dataset instantly  

### 7. Visualization Hub  

Supports multiple interactive charts:

- Histogram  
- Boxplot  
- Scatter Plot  
- Line Chart  
- Bar Chart  
- Violin Plot  
- Pie Chart  
- Treemap  
- Heatmap  
- 3D Scatter Plot  

All charts are generated dynamically based on user input.

---

## 📂 Project Structure
Advanced_EDA_Dashboard/
│
├── app.py # Main Streamlit Application
├── requirements.txt # Required Python Libraries
├── README.md # Project Documentation


---

## ⚙ Installation & Setup

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/Advanced-EDA-Dashboard.git
cd Advanced-EDA-Dashboard
Step 2: Install Dependencies

Create a virtual environment (optional but recommended):

python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate


Install required libraries:

pip install -r requirements.txt

Step 3: Run Application
streamlit run app.py

📦 Requirements

Create a requirements.txt file with:

streamlit
pandas
matplotlib
seaborn
plotly


