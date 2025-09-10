# ds_krishnarana

This repository contains a deep-dive analysis of trader behavior and market sentiment using the Bitcoin Market Sentiment dataset and Hyperliquid historical trader data.

## Project Overview
This project explores how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed). The analysis identifies hidden trends and signals that can inform smarter trading strategies.

## Repository Structure
- `notebook_1.ipynb`: Main Jupyter/Colab notebook with step-by-step analysis, EDA, visualizations, and insights.
- `csv_files/`: Contains raw datasets (`fear_greed_index.csv`, `historical_data.csv`) and any intermediate data outputs.
- `outputs/`: Stores generated visualizations, charts, and figures from the notebook.
- `ds_report.pdf`: Final report summarizing key findings and recommendations.
- `README.md`: Project instructions, setup, and notes.

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-github-username>/ds_krishna.git
   cd ds_krishna
   ```
2. **Install required libraries:**
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. **Run the notebook:**
   - Open `notebook_1.ipynb` in Google Colab or Jupyter Notebook.
   - Ensure datasets are present in the `csv_files` directory.
   - Execute cells step-by-step for full analysis.

## Usage
- All code and analysis are designed for Google Colab. Share Colab links with 'Anyone with the link can view' access for submission.
- Visualizations are automatically saved in the `outputs` directory.
- Update the same structure in your GitHub repository for consistency.

## Analysis Steps
1. **Data Loading:** Import and inspect both datasets.
2. **Data Cleaning:** Handle missing values, convert date columns, and merge datasets.
3. **Exploratory Data Analysis (EDA):** Visualize sentiment distribution, profitability, risk, volume, and leverage.
4. **Advanced Analysis:** Segment traders, analyze risk, volume, leverage, and identify trends.
5. **Reporting:** Summarize insights and export results for further use.

## Notes
- Ensure all datasets are correctly formatted and placed in the `csv_files` directory.
- For any issues, check column names and file paths in the notebook.
- For questions or contributions, open an issue or pull request.

## License
This project is for educational and research purposes.
