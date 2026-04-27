# SuperStore Executive Dashboard

## Overview
This is a comprehensive executive dashboard for analyzing SuperStore sales data from FY 2018–2021. The dashboard provides interactive visualizations of key performance indicators including sales, profits, regional performance, category breakdowns, and more. Built for Bajaj Executive Intelligence, it covers 9,994 transactions across 793 customers in the US retail market.

## Features
- **Interactive Filters**: Filter data by year, region, segment, category, and shipping mode
- **Key Metrics**: Total sales, profit margins, and transaction counts
- **Visualizations**:
  - Monthly sales and profit trends
  - Category and sub-category performance
  - Regional sales distribution
  - Top states analysis
  - Shipping mode insights
  - Segment-wise yearly sales
  - Profit vs. discount analysis
  - Order heatmap by day of week and month
  - Scatter plot of sub-categories by sales and profit
- **Responsive Design**: Optimized for desktop viewing with a clean, professional interface

## Technologies Used
- **HTML5**: Structure and layout
- **CSS3**: Custom styling with CSS variables for theming
- **JavaScript**: Data manipulation and interactivity
- **Chart.js**: Chart rendering library (loaded from CDN)
- **Google Fonts**: DM Serif Display and DM Sans for typography

## Data Source
The dashboard uses embedded JSON data derived from SuperStore sales records. The raw data file `SuperStore Data.xlsx` is included for reference.

## How to Use
1. Open superstore_dashboard.html in a modern web browser
2. Use the filter controls at the top to explore different data segments
3. Click "Apply Filters" to update all charts
4. Click "Reset" to clear all filters

## File Structure
- superstore_dashboard.html: Main dashboard file containing HTML, CSS, and JavaScript
- `SuperStore Data.xlsx`: Raw data source

## Screenshots
-<img width="1745" height="523" alt="image" src="https://github.com/user-attachments/assets/51ce5c94-7f1c-4b39-81fa-edd4a090f2f9" />

-<img width="1127" height="827" alt="image" src="https://github.com/user-attachments/assets/3aa00109-3c42-4356-a7de-ac932d17fcb3" />

-<img width="532" height="532" alt="image" src="https://github.com/user-attachments/assets/dadd02d4-dc32-4035-bb2d-f35df130a89f" />

-<img width="830" height="553" alt="image" src="https://github.com/user-attachments/assets/bc5833a3-5463-4a21-ac26-22c9dddabf2e" />

-<img width="830" height="553" alt="image" src="https://github.com/user-attachments/assets/6631fdf5-d628-481f-ac6e-f04240e39a6e" />

-<img width="525" height="385" alt="image" src="https://github.com/user-attachments/assets/ab147071-be40-4987-bb42-dac8a21c19e2" />

-<img width="525" height="385" alt="image" src="https://github.com/user-attachments/assets/51ee8af9-3b55-4787-ac88-8cca564a82a7" />

-<img width="1127" height="902" alt="image" src="https://github.com/user-attachments/assets/f7dfddc8-273e-456c-9ee2-e30046f26ba2" />

-<img width="532" height="532" alt="image" src="https://github.com/user-attachments/assets/31c3df9b-bc71-47e9-81cc-01af77b808b7" />


## Code Reference
The main code is in superstore_dashboard.html. Key sections:
- **Data**: Embedded in the `RAW` JavaScript object
- **Styling**: CSS variables and responsive design
- **Charts**: Chart.js configurations for various visualizations
- **Filters**: JavaScript functions for data filtering and chart updates

## Browser Compatibility
Requires a modern browser with JavaScript enabled. Tested on Chrome, Firefox, and Edge.
