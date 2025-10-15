<h3>Time Series Forecasting using Prophet</h3>
<p>
  This project applies Meta’s Prophet model to forecast financial time series
  data. It focuses on analyzing stock trends, seasonality, and forecasting
  accuracy using both custom and real-world Apple datasets.
</p>
<h3>Overview</h3>
<p>
  The project demonstrates how to prepare, decompose, and model time series
  data. It includes data preprocessing, visualization, model training,
  evaluation, and interpretation of forecast components like trend and weekly
  seasonality.
</p>
<h3>Steps Involved</h3>
<ul>
  <li>
    Imported and explored the dataset (shape, date range, and holiday checks)
  </li>
  <li>Performed the Durbin-Watson test to confirm time series suitability</li>
  <li>Applied seasonal decomposition to visualize trend and residuals</li>
  <li>Trained Prophet model for forecasting and plotted forecast components</li>
  <li>Used Apple stock data (1980–2020) for real-world validation</li>
  <li>Performed cross-validation and evaluated forecast performance</li>
</ul>
<h3>Tools & Libraries Used</h3>
<ul>
  <li>Python</li>
  <li>Pandas, NumPy</li>
  <li>Statsmodels (TSA)</li>
  <li>Prophet</li>
  <li>Matplotlib, Seaborn</li>
  <li>Jupyter Notebook</li>
</ul>
<h3>Results</h3>
<p>
  The Prophet model effectively captured long-term trends and seasonal
  variations, producing accurate forecasts and interpretable visualizations. The
  analysis showcased the model’s strength in handling complex time series data.
</p>
<h3>How to Run</h3>
<p>
  1. Clone the repository
  <code>git clone https://github.com/lagyal/Stock-Market-Time-Series-Analysis.git</code>
</p>
<p>2. Install dependencies <code>pip install -r requirements.txt</code></p>
<p>
  3. Run the notebook <code>jupyter notebook StockPricePrediction.ipynb</code>
</p>
<h3>Author</h3>
<p>Developed by Lagyal — Data Science & Machine Learning Enthusiast.</p>
