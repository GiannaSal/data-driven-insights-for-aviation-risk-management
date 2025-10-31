# data-driven-insights-for-aviation-risk-management

# Overview
Analyzes NTSB, FAA, and WAAS aviation accident data using Python for data cleaning, analysis, and visualization. Identifies key risk patterns and provides three actionable business recommendations to support safer, data-driven aviation decisions.

# Business Understanding
Company is expanding into the aviation industry including commercial and private aircraft operations but the company has little to no knowledge about the risks associated with different aircrafts. The main goal is to identify the aircraft with the least risk enabling informed purchase decisions.

# Data Understanding and Analysis
More than half of the data in Aircraft.Category is missing and is filled using the number of engines and engine type of a an aircraft
Aicrafts are also diviided into Commercial and Personal based on the flight purpose
Aircraft damage is divided into categories where Substantial is the highest degree of damage followed by Destroyed then Minor then Unknown for ongoing investigations.
Injury severity is also classified in categories : Fatal - where a death occured, Non-Fatal -  injuries, Incident - no injury and unknown for ongoing investigations
Similarly weather conditions are classified into categories containing VMC - Good visual conditions, IMC -Instrument only conditons(poor visibility), UNK - Not recorded, Unknown - pending investigations.

# Conclusion
Airplanes and Helicopters are the most common aircrafts used in commercial and private enterprise hence the need for direct comparison between the two. Both have pros and cons that are well reflected . The data generated can be useful in confering valid business recommendations.

#Interactive Dashboard
[This dashboard shows represents 3 business recommendations](https://public.tableau.com/views/phase1projecttableau_17619219005770/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


![Dashboard Preview](dashboard_preview.png)

