🏏 ICC Cricket World Cup 2023: Power BI Analytics Dashboard
🚀 Project Overview
This project is an end-to-end Data Analytics solution that transforms raw ICC World Cup 2023 statistics into an interactive dashboard. It provides a 360-degree view of player performances, enabling users to analyze batting and bowling metrics through a highly personalized and interactive interface.

🛠️ Technical Architecture & Data Pipeline
Data Sourcing: Integrated data from multiple sources, including Excel workbooks and SQL databases.

Power Query (ETL): Performed extensive data cleaning, including resolving Type Mismatch errors (0x80020005) and handling null values to ensure data integrity.

Data Modeling: Established a relational schema connecting Batting_Stats, Bowling_Stats, and Player_Metadata to allow for seamless cross-filtering.

System Resilience: Successfully managed project delivery despite hardware challenges, including a system SSD crash and lab environment freezes during development.

🧠 Advanced DAX Implementation
I authored custom DAX measures to enhance the user experience and analytical depth:

Dynamic UI Logic: Implemented HASONEVALUE and SELECTEDVALUE to ensure the dashboard remains clean. For example, the Player Name only appears when a specific player is selected in the slicer, preventing "alphabetical default" errors.

Custom Bowling Figures: Created a complex string-based measure to display figures in the traditional Wickets/Runs format (e.g., 5/24) rather than a mathematical division.

Zero-Default State: Designed logic to ensure visuals remain blank or show a placeholder when no filter is active.

📊 Key Insights & Features
Performance Tracking: Detailed analysis of top scorers like Virat Kohli (765 runs) and leading wicket-takers like Mohammad Shami.

Power Hitting Analysis: A dedicated visual correlation between boundaries (4s/6s) and scoring efficiency (Strike Rate).

Mobile Optimized: Developed a custom Mobile Layout for stakeholders to access insights on smartphones.

Slicer Synchronization: Ensured that filters applied on one page automatically update related visuals across the entire report.

🎮 Interactive Tournament Trivia
Can you find these answers using my dashboard?

The Milestone: Who scored exactly 765 runs to become the top scorer?

The Finisher: Which player maintained a Strike Rate above 150.00?

The Wall: Find the player with the highest batting average of 95.62.

How to Play: Use the "Select Player" slicer in the dashboard and see if the KPI cards match these records!

📂 Repository Contents
ICC Cricket Analysis.pbix: The core Power BI project file.

README.md: Technical documentation and presentation guide.

Data/: Cleaned datasets used for the visualization.
