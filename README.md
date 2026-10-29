# YouTube Channel Intelligence

A YouTube analytics project built to collect, store, analyze, and visualize channel and video performance data.

The main idea behind this project is simple: take raw YouTube data and turn it into useful insights about content performance, publishing patterns, and audience engagement.

## What This Project Does

The project collects YouTube channel and video data and stores it in a structured database. The data is then used for analysis and Power BI reporting.

The analysis focuses on:

- Total views and video performance
- Likes and comments
- Video-level comparisons
- Upload activity
- Publishing patterns
- Audience engagement
- Overall channel performance

## How It Works

YouTube Data API
        ↓
Data Collection
        ↓
SQLite Database
        ↓
ODBC Connection
        ↓
Power BI
        ↓
Interactive Reports

## Tools Used

- **YouTube Data API** — Data collection
- **Python / Jupyter Notebook** — Data extraction and processing
- **SQLite** — Data storage
- **SQL** — Database queries and analysis
- **ODBC** — Database connectivity
- **Power BI** — Dashboard and visualization

## Project Structure

```text
YouTube-Channel-Intelligence/
│
├── Power bi file/
│
├── Sample report/
│   ├── Dhruv Rathee.pdf
│   ├── Jasmine Sandlas.pdf
│   ├── Karan Aujla.pdf
│   └── Mumbiker Nikhil.pdf
│
├── Setupguide/
│
└── code and database/
    └── YouTube Data Collection_sql_connected .ipynb
