Google Search Analysis Project


Introduction:
The Google Search Analysis Project focuses on analyzing search trends to understand what people are searching for and how interest in different topics changes over time. 
With the rapid growth of the internet, analyzing search behavior helps businesses, marketers, and analysts identify trending topics, user interests, and seasonal patterns.
In this project, search trend data was collected using Google Trends through the Python library Pytrends. The analysis was performed using powerful data analytics tools such as Python, Pandas, Matplotlib, and Plotly to process, analyze, and visualize search trend data.
Objective:
The main objective of this project is to identify:
1) First, write a code where, by changing just the keyword, we can search for multiple things.
2) Top 15 countries where the keywords are searched the most, and also create visual representation of it.
3) A world map needs to be plotted showing the countries that search the keyword the most.
4) We need to extract the time-wise interest of the keyword — how it trended in different years.
5) Compare related keywords and plot the graph.


Analysis:

1.	First, write a code where, by changing just the keyword, we can search for multiple things.

Ans- I have setup Pytrends Library and Defined the Keyword. The Keyword is most demanding that is Data Science.

2.	Top 15 countries where the keywords are searched the most, and also create visual representation of it.

Ans- The chart shows which countries search the most for the term “Data Science.” The data is usually obtained from Google Trends using the Pytrends library in Python.

🥇1. India – Interest ≈ 100
•	Highest search interest.
•	Indicates very high demand for data science learning and jobs.
•	Many students and professionals are searching for data science courses and careers.
🥈 2. Kenya – Interest ≈ 98
•	Strong interest in data science.
•	Shows growth in tech and analytics education.
🥉 3. Singapore – Interest ≈ 85
•	Major technology and analytics hub in Asia. High demand for AI and data professionals.
 
3.	A world map needs to be plotted showing the countries that search the keyword the most.
Ans- This is a Choropleth Map (Geographical Heat Map).
•	Each country is colored based on search interest level.
•	Darker colors indicate higher interest.
•	Lighter colors indicate lower interest.
This type of visualization is commonly used in data analytics and business intelligence dashboards.

3️⃣ Color Scale (Legend on the Right)
The color bar shows the interest score from about 45 to 100.
Interpretation:
•	100 → Highest search interest
•	80–90 → Very high interest
•	60–80 → Moderate interest
•	Below 60 → Lower interest
Important:
These values represent relative popularity, not the actual number of searches.

4️⃣ Countries with Highest Interest
🇮🇳 India – Score ≈ 100
•	Darkest color on the map.
•	Indicates the highest search interest in “Data Science.”
•	Large number of students and professionals searching for data science courses and jobs.
🇰🇪 Kenya – High interest
•	Also shown with a dark shade.
•	Indicates growing interest in technology and analytics education.

5️⃣ Countries with Moderate Interest
Countries such as:
•	China
•	Nepal
•	Pakistan
•	Sri Lanka
show moderate to high interest in the topic.
These regions are experiencing:
•	Growth in AI and machine learning
•	Increasing tech education
•	Rising demand for data-related jobs

6️⃣ Countries with Lower Relative Interest
Countries like:
•	United States
•	South Africa
•	Brazil
appear lighter on the map.
This does NOT mean low usage.
Instead, it means:
•	People search many other topics.
•	The relative share of “Data Science” searches is smaller compared to other topics.


 

4.	We need to extract the time-wise interest of the keyword — how it trended in different years.

Ans- 1️⃣ Search Interest Over Time – “Data Science”
What the Chart Shows
This line graph shows how the popularity of the keyword “Data Science” changed over time.
•	X-axis: Date (from 2025 to 2026) and Y-axis: Interest level (0–100)
Meaning of Interest Score
•	100 → Maximum search popularity
•	50 → Moderate interest
•	Below 40 → Lower interest
These scores are relative values, not actual search numbers.

Trend Analysis
Early Period (March – June 2025)
Interest remains moderate between 33–40.
This suggests:
•	Stable but not very high search demand.

Growth Phase (July – September 2025)
Interest increases rapidly:
•	July: around 45–50
•	August–September: 80+
Possible reasons:
•	Increased interest in data science courses
•	Academic semesters starting
•	Growing industry demand

Fluctuation Phase (October – December 2025)
Interest fluctuates between:
•	60 – 85
This indicates consistent global interest in Data Science.

Peak Period (Early 2026)
The graph reaches its highest value close to 100.
This suggests:
•	Major spike in search activity
•	Possibly related to job trends, courses, or AI discussions

Sudden Drop
At the end of the timeline, the interest drops sharply to around 40–45.
Possible reasons:
•	Short-term spike earlier
•	Seasonal search behavior

Key Insight: 
Search interest for Data Science has generally increased over time, showing strong and growing demand for this field.

 

5.	Compare related keywords and plot the graph.

Ans- This graph compares four technology keywords:
•	Data Science
•	Machine Learning
•	Cloud Computing
•	Artificial Intelligence
All keywords are commonly used in modern technology and analytics.

X-axis
Date (2025–2026)
Y-axis
Interest score (0–100)

Keyword Trend Analysis
🔵 Data Science
Moderate but steady interest.
•	Range: 25 – 55
•	Shows consistent popularity
Used in:
•	analytics
•	business intelligence
•	predictive modeling

🟠 Machine Learning
Highest overall interest.
Peak near 100, making it the most searched topic among the four.
Reasons:
•	AI revolution
•	automation
•	predictive algorithms
Machine Learning is a core part of modern AI systems.

🟢 Cloud Computing
Lowest search interest among the four.
Range: 5 – 30
However, it remains important because it powers:
•	cloud infrastructure
•	big data platforms
•	scalable applications

🔴 Artificial Intelligence
Second highest trend after Machine Learning.
Range: 20 – 75
Interest increases significantly during AI boom periods.
AI includes:
•	robotics
•	natural language processing
•	computer vision

Important Observations
1️⃣ Machine Learning dominates searches
It reaches the highest interest score, indicating strong global curiosity and adoption.
2️⃣ AI and Data Science grow together
Their trends rise during similar periods because they are closely related fields.
3️⃣ Cloud Computing grows slowly
Even though search interest is lower, it remains essential for data storage and large-scale computing.

Business / Industry Insight
This type of analysis helps:
Companies
Understand technology trends.
Education Platforms
Create courses based on popular skills.
Job Seekers
Identify high-demand technology skills.

 


Conclusion: 
By analyzing these trends, the project demonstrates how search data can provide valuable insights for digital marketing, business decision-making, and market research. 
The visualizations and statistical analysis help transform raw search data into meaningful insights that can guide companies in understanding consumer interests and predicting future trends.

