# NYC Parking & Traffic Violations Analysis (2024)
![49-16504 jpg](https://github.com/user-attachments/assets/6fc3cca9-fd2d-46bd-8db5-6febf3d2ef70)

Data Analysis of 2024 Traffic Enforcement Patterns in New York City
*Note: This was a collaborative project completed with Dinara Ibotova, Diana Konsevych, Beelen Guzman, and Ray Kim for CIS3120.*

Analyzed 1 million NYC parking and traffic violation records from the city's open data API to see what's actually happening with enforcement. Found some interesting patterns in who gets tickets the most, where, and inconsistencies in how much people pay for the same violations.

## Business Problem
**Urban Traffic Management Challenge:**
NYC issues over 122 million parking and traffic violations annually, generating significant revenue while attempting to manage traffic flow and safety. We wanted to dig into the data to see if there are patterns that could help city officials figure out where to focus enforcement or fix policy gaps.

## 📂 Data Source
[NYC Open Data – Parking & Camera Violations] (https://data.cityofnewyork.us/City-Government/Open-Parking-and-Camera-Violations/nc67-uf89/about_data)

## What we looked at
- Which violations happen most often and cost how much
- Where tickets cluster geographically across the boroughs
- What days of the week are worst for violations
- Whether different agencies charge different amounts for the same thing
-How enforcement varies by vehicle type

## Technical Stuff
Code: https://github.com/Dinarauz/Parking-and-Traffic-Violations/blob/main/Open%20Parking%20and%20Camera%20Violations%20Analysis%20Project%20-%20Fall%202024.ipynb

Used Python to pull data from NYC's API, cleaned up about 1M records (out of 122M+ total), and analyzed patterns with pandas and seaborn. Built a Tableau dashboard to visualize the findings.

Data Challenge Solved: The API results kept changing between runs, giving us different data and new errors each time. We fixed this by saving the initial API pull to a CSV file and using that consistent dataset for all analysis.

## 🛠️ Tools & Technologies
	•   Python (Pandas, Seaborn, Requests)
	•	Jupyter Notebook (Deepnote for collaboration)
   	•	Tableau for visualization
	•	ChatGPT for troubleshooting support

## 📊 Key Findings

## Most Common Violations:
	•	School Zone speed cameras: 271K violations ($50 each)
	•	No Parking during street cleaning: 113K violations (65$ each)
	•	Bus lane violations: 59K violations (50$ each)
## Geographic Patterns:
	•	Kings County had the highest ticket count.
	•	Traffic and Transportation agencies issued over 90% of all tickets.
	•	Fine amounts varied inconsistently across agencies, indicating inconsistent enforcement.

## ⚠️ Limitations
 	•	Dataset restricted to 1 million rows (of 122+ million total).
	•	Time-related data like violation time was excluded due to formatting issues.
	•	Limited by absence of data such as driver demographics or registered vehicle counts.

## 📈 Interactive Dashboard
https://public.tableau.com/app/profile/dinara.ibotova/viz/OpenParkingandTrafficViolations/Dashboard1?publish=yes
