Solution Approach: VitaTrack Wellness Dashboard 

Google drive link for interactive dashboard-
https://drive.google.com/file/d/1-9xyunYieaQZ8H6HeXvPh_pnmKNd5JdN/view?usp=sharing

Objective: 

The goal was to analyze user lifestyle patterns and health data from VitaTrack Wellness in order 
to: 
● Identify risk factors for heart disease 
● Understand relationships between lifestyle and health indicators 
● Provide data-driven wellness insights 
● Create a clear and interactive Power BI dashboard for stakeholders 

Step-by-Step Approach: 

1. Understanding the Dataset 

● The dataset included key health metrics like Age, Gender, BMI, Daily Steps, Sleep, 
Smoking, Alcohol, Heart Rate, etc. 
● First, the data was cleaned (ensuring valid types and removing any nulls or anomalies 
where applicable). 
● Additional columns were created, such as BMI Category and Age Group, for easier 
aggregation and analysis. 

2. DAX Measures & Calculated Columns 

Custom measures were created to support meaningful visuals. Examples include: 
● Avg Daily Steps = AVERAGE(Daily_Steps) 
● Heart Disease Count  

3. Dashboard Structure  

Lifestyle Overview 

● Key metrics via card visuals: Steps, Sleep, Calories, BMI 
● Donut chart showing Gender distribution 
● Clustered bar chart comparing average lifestyle indicators by Gender 
● Slicers for Gender, Age, Smoking, and Diabetic status 

Heart Health Risk 

● Heart disease count (card) 
● Stacked column charts showing heart disease risk based on smoking and alcohol habits 
● Clustered bar chart comparing Blood Pressure and Heart Rate across BMI categories 
● Donut chart for heart disease ratio 

Sleep & Activity Insights 

● Line chart: Exercise hours vs Sleep duration 
● Cards for Avg Sleep and Avg Exercise Hours 

Health Segmentation  

● Use clustering logic to segment users into groups based on activity, diet, and risk 
● Recommend lifestyle tips for each cluster 

4. User Interactivity 

● Slicers added across all pages for personalized filtering 
● Visuals respond dynamically to slicers and selections 

Result & Impact: 

The final dashboard enables VitaTrack’s analytics and wellness teams to: 
● Pinpoint at-risk groups (e.g., smokers with heart issues) 
● Promote healthy behaviors through sleep and activity insights 
● Personalize health guidance based on user demographics and lifestyle patterns
