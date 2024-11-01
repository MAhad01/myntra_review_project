# Myntra Review Scraper

This project is a web application that allows users to scrape product reviews from Myntra (a popular Indian e-commerce website) based on a specified query. Users can enter a product query and specify the number of products they want to search for. The app then scrapes reviews for these products, displays them in a table, and provides an option to save the data to MongoDB. The results are also available as a downloadable spreadsheet.

![App Screenshos](images\ss1.png)
![App Screenshos](images\ss2.png)
![App Screenshos](images\ss3.png)
![App Screenshos](images\ss4.png)
![App Screenshos](images\ss5.png)
![App Screenshos](images\ss6.png)
![App Screenshos](images\ss7.png)
![App Screenshos](images\ss8.png)

## Features

- **User Input**: Accepts a product query and the desired number of products to search.
- **Web Scraping**: Collects reviews for the specified product from Myntra.
- **Spreadsheet Export**: Displays scraped reviews in a data frame with options to save them to MongoDB and download them as a `.csv`.
- **Streamlit Interface**: An interactive UI for easy operation.

## Technology Stack

- **Python**: The core language for web scraping, data handling, and backend logic.
- **Streamlit**: Framework to build the interactive web application.
- **MongoDB**: Database to store the scraped reviews.
- **BeautifulSoup** and **Requests**: Used for the web scraping functionality.

## Project Structure

- **app.py**: Main application file for the Streamlit interface, handles user inputs and displays data.
- **src/scraper/scrape.py**: Contains the web scraping logic to extract reviews.
- **src/cloud_io.py**: Defines `MongoIO`, a class to manage saving scraped data to MongoDB.
- **src/constants.py**: Stores any constants used, like session keys.
- **requirements.txt**: Lists required Python packages.
- **README.md**: Project documentation.

## Requirements

- **Python 3.x**: Ensure you have Python 3 installed.
- **Streamlit**: For creating the web application interface.
- **pandas**: For data handling and exporting.
- **pymongo**: For interacting with MongoDB.
- **BeautifulSoup4** and **Requests**: For handling the web scraping.

To install the requirements, run:
```bash
pip install -r requirements.txt
