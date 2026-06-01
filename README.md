# User Survey Analysis Dashboard

An interactive dashboard that analyzes user-feedback survey responses for an
AI SaaS product, turning raw open-text and multiple-choice answers into a clean,
explorable visual report.

> This is a portfolio demo built with **synthetic data** for a **fictional product**.
> The real version was built on actual survey data during a business analytics internship.

## What it does
- Cleans and normalizes messy survey data (merging inconsistent free-text answers,
  grouping fields of study into research domains, coding open-text feature requests into themes)
- Visualizes the results across five sections: advocacy & satisfaction, who the users are,
  acquisition channels, feature requests, and trend over time
- Fully interactive — hover any chart for exact values

## Built with
- HTML / CSS / JavaScript
- [Chart.js](https://www.chartjs.org/) for the visualizations
- Data cleaning & aggregation in Python (pandas)
