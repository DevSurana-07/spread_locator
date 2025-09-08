# Spread Locator

This project analyzes transaction data and models it using different probability distributions. The dataset used is **`spread_locator_dataset.csv`**, and the analysis is done in **`spread_locator.ipynb`**.

## 📂 Files
- `spread_locator.ipynb` → Jupyter Notebook containing the full analysis and visualizations.  
- `spread_locator_dataset.csv` → Dataset containing transaction records.

## ⚙️ Workflow
1. **Bernoulli & Binomial Distribution**  
   - Converted transaction outcomes (Success = 1, Fail = 0).  
   - Calculated probability of success and failure.  
   - Modeled occurrence of transactions using Bernoulli and Binomial distributions.  

2. **Poisson Distribution**  
   - Aggregated daily transactions.  
   - Modeled transaction counts per day using Poisson distribution.  

3. **Log-Normal & Power Law Distributions**  
   - Modeled transaction amounts using Log-Normal distribution.  
   - Compared with Power Law distribution.  

4. **Q-Q Plot (Normality Check)**  
   - Generated and interpreted Q-Q plots to assess data normality.  

## 📊 Visualizations
- Probability Mass Functions (PMF) for Bernoulli, Binomial, and Poisson.  
- Histogram with Log-Normal and Power Law fits.  
- Q-Q plot for normality check.  
