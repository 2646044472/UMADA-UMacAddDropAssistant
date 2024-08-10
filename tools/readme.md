# tools

This project aims to collect and analyze course ratings for the University of Macau (UM). It includes tools for web scraping teacher ratings and merging this data with course schedules.

The main components are:
1. `scrabble.ipynb`: A Jupyter notebook file for collecting teacher ratings.
2. `data_merge.ipynb`: A Jupyter notebook file to merge scraped ratings with course schedule information.

Course schedule data (CM.xlsx and GE.xlsx) can be obtained from the [UM Course Enrolment page](https://reg.um.edu.mo/current-students/enrolment-and-examinations/course-enrolment/class-schedule/).

Please note that teacher ratings are frequently updated. The provided code allows you to fetch the most recent data. However, use the scraper responsibly and set appropriate intervals between scraping sessions to avoid overloading the server.

This project is for educational purposes only. Users are responsible for ensuring their use of this tool complies with UM's policies and relevant regulations. The project is not responsible for any consequences resulting from misuse or excessive scraping activities.

Note that web page structures may change over time. You might need to update the scraping code accordingly if you encounter any issues.


```
cd tools
pip install -r requirements.txt
jupyter notebook
```
