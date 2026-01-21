# Washington State Climate Dashboard

An interactive dashboard displaying 100 years of temperature and precipitation data for the five largest cities in Washington State.

## Live Demo

[View the Dashboard](https://rboenish.github.io/test-dashboard/)

## Features

- **100 Years of Data**: Annual climate data from 1924-2024
- **5 Washington Cities**: Seattle, Spokane, Tacoma, Vancouver, Bellevue
- **Dual-Axis Chart**: Temperature (°F) on left, Precipitation (inches) on right
- **Multi-City Comparison**: Select multiple cities to compare side-by-side
- **Visual Differentiation**:
  - Solid lines for temperature
  - Dotted lines for precipitation
  - Color-coded by city
- **Year Range Filter**: Focus on specific time periods
- **Data Export**: Download selected data as CSV
- **Interactive Tooltips**: Hover for detailed values
- **Responsive Design**: Works on desktop and mobile

## Technologies

- HTML5 / CSS3
- JavaScript (Vanilla)
- Chart.js for visualizations

## Data

The dashboard uses generated climate data based on historical averages for each city:

| City | Avg Temp (°F) | Avg Precip (in) |
|------|---------------|-----------------|
| Seattle | 52 | 37 |
| Spokane | 47 | 17 |
| Tacoma | 51 | 40 |
| Vancouver | 53 | 43 |
| Bellevue | 51 | 38 |

Data includes realistic year-to-year variation and a slight warming trend over the century.

## Usage

1. **Select Cities**: Check/uncheck cities to compare
2. **Set Year Range**: Enter start and end years
3. **Click Update**: Refresh the chart with selections
4. **Export Data**: Download a CSV of the visible data

## Local Development

Simply open `index.html` in a web browser. No build process required.
