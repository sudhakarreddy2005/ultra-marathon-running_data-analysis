# Ultra-Marathon Running Data Analysis

## Background

Ultra-marathons are races longer than the traditional marathon distance of **42.195 km**. Distances range from **50 km to over 200 miles**, and events have been organised worldwide for more than two centuries. Analysing ultra-running trends provides valuable insights into athlete performance, country-level participation, and the evolution of endurance sports.

This project explores a large-scale dataset of ultra-marathon records from **1798 to 2022**, making it one of the most comprehensive historical collections of running data.

- **7,461,226 race records**  
- **1,641,168 unique athletes**  
- All records anonymised with a unique Athlete ID  
- Data covers athlete demographics, race distances, event details, average speeds, and seasons  



## Methodology

The analysis was conducted using a structured workflow:

1. **Data Loading & Inspection**  
   - Imported raw datasets and validated shape, columns, and completeness.  
   - Checked for null values and duplicates.  

2. **Data Cleaning**  
   - Converted event distances and race times to consistent formats.  
   - Standardised categorical variables (sex, country codes).  
   - Extracted year and race season for temporal analysis.  

3. **Exploratory Data Analysis (EDA)**  
   - Examined distributions of speeds, distances, and participation counts.  
   - Summarised data by sex, country, and event.  

4. **Visualisation**  
   - Used plots (boxplots, histograms, line charts, bar plots) to highlight trends.  
   - Focused on comparisons across gender, country, event, and season.  

5. **Interpretation**  
   - Converted statistical and visual findings into actionable insights.  



## Data Structure

| Column            | Description                                            |
| ----------------- | ------------------------------------------------------ |
| Athlete ID        | Unique anonymised identifier for each runner           |
| Sex               | Gender category (M/F)                                  |
| Athlete Country   | Nationality of the athlete                             |
| Event Name        | Official name of the ultra-marathon event              |
| Event Date        | Year/date of the race                                  |
| Event Distance    | Distance of the race (50 km, 100 km, 100 miles, etc.)  |
| Athlete Avg Speed | Average speed of the athlete during the event (km/h)   |
| Race Season       | Categorised as Summer/Winter                           |



## Data Types

| Column            | Data Type   |
| ----------------- | ----------- |
| Athlete ID        | Integer     |
| Sex               | Category    |
| Athlete Country   | Category    |
| Event Name        | String      |
| Event Date        | Date        |
| Event Distance    | Float       |
| Athlete Avg Speed | Float       |
| Race Season       | Category    |

---

## Executive Summary

- Ultra-marathon participation has grown significantly over the past two centuries.  
- Distinct performance differences are observed when comparing **sex, country, and event type**.  
- Seasonal analysis shows a greater number of races are held in **winter months**.  
- Average speed distributions differ clearly between men and women.  



## Insights & Visualisations

### 1. Sex and Athlete Average Speed
- Men and women show **different speed distributions**, with men having slightly higher averages.  
- **Insight Note**: Female athletes demonstrate competitive endurance performance, especially in longer races.  

![Sex vs Speed](https://github.com/sudhakarreddy2005/ultra-marathon-running_data-analysis/blob/main/i1.png)




### 2. Athlete Country and Performance
- Country-level comparison highlights variations in average speeds.  
- **Insight Note**: Athletes from endurance-dominant nations (e.g., USA, Japan, France) show consistently higher performance.  

![Country vs Speed](images/country_vs_speed.png)



### 3. Event-Level Performance
- Events with multiple editions reveal **consistent speed trends**.  
- **Insight Note**: Certain iconic races exhibit stable long-term performance patterns.  

![Event vs Speed](images/event_vs_speed.png)


### 4. Seasonal Races
- More races occur in **winter** than summer.  
- **Insight Note**: Seasonal climate factors strongly influence both participation and performance.  

![Seasonal Speeds](images/seasonal_speeds.png)


### 5. Statistical Summary by Sex
- Male and female athletes differ in both **minimum and maximum speeds**.  
- **Insight Note**: Extreme values highlight physiological and participation-based differences across genders.  



## Recommendations

- **Athlete Development**: Training plans can be tailored based on gender differences and seasonal factors.  
- **Event Organisers**: Insights into seasonal participation trends can support better race scheduling.  
- **Sports Analysts**: Country-level differences may reflect infrastructure, culture, and emphasis on endurance sports.  
- **Future Research**: Track longitudinal performance of individual athletes across multiple years.  


## Conclusion

This project provides one of the most comprehensive analyses of ultra-marathon history. By combining athlete demographics, event information, and performance metrics across more than two centuries, the dataset enables deep insights into the evolution of endurance sports.  

The findings demonstrate how long-term datasets reveal patterns in **athletic progress, cultural participation, and event design**.
