# stock-revenue-analysis
Stock &amp; Revenue Data Analysis and Visualization
# Financial Data Analysis and Visualization

## Overview

This project involves extracting, processing, and visualizing stock and revenue data for Tesla and GameStop. The analysis focuses on historical share prices and revenue figures, providing insights through interactive graphs.

## Project Structure

- **Data Extraction**: 
  - Used `yfinance` to fetch historical stock data for Tesla and GameStop.
  - Downloaded revenue data from provided URLs using `requests`.

- **Data Processing**: 
  - Parsed HTML tables containing revenue data using `BeautifulSoup`.
  - Cleaned and formatted revenue data for analysis.

- **Visualization**: 
  - Created interactive plots using `Plotly` to visualize stock prices and revenue over time.
  - Generated two subplots: one for historical share prices and one for revenue.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: `yfinance`, `pandas`, `requests`, `beautifulsoup4`, `plotly`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/financial-data-visualization.git
   cd financial-data-visualization
