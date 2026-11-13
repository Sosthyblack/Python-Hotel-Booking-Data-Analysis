\# Python Hotel Booking Data Cleaning \& Analysis



\## Project Overview

This project uses Python and Pandas to clean and explore a hotel booking dataset. The goal is to identify data quality issues, investigate booking cancellation patterns, and provide useful business recommendations for hotel management.



\## Tools Used

\- Python

\- Pandas

\- Google Colab

\- Jupyter Notebook



\## Data Cleaning

\- Handled missing values in the children, country, agent, and company columns.

\- Identified 31,994 duplicate rows for further investigation.

\- Removed 180 bookings with zero guests.

\- Removed one booking with a negative Average Daily Rate (ADR).

\- Excluded one unusually high ADR value of 5,400.

\- Retained 119,208 bookings in the cleaned dataset.



\## Key Findings

\- Group and Online Travel Agent bookings showed notable cancellation patterns.

\- Data quality checks identified missing values, potential duplicates, and unusual ADR values.

\- Cleaning improved the consistency of the dataset for further analysis.



\## Business Recommendations

\- Investigate cancellation patterns across booking market segments.

\- Consider booking reminders and reservation confirmation procedures.

\- Monitor unusual room rates to improve data quality and reporting accuracy.



\## Limitations

The findings show associations rather than proven causes. Duplicate bookings and unusually high room rates require further investigation before removal decisions are made.



\## Project Files

\- `Python\_Data\_Cleaning\_EDA\_Project.ipynb` — Python notebook containing the analysis.

\- `README.md` — Project documentation.



\## Dataset

Hotel Booking Demand dataset, containing bookings for city and resort hotels.

