README.md
📊 Sales & Demand Forecasting Engine
AI-powered predictive analytics pipeline with interactive dashboard for sales forecasting and demand planning.
https://python.org
https://scikit-learn.org
LICENSE
✨ Features
🔮 90-Day Forecast — Ensemble prediction using Linear Regression + Random Forest
📈 Interactive Dashboard — Dark-themed Chart.js visualization with real-time data
🤖 ML Pipeline — Automated feature engineering, model training & evaluation
📁 Data Export — JSON/CSV outputs for downstream integration
🎯 Confidence Intervals — ±15% prediction bounds for risk assessment
🚀 Quick Start
Prerequisites
Python 3.8 or higher
pip package manager
Installation
bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/sales-forecasting-engine.git
cd sales-forecasting-engine

# 2. Create virtual environment (recommended)
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt
Usage
bash
# Run the forecasting engine
python forecast_engine.py

# Open the dashboard
# Simply open `index.html` in your browser
The engine will:
Generate 2 years of synthetic business data
Train & evaluate ML models
Export predictions to data/ directory
Serve data to the interactive dashboard
📁 Project Structure
plain
sales-forecasting-engine/
├── forecast_engine.py      # Main ML pipeline
├── index.html              # Interactive dashboard
├── requirements.txt        # Python dependencies
├── data/                   # Generated outputs
│   ├── sales_data.csv      # Historical data
│   ├── forecast_results.csv # 90-day predictions
│   ├── chart_data.json     # Visualization data
│   ├── summary.json        # KPI metrics
│   └── metrics.json        # Model performance
└── README.md
🧠 How It Works
Data Generation
Synthetic 2-year dataset with realistic patterns:
Upward trend (business growth)
Weekly seasonality (weekend peaks)
Monthly & yearly cycles
Holiday spikes (Black Friday, Christmas, July 4th)
Market noise & volatility
Feature Engineering
Time-based: day_of_week, month, quarter, day_of_year
Categorical: one-hot encoded category & region
Binary: weekend & holiday indicators
Models
Table
Model	Type	Strength
Linear Regression	Baseline	Interpretable, fast
Random Forest	Ensemble	Captures non-linear patterns
Ensemble	Averaged	Best of both worlds
Evaluation Metrics
MAE — Mean Absolute Error
RMSE — Root Mean Squared Error
R² — Coefficient of Determination
📊 Dashboard Preview
The dashboard includes:
KPI Cards — Total sales, daily average, forecast total, model accuracy
Sales Trend Chart — Historical data + 90-day forecast with confidence bands
Category Breakdown — Doughnut chart by product category
Monthly Trend — Seasonal bar chart
Regional Performance — Polar area chart
Day-of-Week Pattern — Radar chart for weekly cycles
Forecast Table — Detailed 90-day prediction table
🛠️ Tech Stack
Table
Layer	Technology
Backend	Python, pandas, NumPy, scikit-learn
Frontend	HTML5, CSS3, Chart.js
Styling	CSS Grid, Flexbox, CSS Variables
Fonts	Inter (Google Fonts)
📝 Requirements
plain
pandas>=1.5.0
numpy>=1.24.0
scikit-learn>=1.3.0
matplotlib>=3.7.0
🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
📄 License
Distributed under the MIT License. See LICENSE for more information.
🙏 Acknowledgments
scikit-learn for machine learning tools
Chart.js for beautiful visualizations
Inter font family by Rasmus Andersson
<p align="center">
  Made with ❤️ for data-driven decision making
</p>
