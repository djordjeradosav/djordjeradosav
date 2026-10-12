## Hi, I'm Đorđe 👋

**Full-stack & mobile developer with a machine-learning focus**, based in Serbia. I build cross-platform apps with React Native, web apps with React/Next.js and Laravel, and data and neural-network pipelines in **Python**.

- 🚀 Currently building **[Ticksnap](https://github.com/djordjeradosav/Mobilno)**, a social trading-journal app (Expo · TypeScript · Supabase)
- 🧠 Latest ML work: **[neural networks for FX price prediction](https://github.com/djordjeradosav/NeuralNetwork-for-Price-Prediction)**, 630 model runs across 6 currency pairs
- 🎓 Computer science student, focusing on ML and neural networks
- 💼 **Open to junior / internship roles** in full-stack, mobile, data, or quant
- 📫 radosavljevicdjordje01@gmail.com

---

### 🧠 Spotlight: Neural networks for FX price prediction

**[NeuralNetwork-for-Price-Prediction](https://github.com/djordjeradosav/NeuralNetwork-for-Price-Prediction)** asks whether a neural network can forecast currency markets. It uses 10 years of daily data for 6 currency pairs (EURUSD, USDCAD, USDCHF, USDCNY, USDGBP, USDJPY).

<p>
  <a href="https://github.com/djordjeradosav/NeuralNetwork-for-Price-Prediction"><img src="https://raw.githubusercontent.com/djordjeradosav/NeuralNetwork-for-Price-Prediction/main/grafovi/plot1_cene.png" width="49%" alt="Currency pair prices 2016-2026" /></a>
  <a href="https://github.com/djordjeradosav/NeuralNetwork-for-Price-Prediction"><img src="https://raw.githubusercontent.com/djordjeradosav/NeuralNetwork-for-Price-Prediction/main/grafovi/plot9_heatmapa_r2.png" width="49%" alt="R² heatmap for price prediction" /></a>
</p>

| | |
|---|---|
| **Tasks** | Predict the future price, the future return and the up/down direction, 1, 3, 5 and 10 trading days ahead |
| **Features** | 13 technical indicators (RSI, MACD, ATR, KAMA, CCI, Parabolic SAR…), lagged prices, and ROC/SMA transforms |
| **Model** | scikit-learn MLP (128-64-32, ReLU, Adam, L2, early stopping) for both regression and classification |
| **Scale** | 27 experiment variants × 6 pairs × up to 4 horizons = **630 runs**, all logged with MAE, RMSE, R², MAPE, accuracy, F1 and confusion matrices |
| **Results** | Price R² up to **0.986** (EURUSD, 1 day). Direction accuracy up to **70.7%** against a 50% baseline (USDCAD, 3 days). The README also covers where the model fails and why |

---

### 🐍 Python & machine learning

- **Data wrangling:** cleaning messy CSVs, aligning time series and handling missing values (choosing mean or median after a Shapiro–Wilk test), with pandas and NumPy
- **Feature engineering:** technical indicators (`ta`, `stockstats`, and hand-written implementations), lag features, ROC/SMA transforms and scaling
- **Neural networks:** MLP regressors and classifiers, experiment grids, early stopping and regularisation
- **Classical ML:** linear regression, decision trees, kNN, K-Means and hierarchical clustering ([Models](https://github.com/djordjeradosav/Models))
- **Evaluation:** MAE, RMSE, R², MAPE, accuracy, precision/recall/F1, confusion matrices, silhouette score and elbow method
- **Reporting:** Matplotlib and Seaborn charts, plus automated Excel result exports (`xlsxwriter`)
- **Projects:** [FX Neural Networks](https://github.com/djordjeradosav/NeuralNetwork-for-Price-Prediction) · [PriceTrend](https://github.com/djordjeradosav/PriceTrend) (the same research applied to stocks on 9 exchanges) · [ML Models](https://github.com/djordjeradosav/Models)

---

### 📈 Quant & finance

Most of my projects are about financial markets. I'm working toward a career in **quantitative finance**.

| Project | Finance angle |
|---|---|
| [FX Neural Networks](https://github.com/djordjeradosav/NeuralNetwork-for-Price-Prediction) | Price, return and direction forecasting for 6 currency pairs from 13 technical indicators |
| [PriceTrend](https://github.com/djordjeradosav/PriceTrend) | The same research applied to stocks on 9 exchanges (US, UK, Europe, Japan, China) |
| [Ticksnap](https://github.com/djordjeradosav/Mobilno) | Trading journal with P&L analytics and live US macro data (FRED) |
| [IPO Tracker](https://github.com/djordjeradosav/IPO) | IPO calendar backed by a market-data API |

**Next up:** walk-forward backtesting with transaction costs, risk metrics (Sharpe ratio, max drawdown), portfolio optimization (mean-variance, risk parity) and options pricing (Black-Scholes, Monte Carlo).

---

### Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**Ticksnap**](https://github.com/djordjeradosav/Mobilno) | Social trading journal: trade logging, P&L analytics, follows/comments, live US macro data | React Native, Expo, TypeScript, Supabase |
| [**FX Neural Networks**](https://github.com/djordjeradosav/NeuralNetwork-for-Price-Prediction) | MLPs predicting price, return and direction for 6 currency pairs across 630 runs; up to 70.7% direction accuracy | Python, scikit-learn, pandas |
| [**PriceTrend**](https://github.com/djordjeradosav/PriceTrend) | ML pipeline that predicts stock and FX price trends from 12 hand-built technical indicators | Python, pandas, scikit-learn |
| [**E-commerce Cart**](https://github.com/djordjeradosav/e-com) | Shopping cart with queued low-stock alerts and scheduled sales reports | Laravel 11, React, Inertia.js, Tailwind |
| [**CRM API**](https://github.com/djordjeradosav/CRMAPPBACK) + [**Dashboard**](https://github.com/djordjeradosav/CRMFINALE) | Clients/contacts/invoices CRM with token auth and role-based access | Laravel 12, Sanctum, React |
| [**IPO Tracker**](https://github.com/djordjeradosav/IPO) | IPO calendar with search and filters, via a server-side API proxy | Next.js 14, TypeScript, Tailwind |
| [**ML Models**](https://github.com/djordjeradosav/Models) | Applied notebooks: regression, decision trees, kNN, MLP, clustering | Python, scikit-learn, Jupyter |

---

### Tech stack

**Languages:** TypeScript · JavaScript · Python · PHP · Swift · SQL
**Frontend & mobile:** React · React Native / Expo · Next.js · Tailwind CSS · SwiftUI
**Backend & data:** Laravel · Supabase · PostgreSQL · MySQL · REST APIs
**Python / ML:** scikit-learn (MLP, trees, kNN, clustering) · pandas · NumPy · SciPy · Matplotlib · Seaborn · ta · Jupyter
**Tools:** Git · Vite · EAS · Vercel

---

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=djordjeradosav&show_icons=true&hide_border=true&count_private=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=djordjeradosav&layout=compact&hide_border=true" height="160" />
</p>
