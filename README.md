# Google Search Trend Analysis: Cloud Computing

This project uses Python to analyze **Google search trends** related to the topic **"Cloud Computing"**, leveraging the `pytrends` library.

## Objective
To explore:
- How interest in *Cloud Computing* changes over time
- Which regions search for it the most
- Related queries and keyword suggestions

## Dataset & Source
Data is fetched live from **Google Trends** using `pytrends` (an unofficial API).

## Steps & Approach
- Connect to Google Trends via `pytrends`
- Fetch interest over time (top 10 peaks)
- Fetch interest by region (top 10 regions)
- Retrieve related queries and suggestions
- Visualize the regional interest using bar charts

## Libraries Used
- Python
- Pandas
- Pytrends
- Matplotlib
- time

## Results
- Identified peak times of interest over the past year and a specific month (Jan 2024).
- Top 10 regions with highest search volume.
- Related queries & keyword suggestions for deeper analysis.
- Visualization of regional data with a clean bar chart.

*(You can also save and add plot images in the `/images` folder to show them here)*

## How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/google-search-analysis.git
cd google-search-analysis

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebooks/Google_Search_Analysis_with_Python.ipynb
