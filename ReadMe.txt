Project Objective: The aim of this project is to analyze fishing data from Connecticut with the goal of discovering new fishing locations and gaining insights into local fishing trends.

Project Process:

Step 1: Data Acquisition
- Utilizing a web scraper in Jupyter Notebook, data is manually retrieved from the CT DEEP Fish Community Data Map Located here: (https://cteco.uconn.edu/projects/fish/viewer/index.html)
- The web scraper employs Selenium and BeautifulSoup to download all available public data at the town level.
- It identifies and retrieves all town names, searches for each town in the website's search bar, clicks the "download to CSV" prompt, and saves the data with the respective town name in the designated Step 1 directory.

Step 2: Data Cleaning
- Jupyter Notebook is used to clean the downloaded data.
- All downloaded data from Step 1 is aggregated into a single comprehensive data frame.
- After aggregation, the data is cleaned to eliminate any missing values (NaN).
- Further filtering is applied to remove irrelevant fish species data.
- The data frame is then restructured and transformed, consolidating information into a single count column.

Step 3: Data Visualization
- Data visualization is performed by transferring the cleaned data into an Excel dashboard pivot table template.
- Users are encouraged to explore the data independently and derive relevant insights.

This directory offers a structured method for retrieving and analyzing forthcoming fish data. If you're interested in trying it out, follow the steps below:

1. Open the Jupyter Notebook located in the Step 1 directory.
2. Transfer all files downloaded from Step 1 to the Step 2 directory.
3. Execute the Jupyter Notebook in the Step 2 directory (you can customize it by adjusting parameters like the number of fish species to analyze).
4. Move the "Clean Data.xlsx" file generated from Step 2 to the Step 3 directory.
5. Access the "Dashboard.xlsx" file and the "Clean Data.xlsx" file in the Step 3 directory.
6. Copy all data from the "Clean Data.xlsx" file to the sheet named "raw data" in the "Dashboard.xlsx" file.
7. Dive into the data and explore!