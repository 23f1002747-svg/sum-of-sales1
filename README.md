# Product Sales Dashboard

This webpage displays a sales dashboard for products. It includes:
- A Bootstrap-styled table listing each product with total sales and quantity.
- Filters to select region and currency.
- Dynamic calculation of total sales, updated according to selected filters and currency.

## Features
- Loads sales data from `data.csv`.
- Loads currency conversion rates from `rates.json`.
- Filters sales by region.
- Converts total sales into selected currency using conversion rates.
- Keeps total sales accurate based on applied filters.

## Usage
1. Place `data.csv` and `rates.json` in the same directory as `index.html`.
2. Open `index.html` in a web browser.
3. Use the dropdowns to filter by region and select currency.
4. View the updated sales data and total.

## Data Files
- `data.csv`: Contains sales data with columns: Product, Region, Quantity, Total Sales (USD).
- `rates.json`: Contains currency conversion rates relative to USD.

## License
This project is licensed under the MIT License.
