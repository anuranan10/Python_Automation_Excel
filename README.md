# Excel Price Correction Tool

This Python script processes an Excel workbook, adjusts prices in a specific column, and generates a bar chart of the corrected prices. It uses the `openpyxl` library to interact with Excel files.

## Features

- Reads data from a given Excel file.
- Corrects prices in the third column by applying a 10% discount.
- Writes the corrected prices to the fourth column.
- Creates a bar chart to visualize the corrected prices.
- Saves the updated Excel workbook.

## Requirements

- Python 3.x
- `openpyxl` library

## Installation

1. Ensure you have Python installed on your system.
2. Install the `openpyxl` library by running:
   ```bash
   pip install openpyxl
