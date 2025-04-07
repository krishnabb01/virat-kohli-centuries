# virat-kohli-centuries
🏏 Project Title: Virat Kohli Centuries Analysis using Power BI
📄 Project Description:
This Power BI project presents an interactive analysis of Virat Kohli's international centuries across formats. The dataset includes match-wise century details, such as runs scored, dismissal status (Out/Not Out), and performance trends.

The objective of this project is to showcase:

Virat Kohli's batting consistency

The frequency of "Not Out" vs "Out" innings

Run distribution insights

Comparison of high scores across different opponents or venues (if applicable)

📊 Key Features & Visuals:
Runs Breakdown: A bar chart showing the runs scored in each century.

Dismissal Status: A pie chart comparing how often Kohli was Out vs Not Out during centuries.

Century Trends Over Time: A line or scatter plot showing how his scores evolved over his career.

Stat Cards: KPIs showing:

Total Centuries

Average Score in Centuries

Highest Score

Number of Not Outs

🔍 Data Transformation Highlights (Power Query / M Language):
Added a custom column to detect Out/Not Out using:

m
Copy
Edit
if Text.EndsWith([Runs], "*") then "NotOut" else "Out"
Cleaned the Runs column by removing the asterisk (*) and converting to numeric type for analysis.

Sorted and indexed scores chronologically (optional).

📦 Tools Used:
Power BI Desktop

Power Query (M Language)

Data Modeling

Custom Measures (DAX)

Cleaned data manually or through Power BI for better analysis

🎯 Outcome:
This dashboard gives a clear, visual summary of Kohli's legendary batting achievements. It helps cricket fans and data enthusiasts explore patterns in his century-making career.

