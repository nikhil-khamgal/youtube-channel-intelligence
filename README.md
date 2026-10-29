# YouTube Channel Intelligence

**A YouTube Analytics Project using Python, SQL, SQLite, and Power BI**

## Project Overview

YouTube Channel Intelligence is a data analytics project designed to collect, store, analyze, and visualize publicly available YouTube channel and video statistics.

The project uses the YouTube Data API to retrieve data, Python to support data collection, SQLite for structured storage, SQL for data querying, and Power BI to create interactive visual reports.

The goal is to transform raw YouTube statistics into meaningful information that helps compare video performance, understand publishing activity, and evaluate audience engagement.

## Business Problem

YouTube channels generate large amounts of video performance data, but understanding that data requires more than looking at individual view counts.

This project provides a structured analytics workflow to explore questions such as:

- Which videos receive more views and engagement?
- How do likes and comments vary across videos?
- What publishing patterns can be observed?
- How does video performance differ within a channel?
- Which metrics can help compare content performance?

## Project Objectives

- Collect channel and video statistics through the YouTube Data API.
- Organize the collected data for structured storage and analysis.
- Use SQLite and SQL to manage and query the data.
- Connect the database to Power BI through ODBC.
- Build visual reports to compare video performance and engagement metrics.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data collection and processing |
| YouTube Data API | Retrieving public channel and video statistics |
| Jupyter Notebook | Executing and documenting the data workflow |
| SQLite | Storing structured data |
| SQL | Querying and analyzing stored data |
| ODBC | Connecting the database to Power BI |
| Power BI | Data visualization and reporting |

## Project Workflow

YouTube Data API → Python Data Collection → SQLite Database → SQL Queries → ODBC Connection → Power BI Dashboard

## Analysis Areas

The project is designed to explore the following areas:

- **Video Performance:** Compare views across videos.
- **Engagement Analysis:** Examine likes and comments.
- **Publishing Activity:** Explore upload frequency and publishing patterns.
- **Channel Performance:** Compare available performance metrics across videos.
- **Interactive Reporting:** Present performance data through Power BI visualizations.

*Note: These are the project's analysis areas. Specific findings should be documented after validating the results from the collected data.*

## Repository Structure

```text
YouTube-Channel-Intelligence/
│
├── Power Bi File/
│   └── Youtube Channal Dashboard.pbix
│
├── Setupguide/
│   └── YouTube_SQLite_ODBC_Publishing_Guide.pdf
│
├── code and database/
│   └── YouTube Data Collection_sql_connected .ipynb
│
├── README.md
└── .gitignore
```

## How to Explore the Project

1. Clone or download this repository.
2. Review the setup guide in the `Setupguide` folder.
3. Open the Jupyter Notebook in `code and database`.
4. Configure the required API credentials and database connection locally.
5. Run the notebook according to the setup instructions.
6. Open the Power BI `.pbix` file using Power BI Desktop and configure the required data connection.

**Prerequisites:** Python, Jupyter Notebook, a Google Cloud project with the YouTube Data API enabled, SQLite, the required ODBC driver, and Power BI Desktop.

The exact setup requirements may depend on your local environment and the connection configuration.

## Key Learning Outcomes

This project brings together several practical data analytics concepts:

- Working with an external API to collect data.
- Organizing data in a relational database.
- Using SQL for structured data analysis.
- Connecting a database to a business intelligence tool.
- Presenting data through visual reports.
- Building an end-to-end analytics workflow.

## Limitations

The analysis is based on data available through the YouTube Data API. It does not provide private channel-owner analytics, such as individual viewer identities or private audience retention data.

## Future Improvements

- Add automated data refresh and historical performance tracking.
- Develop additional SQL queries for deeper analysis.
- Include validated findings and key performance indicators.
- Improve dashboard interactivity and reporting documentation.



*This project was developed for learning and demonstrating practical data analytics skills.*
