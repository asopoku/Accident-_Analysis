# Project Overview
This analysis aims to provide insight into the accident incidence in England by analyzing various aspects to identify trends make data-driven decisions and get a deep understanding of the causes of accidents in the various districts.

# Data Source
The primary data used for the analysis is accident data sourced from  [here](https://drive.google.com/file/d/1R_uaoZL18nRbqC_MULVne90h3SdRbAyn/view)

# Tools Used
For this analysis, MySQL, Microsoft Excel and Power BI were used for cleaning, mining, analyzing, and visualizing using Power Query, Power View

# Data Preparation
The data was prepared for analysis and it was ensured the data was clean by;
- loading and inspecting the data
- deleting all duplicated entries
- formatting the data into the appropriate types, (texts are in proper format, all unnecessary spaces and special characters were removed  and numbers were in number format)
- Creating new columns
- replacing missing values.

# Exploratory Data Analysis (EDA)
- The data was further explored to find the following KPIs;
- What was the total number of casualties?
- How many casualties were fatal?
- How many casualties were serious?
- How many casualties were slight?
- What was the trend in casualties in 2021 and 2023?
- Casualties by light
- Casualties by surface area
- Casualties by area
- Casualties by road type
- Casualties by light
- Casualties by vehicle type

  # Data Analysis
- To find the number of casualties by road surface, all other types of road surfaces were grouped into wet, snow and dry
- To find the number of casualties by light conditions, the conditions were grouped into Daylight and dark
- New Measures were computed to calculate the severity of casualties
- Charts were also used for further analysis

# Results and Findings
After the analysis, it was found that, 
- The total number of casualties was 409,000.
- There were 7009 fatal casualties.
- There were about 58,000 serious casualties.
- There were about 343,000 casualties with slight injuries.
- 110,000 accident casualties occurred during the dark while 298,000 occurred during daylight.
- 250,000 casualties occurred in the urban centres while 159,000 occurred in the rural areas
- 328,000 casualties occurred by cars which is the most while 994 were by farm vehicles which is the least.
- 272,000 casualties occurred on dry surface, 113,000 on a wet surface and 22,000 on snowy surface.
304,000 casualties occurred on a single carriage road, 66,000 on dual carriage roads 26,000 on roundabouts with the least being 5,000 on a slip road

# Dashboard
Light Theme
![dashboard light](https://github.com/asopoku/Accident-_Analysis/assets/72577156/74dfe1d8-ac06-4255-aea6-56dee65fd353)

Dark Theme
![dashboard dark](https://github.com/asopoku/Accident-_Analysis/assets/72577156/ee4f65fd-60ee-4874-a67a-07fab304e269)
