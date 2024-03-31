UK-Foods-Standards-Analysis-NOSQL

Overview:
In collaboration with "Eat Safe, Love," a prominent food magazine, this project employs NoSQL databases to scrutinize food hygiene ratings across the UK. Utilizing MongoDB, a NoSQL database, and Jupyter Notebook for data manipulation and analysis, our objective is to furnish the magazine's editors with data-driven insights to shape the focus of future articles.

Objective:
The primary aim is to delve into food hygiene ratings provided by the UK Food Standards Agency, uncovering trends and noteworthy establishments. This analysis will equip "Eat Safe, Love" journalists and food critics with valuable insights, facilitating informed decisions regarding future content direction.

Methodology:
Part 1: Database and Jupyter Notebook Setup
Imported establishments.json into a MongoDB database named uk_food, establishing a collection titled establishments.
Utilized PyMongo to engage with the database, ensuring successful data import and priming the collection for analysis.

Part 2: Database Update
Added a new halal restaurant, "Penang Flavours," to the database, enriching the dataset with current market entries.
Updated establishment data to uphold accuracy and relevance, including rectifying data types for latitude, longitude, and rating values.

Part 3: Exploratory Analysis
Focused on addressing pivotal questions for "Eat Safe, Love," including:
Identifying establishments with specific hygiene scores.
Exploring high-rated establishments in London.
Analyzing the top 5 establishments near "Penang Flavours" with a rating of 5.
Assessing hygiene scores across different Local Authority areas.

Key Findings:

A total of 41 establishments received a hygiene score of 20.
In London, 33 establishments earned a rating value of 4 or higher.
Identified the top 5 establishments with a perfect rating of 5, based on proximity to "Penang Flavours," offering a targeted list for potential reviews.
Analysis of Local Authority areas revealed significant disparities in hygiene scores, indicating areas for both improvement and commendation.

Challenges and Solutions:
Data Import: Initially, the command for importing data into MongoDB was omitted but rectified by documenting the mongoimport command within the Jupyter Notebook.
Data Accuracy: Corrected some number values stored as strings to their accurate numeric data types to ensure precise analysis.
Query Accuracy: Adjustments were made to accurately count establishments in London with a rating value greater than or equal to 4, utilizing regex for precise matching.

Conclusion:
This project highlights the efficacy of NoSQL databases in managing and analyzing extensive datasets. By furnishing "Eat Safe, Love" with actionable insights into food hygiene ratings across the UK, we empower them to make informed decisions regarding content direction, thereby enhancing their readers' dining experiences.

