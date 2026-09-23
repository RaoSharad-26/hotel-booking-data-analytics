\# Hotel Booking Data Analytics Project



\## Project Overview



This project analyzes hotel booking data to identify meaningful patterns in booking cancellations, guest behavior, room assignment, and guest origin markets.



The project follows the data analytics workflow covered during the internship:



\*\*Data Cleaning → Data Analysis → Visualization → Observation → Business Insight → Hypothesis → Recommendation\*\*



\## Objective



The objective of this project is to analyze the hotel booking dataset, identify meaningful patterns from the data, and convert those findings into business insights, hypotheses, and recommendations.



\## Business Questions



\### 1. Lead Time and Cancellation Rate



What is the cancellation rate for bookings with a long lead time (>90 days) compared to short lead time bookings (<30 days)?



\### 2. Room Reassignment and ADR



Which reserved room types are most frequently reassigned to a different room type upon check-in, and how does ADR differ between reassigned and non-reassigned bookings?



\### 3. Special Requests, Parking and Cancellation



Do guests who submit special requests or request parking spaces have a different cancellation rate compared with guests with zero requests?



\### 4. Repeat Guests and Booking Behaviour



How do repeat guests compare with first-time guests in terms of cancellation rates and average lead times?



\### 5. Origin Markets and Cancellation Rate



Which guest origin countries have the highest cancellation rates among markets with at least 500 total bookings?



\## Data Preparation



The dataset was cleaned and validated in Google Sheets before being used for analysis.



The cleaned dataset was then loaded into Google Colab for analysis using Python.



\## Analysis Workflow



1\. Cleaned and validated the dataset in Google Sheets.

2\. Loaded the cleaned dataset into Google Colab.

3\. Performed exploratory data analysis using Python.

4\. Created visualizations for the five business questions.

5\. Derived observations from the visualizations.

6\. Converted observations into business insights.

7\. Developed three hypotheses based on selected insights.

8\. Proposed three business recommendations based on the strongest insights.



\## Key Insights



\- Long-lead-time bookings showed a higher observed cancellation rate than short-lead-time bookings.

\- Room reassignment occurred in a minority of bookings and was associated with a difference in observed ADR.

\- Bookings with special requests or parking requirements showed a lower observed cancellation rate than bookings with neither.

\- Repeat guests showed lower observed cancellation rates and shorter average lead times than first-time guests.

\- Cancellation rates varied substantially across high-volume guest origin markets.



\## Hypotheses



Three hypotheses were developed from the strongest insights identified during the analysis.



These hypotheses represent possible explanations for the observed patterns and are not treated as proven causes.



\## Recommendations



Three business recommendations were developed from the strongest insights and hypotheses.



The recommendations focus on:



\- Targeted communication for long-lead-time bookings.

\- Follow-up communication for bookings with zero special requests and parking requirements.

\- Targeted short-notice communication or offers for repeat guests.



These recommendations are proposed actions based on the observed patterns and are not presented as proven causal solutions.



\## Tools Used



\- Google Sheets — Data cleaning and validation

\- Python — Data analysis

\- Google Colab — Analysis environment

\- Pandas — Data manipulation and analysis

\- Matplotlib — Data visualization

\- gspread — Loading the cleaned Google Sheet data into Python



\## Project Files



| File | Description |

|---|---|

| `Hotel\_Booking\_Analysis.ipynb` | Complete Python analysis notebook |

| `requirements.txt` | Python packages required for the project |

| `README.md` | Project documentation |

| `Hotel\_Booking\_Analysis\_Report.pdf` | Project report |



\## How to Run



The project was developed using Google Colab.



1\. Open `Hotel\_Booking\_Analysis.ipynb` in Google Colab.

2\. Run the notebook from the beginning.

3\. Authenticate with a Google account when prompted.

4\. The notebook connects to the Google Sheet containing the cleaned dataset.

5\. Run the cells sequentially to reproduce the analysis and visualizations.



\## Dataset



The project uses the hotel booking dataset selected for the internship project.



The dataset was cleaned and validated in Google Sheets and subsequently loaded into Google Colab for analysis.



\*\*Dataset Link:\*\*  

https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand



\## Limitations



\- The analysis identifies observed patterns and associations; it does not establish causation.

\- The hypotheses represent possible explanations for observed patterns and were not independently tested.

\- The lead-time analysis specifically compares bookings made under 30 days and over 90 days in advance.

\- The origin-market analysis considers countries with at least 500 total bookings.

\- The recommendations are proposed actions based on the observed findings and should be evaluated before being implemented as business policies.

