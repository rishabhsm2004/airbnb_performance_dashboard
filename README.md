# Airbnb Performance Dashboard

An interactive Airbnb performance dashboard for exploring listing trends, review activity, and property metrics. This project includes a Power BI dashboard, source datasets, and supporting data dictionary files to help users understand and analyze the data.

## Overview

This repository contains a business intelligence dashboard focused on Airbnb performance insights. It is designed to help users evaluate:

- Listing-level performance and pricing trends
- Review activity and sentiment signals
- Property and host metrics across listings
- Market performance patterns using structured Airbnb data

The dashboard is provided as a Power BI report (`Airbnb Dashboard.pbix`) and a PDF export (`Dashboard.pdf`) for quick viewing and sharing.

## Repository Structure

```text
.
├── Airbnb Dashboard.pbix
├── Dashboard.pdf
├── .gitattributes
└── dataset/
    ├── Listings.csv
    ├── Listings_data_dictionary.csv
    ├── Reviews.csv
    └── Reviews_data_dictionary.csv
```

## Data Files

### `dataset/Listings.csv`
Contains property or listing-level data such as listing attributes, room characteristics, and performance-related fields.

### `dataset/Listings_data_dictionary.csv`
Explains the meaning and description of each column in the listings dataset.

### `dataset/Reviews.csv`
Contains review-related information used for analyzing review activity and engagement patterns.

### `dataset/Reviews_data_dictionary.csv`
Provides definitions and context for the review dataset columns.

## Dashboard

- Power BI file: `Airbnb Dashboard.pbix`
- PDF snapshot: `Dashboard.pdf`

To explore the dashboard:

1. Open `Airbnb Dashboard.pbix` in Power BI Desktop.
2. Refresh the data if needed, depending on your environment.
3. Use the report to analyze listing performance, review activity, and property trends.

## Use Cases

This repository can be used for:

- Airbnb market analysis
- Performance benchmarking across properties
- Review trend analysis
- Data exploration and dashboard presentation
- Learning data storytelling with Power BI

## Notes

This repository is intended for analysis and visualization rather than production deployment. The dataset files and supporting dictionaries are included to make the dashboard easier to understand and extend.

## License

This project does not currently specify a license file. Please check with the repository owner before reusing or distributing the contents beyond personal or educational use.
