# 📊 Financial News and Stock Price Analysis

This project focuses on the analysis of **financial news articles** and **stock price data** for seven major companies:  
**AAPL, AMZN, GOOG, META, MSFT, NVDA, and TSLA**.  

The analysis involves **Exploratory Data Analysis (EDA)**, **Quantitative Analysis**, and the application of key financial indicators.  
The project is divided into **three main tasks** to ensure a structured and stepwise approach.

---

## 🚀 **Project Objectives**
1. **Task 1: Exploratory Data Analysis (EDA)**  
   - Understand the structure, content, and patterns within the financial news dataset.  
   - Identify key publishers, sentiment distribution, and time-based publication frequency.  
   
2. **Task 2: Quantitative Analysis**  
   - Analyze stock price data for seven companies using financial indicators.  
   - Calculate and visualize key technical indicators like **SMA, EMA, RSI, MACD, and Volatility**.  

3. **Task 3: [To be completed]**  
   - Further analysis and integration of insights from EDA and quantitative analysis.

---

## 📂 **Project Structure**

```
project-folder/
├── notebooks/                # Jupyter notebooks for EDA and analysis
│   ├── EDA.ipynb             # Exploratory Data Analysis (Task 1)
│   ├── quantitative_analysis.ipynb  # Quantitative analysis (Task 2)
│   └── .ipynb_checkpoints/   # Auto-saved Jupyter files (ignored by Git)
├── Data/                     # Data files (financial news and stock price data)
│   └── cleaned_data.csv      # Cleaned financial news dataset
├── env/                      # Python virtual environment (ignored by Git)
├── .gitignore                # Git ignore file (excludes unnecessary files)
├── README.md                 # This README file
└── requirements.txt          # Required packages and dependencies
```

---

## 🔧 **How to Set Up the Project**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/financial-news-analysis.git
   cd financial-news-analysis
   ```

2. **Set Up a Virtual Environment**
   ```bash
   python -m venv env
   source env/bin/activate   # On macOS/Linux
   .\env\Scripts\activate    # On Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Lab**
   ```bash
   jupyter lab
   ```

---

## 📊 **Tasks and Progress**

### **✅ Task 1: Exploratory Data Analysis (EDA)**
**Goal**: Understand and analyze the financial news dataset.  
**Methods**:  
- Time-Series Analysis: Analyzed the frequency of news publications over time.  
- Sentiment Analysis: Used VADER sentiment analysis to understand the sentiment distribution.  
- Publisher Analysis: Identified dominant publishers in the dataset.  

**Key Findings**:  
- **Publication Spikes**: Significant increases in article publications occurred during major market events.  
- **Publisher Influence**: A small number of publishers contributed a majority of the articles.  
- **Sentiment Trends**: Most articles were neutral, with fewer classified as strongly positive or negative.  

---

### **✅ Task 2: Quantitative Analysis**
**Goal**: Calculate and visualize financial indicators for seven companies.  
**Methods**:  
- **Simple Moving Average (SMA)**: 50-day SMA to track short-term price movements.  
- **Exponential Moving Average (EMA)**: 200-day EMA to identify long-term trends.  
- **Relative Strength Index (RSI)**: 14-day RSI to track overbought/oversold conditions.  
- **Moving Average Convergence Divergence (MACD)**: Used to track price momentum and identify buy/sell signals.  
- **Volatility**: Calculated the 30-day rolling standard deviation of stock returns.  

**Key Insights**:  
- **Trend Reversals**: The crossover of 50-day SMA and 200-day EMA indicates trend reversals.  
- **Market Conditions**: Overbought/oversold conditions were detected using the RSI.  
- **Volatility**: Companies like **NVDA** exhibited higher volatility, indicating potential risk.  

---

## 📈 **Key Insights**

1. **EDA Results**: Insights into news publication spikes, sentiment trends, and publisher influence.  
2. **Quantitative Analysis**: Detection of price trend reversals, market conditions (RSI), and stock price volatility.  
3. **Next Steps**: Further analysis and finalization of Task 3.  

---

## 🤝 **Contributing**
Contributions, issues, and feature requests are welcome!  
Feel free to check the **issues page** if you'd like to contribute.  

---

## 📄 **License**
This project is licensed under the **MIT License**.  

---

## 📬 **Contact**
If you have any questions, feel free to reach out to the project maintainers.  

**Project Link**: [GitHub Repository](https://github.com/kaleabb266/financial-news-analysis.git)

