# death_age_eda 
### Analysis and Insights
1. Gender Distribution:
 ○ What is the distribution of genders (Male and Female) in the combined dataset? How does it differ between the two datasets before matching? 
 * Dataset1
![image](https://github.com/user-attachments/assets/a57bfeec-c7a6-4a66-aad4-f36173d792bb)
 * Data set 2
![image](https://github.com/user-attachments/assets/a7a48714-114c-4683-8a3f-5e174e3bdd31)
 * After merge 
![image](https://github.com/user-attachments/assets/119d9ad2-022a-49c2-a4ba-c7c2a162070c)

2. Geographic Representation: 
○ Whichcountries are most represented in the dataset, and are there any discrepancies in country distributions between Dataset 1 and Dataset 2? 
 
![image](https://github.com/user-attachments/assets/bb98e74c-cd65-4350-936c-442332881212)

3. Occupation Trends:
 ○ What are the most common occupations, and how do they vary by gender? 
 ![image](https://github.com/user-attachments/assets/7a24d900-86a8-492c-83ed-f341ed7eec6d)

4. Historical Patterns: 
○ What is the average age at death for individuals in the dataset? Are there differences based on gender or country? 
 ![image](https://github.com/user-attachments/assets/5ddcc23a-82d3-44ae-acad-81eeb306cc72)

5. Analysis of Missing Data: 
○ After matching, what proportion of records still contain missing values in key fields such as Country or Manner of death? What strategies could be used to impute or address these gaps?
 ![image](https://github.com/user-attachments/assets/6a89a0b8-7150-4625-a429-b0334ad3a6be)
# powerbi dashboard
![image](https://github.com/user-attachments/assets/544dbc40-b6af-4acf-a5d6-c7aaf469d304)

1. Filters (Top Section)
The green section at the top contains three dropdown filters:
•	Gender – Select "All" or filter by "Male" or "Female."
•	Country – Choose one or multiple countries to filter the data.
•	Occupation – Select an occupation to see relevant insights.
* 🔹 How to Use:
•	Click on a dropdown menu.
•	Select one or multiple options.
•	The dashboard updates automatically based on your selection.
________________________________________
2. Key Metrics (Top Center)
Below the filters, four key metrics provide a quick summary:
•	Death Age Average – Displays the average age at death.
•	Total People – Shows the total number of records in the dataset.
•	Number of Males – Represents the total count of male records.
•	Number of Females – Represents the total count of female records.
* 🔹 How to Use:
•	These are static indicators that change dynamically based on your selected filters.
________________________________________
3. Data Visualizations (Main Section)
A. Top 10 Countries by Gender (Treemap)
•	This chart visualizes the top 10 countries with data distribution by gender.
•	Larger blocks represent a higher proportion of records.
•	The "Unknown" category may include missing or unidentified country data.
* 🔹 How to Use:
•	Hover over a country to see additional details.
•	The size of each block indicates the relative proportion.
B. Top 5 Occupations by Gender (Bar Chart)
•	Displays the top 5 occupations with gender representation.
•	Darker sections represent male data, while lighter sections represent female data.
* 🔹 How to Use:
•	Compare gender distribution across different occupations.
•	Hover over bars for precise values.
C. Death Age Average by Gender (Bar Chart)
•	Shows the average death age for each gender.
•	"Unknown" represents records where gender is unspecified.
* 🔹 How to Use:
•	Compare life expectancy trends by gender.
•	Hover over bars to see specific values.
________________________________________
4. Navigation & Additional Features
•	The bottom panel has tabs for different analysis views.
•	Click "Manner of death analysis by age avg" to explore another detailed analysis.
•	Use the "+" button to add new reports or custom insights (if enabled).
![image](https://github.com/user-attachments/assets/a8e4b470-d695-4657-9e55-2aa31030643b)

 
5. Filter Section (Top Right)
* 🔹 Manner of Death Dropdown – Allows users to filter data based on the cause of death, including:
•	Natural causes
•	Suicide
•	Accident
•	Unknown
* ✅ How to Use:
•	Click the dropdown menu.
•	Select a specific manner of death to refine the results.
•	The dashboard updates automatically based on your selection.
________________________________________
6. Pie Chart: "Top 4 #Gender by Manner of Death"
•	Shows the distribution of deaths by manner.
•	Different colors represent different categories (natural causes, suicide, accident, and unknown).
•	The percentage and total count are displayed.
* ✅ How to Use:
•	Hover over the chart to see detailed percentages.
•	Use the manner of death filter to observe category-specific changes.
________________________________________
7. Table: "Manner of Death & Average Death Age" (Top Right Panel)
•	Displays various causes of death alongside their average age at death.
•	Sorted in descending order of frequency or impact.
•	Causes include work accidents, suicides, war-related deaths, illnesses, and other fatal incidents.
* ✅ How to Use:
•	Scroll down to explore different causes of death.
•	Identify causes with significantly high or low average death ages.
________________________________________
8. Table: "Top Occupations by Average Age of Death" (Bottom Panel)
•	Lists occupations alongside their average age at death.
•	Some professions (e.g., Vicar, Lecturer, Astronomer) have an average death age of 99, suggesting longevity.
•	Other professions may show significantly lower life expectancy based on risk factors.
* ✅ How to Use:
•	Analyze which occupations are associated with higher or lower death ages.
•	Compare trends between different job roles.
