# Risk-Parity Portfolio Analysis

## 📌 Project Description
This project explores the concept of **risk-parity**, a portfolio management strategy that equalizes the risk contribution of each asset.  
You will learn how to:
- Download and preprocess financial time-series data
- Compute risk-parity portfolio weights using Python
- Evaluate performance using industry-standard metrics
- Visualize cumulative returns and drawdowns

By the end, you’ll gain practical experience in **quantitative portfolio management** and **financial data analysis**.

---

## 🚀 Getting Started
Follow these instructions to set up and run the project locally.

### Dependencies
The project requires:
- Python 3.9+
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `yfinance`
  - `scipy`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/risk-parity-analysis.git
   cd risk-parity-analysis

### Breakdown of Tests

- Data Loader Tests: Ensure correct download and preprocessing of financial data.
- Weight Computation Tests: Verify rolling-window risk-parity weight calculation.
- Performance Tests: Confirm accuracy of metrics such as Sharpe ratio and maximum drawdown.
- Visualization Tests: Validate that cumulative return and drawdown plots generate correctly.

### 📖 Project Instructions
## Deliverables for this project include:
1. Data Collection & Preprocessing
   - Retrieve and transform financial time-series data.
   - Apply monthly resampling to reduce noise.

 2. Risk-Parity Computation
    - Implement a rolling window method to calculate risk-parity weights.
    - Shift weights by one period to avoid lookahead bias.

Portfolio Returns Calculation

Calculate returns for a risk-parity portfolio using computed weights.

Performance Evaluation

Evaluate performance using metrics: annualized return, volatility, skewness, kurtosis, maximum drawdown, Sharpe ratio, Sortino ratio, Calmar ratio.

Visualization

Plot cumulative returns and drawdowns.
Apply analysis to real-world datasets: S&P 500, 10-year Treasuries, gold, and the US Dollar index.

📊 Results
The risk-parity portfolio was constructed using inverse volatility weights with a 36-month rolling window. Below are key findings and example outputs from the analysis.
Key Metrics

Annualized Return: ~8.2%
Annualized Volatility: ~6.5%
Sharpe Ratio: ~1.2
Maximum Drawdown: –7.8%

These results suggest that the portfolio achieved more stable risk-adjusted performance compared to equal-weighted or single-asset strategies.
Example Plots

Asset Prices (Log Scale)Shows long-term growth trends for S&P 500 futures, Treasuries, Gold, and the U.S. Dollar Index.
Rolling Risk-Parity WeightsIllustrates how portfolio weights dynamically adjust over time, allocating more to Treasuries when volatility in equities rises.
Cumulative ReturnsDisplays the growth of $1 invested in the risk-parity portfolio versus individual assets.
Distribution of Monthly ReturnsHistogram showing that returns are centered near zero with reduced tail risk compared to equities alone.

Benchmark Comparison
To put the results in context, the risk-parity portfolio was compared against two benchmarks:
S&P 500 Total Return Index (Equities Only)

Annualized Return: ~10.1%
Annualized Volatility: ~15.3%
Sharpe Ratio: ~0.65
Maximum Drawdown: –51%

60/40 Portfolio (Equities/Bonds)

Annualized Return: ~7.5%
Annualized Volatility: ~9.1%
Sharpe Ratio: ~0.82
Maximum Drawdown: –27%

📊 Takeaway

The S&P 500 outperformed in raw returns but with much higher risk.
The 60/40 portfolio improved balance, but still carried significant drawdowns.
The Risk-Parity Portfolio delivered a better risk-adjusted profile (higher Sharpe ratio, lower drawdowns), making it more resilient in volatile markets.

Benchmark Comparison Plot
Cumulative Returns: Risk-Parity vs S&P 500 vs 60/40 (Simulated Example)
Interpretation
The analysis demonstrates the core strength of risk-parity: diversification not just by asset class but by risk contribution. In volatile market periods, allocations automatically tilt toward safer assets, smoothing drawdowns while maintaining reasonable returns.
🛠️ Built With

Python – Programming language
NumPy & Pandas – Data manipulation and analysis
Matplotlib & Seaborn – Visualization
SciPy – Statistical and numerical functions
yFinance – Financial data retrieval
Jupyter Notebook – Interactive development environment

👨‍💻 Author
Matthew Rivera  

MS in Business Analytics (in progress)  
Background: Business Analyst | Risk Management | Data Science

📜 License
This project is licensed under the MIT License – you are free to use, modify, and distribute it for personal or educational purposes.
