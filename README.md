# Crypto-ETL Project

## Overview

This project demonstrates an end-to-end data engineering pipeline for cryptocurrency data using various tools and technologies. The pipeline consists of three main scripts: `extract.py`, `transform.py`, and `app.py`. The project fetches data from the CoinMarketCap API, transforms it using PySpark, stores it in a PostgreSQL database, and visualizes the data using a Flask web application.

## Project Structure

- `crypto_data_extraction.py`: Extracts cryptocurrency data from the CoinMarketCap API and saves it to a JSON file.
- `transform.py`: Transforms the extracted data using PySpark and loads it into a PostgreSQL database.
- `app.py`: Visualizes the transformed data using Flask and Plotly.

## Prerequisites

- Python 3.6+
- PostgreSQL
- Flask
- PySpark
- SQLAlchemy
- Plotly
- pandas
- requests
- python-dotenv
