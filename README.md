# Transfermarkt Player Data Scraper

This Python script allows you to extract/scrap player data from the Transfermarkt website and save it as a CSV or Excel file.

<img src="https://i.ibb.co/jGSQLMX/Screenshot-2023-07-31-193445.png" alt="Alt text" title="Transfermarkt Player Data Scraper">

## Features

- Fetch player data from the Transfermarkt website
- Select specific fields to extract (e.g., Shirt Number, Name, Age, Position, Nationality, Market Value)
- Option to remove the € sign from the Market Value field
- Option to convert the Market Value to an expanded form (e.g., 6M to 6,000,000)
- Save the extracted data as a CSV or Excel file

## How to Use

### Executable Version

Use the provided .exe build. Simply download the `Transfermarkt.Scraper.zip` from the [Releases](https://github.com/CoderRafay/TransfermarktPlayerDataScraper/releases) section and run it on your machine.

### Run via Source Code

1. Clone the repository or download the `scraper.py` file.
2. Make sure you have Python and the required libraries installed (`requests`, `csv`, `openpyxl`, `bs4`, `tkinter`, and `Pillow`).
3. Run the `scraper.py` script using Python.
4. Enter the Team URL from Transfermarkt you want to scrape.
5. Select the fields you want to extract.
6. Choose additional options, if needed.
7. Click "Extract Data and Save" to save the data to a file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
