# 🚢Titanic Passenger Survival Analysis Dashboard
This project presents an interactive Power BI dashboard built on the Titanic dataset to uncover survival patterns through demographics, class, embarkation points,
and family travel.With KPIs, filters, and storytelling visuals, it highlights how gender, class, and group travel shaped survival, turning raw data into meaningful 
insights.

# 📌Project Objective 
This project delivers an interactive Power BI dashboard built on the Titanic dataset to analyze survival patterns across demographics, class, embarkation points, and 
family travel. It highlights how women and children had higher survival odds, while third-class passengers faced the greatest risk. Key KPIs such as survival rate, 
gender ratio, and class distribution provide quick insights, while filters enable deeper exploration. Through data storytelling, the dashboard transforms raw data 
into meaningful insights, combining history with analytical learning.

# 🎯Project Objectives
  - 👥Examine total passenger demographics including gender, class, and family size.
  - 🧭Understand survival patterns based on gender, class, and embarkation point. 
  - 👨‍👩‍👧Identify the impact of family/group travel on survival chances.
  - 📊Provide clear KPIs and a survival performance benchmark.
  - 🖥️Create an interactive reporting tool with slicers/filters for in-depth exploration.

# 📊Dashboard Features
  - 🔑Key KPIs
       - 👥Total Passengers: 1,309
       - 💚Survived Count: 494
       - 👫Total Siblings/Spouses (SibSp): 653
       - 👨‍👩‍👧Total Parents/Children (Par/Chi): 504
       - 🎯Passenger Survival KPI: 0.27 (27%), Goal = 0.38 (38%)
       | <a href = "https://github.com/SathishRamachandran1975/-Titanic-Passenger-Survival-Analysis-Dashboard-/blob/main/Titanic_output.png">PREVIEW</a> | 

# 📈Visualizations
  - 👩‍🦰Gender Distribution
       - 466 Males (35.6%)
       - 843 Females (64.4%)
  - 🚹Survival Breakdown by Gender
       - Male: 734 ❌ did not survive, 109 ✅ survived
       - Female: 81 ❌ did not survive, 385 ✅ survived
  - 🏷️Class-wise Survival
       - 1st Class: 137 ✅ survived, 186 ❌ not survived → Total 323
       - 2nd Class: 87 ✅ survived, 190 ❌ not survived → Total 277
       - 3rd Class: 518 ❌ not survived, 491 ✅ survived → Total 1,009
  - 🛳️Boarding Point Analysis
       - Southampton (S): 914 passengers (69.8%)
       - Cherbourg (C): 270 passengers (20.6%)
       - Queenstown (Q): 123 passengers (9.4%)
       - Unknown: 2 passengers
  - 📍Boarding Point Survival Analysis
       - Southampton (S): 133 ✅ survived, 609 ❌ not survived
       - Cherbourg (C): 93 ✅ survived, 127 ❌ not survived
       - Queenstown (Q): 39 ✅ survived, 30 ❌ not survived
  - 👨‍👩‍👧Family/Group Bookings
       - Ticket CA.2343 → 8 passengers
       - Ticket 1601 → 8 passengers
       - Ticket CA.2144 → 8 passengers
  - 📊Overall Survival Rate
       - 494 out of 1,309 passengers survived (37.7%)
       - KPI Gauge shows 27% vs 38% Goal
   
# 🎛️Filters Available
  - 🏷️Passenger Class (1st, 2nd, 3rd)
  - 👥 Gender (Male, Female)
  - 🛳️ Boarding Points (S, C, Q, Unknown)
  - ✅❌ Survival Status (Survived, Not Survived)

# 📂Dataset Information
  - Dataset Used: Titanic Passenger Dataset (Kaggle)
  | <a href ="https://github.com/SathishRamachandran1975/-Titanic-Passenger-Survival-Analysis-Dashboard-/blob/main/CLEANED_TITANIC.csv">TITANIC DATASET</a> |
