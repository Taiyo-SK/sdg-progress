# ProgressSDG
ProgressSDG is a tool for viewing global progress on the United Nations Sustainable Development Goals (SDGs). The single-page application covers 17 milestones and hundreds of indicators across environmental, social, and governance (ESG) initiatives. Using data sourced from the UN SDG API, ProgressSDG dynamically updates its main dashboard to display the goal the user wants to see. These are grouped into three sections: a summary of progress, related goal details and indicators, and  an assessment of data quality.

## Tech Stack
- Postgres database
- SQLAlchemy object relational mapper
- Python/Flask server and Jinja
- AJAX for fetching data from the db
- Chart.js for dashboard charts 
- Bootstrap UI
- Data from the UN SDG API

## Features
0. Navigable list of all 17 SDGs (Bootstrap cards and Jinja templating)
1. Summary section displaying the SDG title, progress completion (progress bar) and number of years remaining (pie chart)
2. Details section with the SDG description and its associated indicators (Bootstrap table and vanilla JavaScript)
3. Assessment section illustrating whether or not an SDG's progress data is on-track and up-to-date (chart.js)

## Screenshots
![alt text](https://github.com/Taiyo-SK/progressSDG/static/screenshots/overview.png "page overview")
![alt text](https://github.com/Taiyo-SK/progressSDG/static/screenshots/summary.png "summary section")
![alt text](https://github.com/Taiyo-SK/progressSDG/static/screenshots/details.png "details section")
![alt text](https://github.com/Taiyo-SK/progressSDG/static/screenshots/assessment.png "assessment section")