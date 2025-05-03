# Climate Data Analysis Pipeline 🚀

A modular, end-to-end Python pipeline for climate data processing, analysis, and forecasting. Leverage reanalysis datasets (e.g., MERRA-2) to detect trends, model extreme events, interpolate spatial fields, and project future scenarios with bias-corrected GCM outputs.

## 🚀 Features

* **Data Ingestion & Preprocessing**: Clean, parse, and aggregate daily climate data into monthly summaries.
* **Trend Analysis**: Mann–Kendall test & Sen’s Slope for robust, non-parametric trend detection.
* **Time-Series Forecasting**: ARIMA-based projections with confidence intervals.
* **Correlation Analysis**: Pearson & Spearman matrices for multivariate insights.
* **Extreme Value Modeling**: Fit annual maxima to a GEV distribution to quantify extremes.
* **Spatial Analysis**: Choropleths & Ordinary Kriging for geospatial interpolation.

## 🛠️ Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/victornonso/climate-data-trend-analysis.git
  
   ```
2. (Optional) Create a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```


## 📦 Usage

1. **Jupyter Notebook**: Follow `Climate Data Analysis.ipynb` for an interactive walkthrough.

   ```bash
   Climate Data Analysis.ipynb --input combined_output_3.csv --output results/
   ```


## 🤝 Contributing

Contributions are welcome! Please open issues for bugs or feature requests, and submit PRs against the `develop` branch:

1. Fork the repo
2. Create a feature branch (`git checkout -b feat/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push (`git push origin feat/your-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