| Column Name      | Description                                  |
|------------------|----------------------------------------------|
| Name             | Passenger’s full name                        |
| Gender           | Male / Female                                |
| Age              | Age of the passenger                         |
| Pclass           | Passenger class (1st, 2nd, 3rd)              |
| SibSp            | No. of siblings/spouses aboard               |
| Parch            | No. of parents/children aboard               |
| Ticket           | Ticket number                                |
| Fare             | Ticket fare paid                             |
| Cabin            | Cabin number (if available)                  |
| Embarked         | Boarding point (S = Southampton, C = Cherbourg, Q = Queenstown) |

# 🛠️Tools & Techniques
   - 📊Power BI → Dashboard design and visualization
   - 🧹Power Query → Data cleaning and transformation
   - ➗DAX Measures → KPI calculations (Survival %, Class distribution, Family bookings)
   - 📂Dataset Source: Kaggle Titanic dataset

# 📖Storytelling – The Journey Behind the Dashboard
   - When the RMS Titanic set sail in 1912, it carried more than 1,300 passengers across different classes, families, and backgrounds.
     Each number in the dataset hides a real human story—families on new beginnings, individuals seeking opportunities, and the cruel
     fate that determined survival.
   - This dashboard revives those stories through data storytelling:
          - 👩Women and children had higher survival rates, proving the "women and children first" policy.
          - 🏛️Class played a big role—1st class passengers had better odds compared to 3rd class.
          - 🛳️Boarding point mattered—Cherbourg passengers had higher survival compared to Southampton or Queenstown.
          - 👨‍👩‍👦Family groups had better survival chances, showing the strength of traveling together.
   - The data transforms into a narrative of courage, inequality, and fate, reminding us that behind every statistic was a life, a family, and a story.
   | <a href = "https://github.com/SathishRamachandran1975/-Titanic-Passenger-Survival-Analysis-Dashboard-/blob/main/Titanic_Storytelling.pdf">FULL STORY</a> |

# 📁Project File Structure
   - 📊Titanic_Dashboard.pbix → <a href ="https://github.com/SathishRamachandran1975/-Titanic-Passenger-Survival-Analysis-Dashboard-/blob/main/Titanic_Project.pbix">TITANIC POWER-BI_FILE</a>
   - 📂Titanic_Dataset.csv → <a href ="https://github.com/SathishRamachandran1975/-Titanic-Passenger-Survival-Analysis-Dashboard-/blob/main/CLEANED_TITANIC.csv">TITANIC EXCEL_FILE</a>
   - 📝Titanic_output.png →  <a href = "https://github.com/SathishRamachandran1975/-Titanic-Passenger-Survival-Analysis-Dashboard-/blob/main/Titanic_output.png">TITANIC OUTPUT_FILE</a>
   - 📝Titanic_Storytelling.pdf → <a href = "https://github.com/SathishRamachandran1975/-Titanic-Passenger-Survival-Analysis-Dashboard-/blob/main/Titanic_Storytelling.pdf">TITANIC STORYTELLING_FILE</a>

# ✅Insights
  - 👩Females had a much higher survival rate compared to males.
  - 🏷️1st class passengers had the greatest chance of survival, while 3rd class had the lowest.
  - 🛳️Passengers embarking from Cherbourg (C) had better survival odds compared to Southampton (S) and Queenstown (Q).
  - 👨‍👩‍👧Family/group bookings positively influenced survival chances.
  - 🎯Overall survival rate was 27%, below the desired goal of 38%.

# 📝Conclusion
  - This project successfully demonstrates how data visualization can transform historical records into meaningful insights. By analyzing the Titanic dataset, the dashboard
    highlights clear survival patterns shaped by gender, class, embarkation point, and family travel. The interactive filters and KPIs provide a powerful way to explore the
    data, while storytelling connects numbers to human experiences, making the findings both informative and impactful. Beyond revisiting a historic tragedy, this project
    showcases the importance of data-driven decision-making and the ability of Power BI to turn complex datasets into accessible, actionable knowledge.
