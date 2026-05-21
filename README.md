# Hotel Booking Analysis

## Project Overview

This project analyzes hotel booking data to identify booking trends, cancellation behavior, seasonal patterns, and revenue insights.

The analysis is performed using Python, Pandas, and Matplotlib. The project automatically generates charts and a PowerPoint report to present insights in a simple and structured format.

This project was created as part of an internship assessment.

---

## Dataset Information

The dataset contains **30,000 hotel booking transactions** with information such as:

- Booking channel
- Room type
- Star rating
- Booking value
- Stay duration
- Booking status
- Coupon usage
- Seasonal booking trends

---

## Features

- Booking trend analysis
- Cancellation behavior analysis
- Revenue analysis by booking channel
- Seasonal and monthly trend analysis
- Coupon vs cancellation analysis
- Data visualizations (PNG charts)
- Automated PowerPoint report generation

---

## Tech Stack

- Python
- Pandas
- Matplotlib
- Python-PPTX

---

## Project Structure

```text
Hotel_Bookings_Full_Report/
│── hotel_analysis.py
│── Hotel_bookings_final.csv
│── requirements.txt
│── README.md
│── chart1_overview.png
│── chart2_trends.png
│── chart3_revenue.png
│── Hotel_Bookings_Analysis.pptx
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Shreyansh301/Assignment.git
cd Assignment
```

Install dependencies:

```bash
pip3 install -r requirements.txt
```

---

## Run the Project

Run the Python script:

```bash
python3 hotel_analysis.py
```

---

## Output

After running the script, the following files are generated automatically:

### Charts
- `chart1_overview.png`
- `chart2_trends.png`
- `chart3_revenue.png`

### PowerPoint Report
- `Hotel_Bookings_Analysis.pptx`

The report includes:

- Key observations
- Root cause analysis
- Business recommendations
- Final summary
- Visual charts and trends

---

## Key Insights

Some important observations from the analysis:

- Web bookings generated the highest revenue and had lower cancellation rates.
- Travel Agent bookings showed the highest cancellation behavior.
- Standard rooms had higher cancellations compared to Deluxe rooms.
- Booking activity was highest during certain months, showing seasonal demand.
- Coupon usage had limited impact on cancellation behavior.

---

## Future Improvements

Possible improvements for this project:

- Add interactive dashboards
- Improve visualizations with advanced charts
- Add predictive analysis for cancellations
- Create a web-based reporting dashboard