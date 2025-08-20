
# Ultra-Marathon Running Data Analysis

## Background

Ultra-marathons are races longer than the traditional marathon distance of 42.195 km. Distances range from 50 km to over 200 miles, and events have been organised globally for more than two centuries. Understanding trends in ultra-running can provide insights into athlete performance, country-level participation, and long-term developments in endurance sports.

This project analyses a large-scale dataset of ultra-marathon race records collected from public websites. The data spans from **1798 to 2022**, covering over two centuries of competitive running history.

* **7,461,226 race records**
* **1,641,168 unique athletes**
* All records are anonymised (unique Athlete ID replaces names)
* Includes attributes such as athlete sex, country, event details, race distances, times, and average speeds

---

## Data Structure

| Column            | Description                                            |
| ----------------- | ------------------------------------------------------ |
| Athlete ID        | Unique anonymised identifier for each runner           |
| Sex               | Gender category (M/F)                                  |
| Athlete Country   | Nationality of the athlete                             |
| Event Name        | Official name of the ultra-marathon event              |
| Event Date        | Year and date of the race                              |
| Event Distance    | Distance of the event (50 km, 100 km, 100 miles, etc.) |
| Athlete Avg Speed | Average running speed of the athlete during the event  |
| Race Season       | Categorised as Summer/Winter                           |

---

## Executive Summary

* Ultra-marathon participation has grown significantly over the past two centuries.
* Clear performance patterns emerge when analysing **sex, country, and event type**.
* Seasonal analysis shows a higher number of races held during **winter months**.
* Statistical summaries reveal **distinct distributions of average speed by gender**.

---

## Insights & Analysis

### 1. Sex and Athlete Average Speed

* Men and women show differences in average speed distributions.
* Visualisation: **Boxplot / Violin plot** of `Sex vs Athlete Avg Speed`.

### 2. Athlete Country and Performance

* Country-level comparison shows variation in average speeds.
* Visualisation: **Bar chart / Strip plot** comparing `Country vs Athlete Avg Speed`.

### 3. Event-Level Performance

* Events with more than 10 races analysed for mean speeds.
* Certain iconic races show consistent speed patterns.
* Visualisation: **Point plot / Bar plot** for `Event Name vs Average Speed`.

### 4. Seasonal Races

* More races occur in **winter** compared to summer.
* Both men and women show seasonal variations in performance.
* Visualisation: **Grouped bar chart** of `Season vs Average Speed by Sex`.

### 5. Statistical Summary by Sex

* Minimum and maximum values of key numerical features calculated.
* Highlights differences in extreme performances.

---

## Recommendations

* **Athlete Development**: Training programs can be tailored based on gender and seasonal patterns.
* **Event Organisers**: Insights into seasonal participation trends can guide scheduling.
* **Sports Analysts**: Country-level differences in performance could reflect infrastructure and cultural emphasis on endurance running.
* **Future Research**: Explore longitudinal performance improvements of individual athletes across years.

---

## Visualisations

*(Representative Seaborn/Matplotlib plots — to be generated in notebook)*

* `sex_vs_speed.png`: Distribution of average speed by gender
* `country_vs_speed.png`: Country-level comparison of performance
* `event_vs_speed.png`: Average speed in major events
* `seasonal_speeds.png`: Seasonal variation in athlete speeds

---

## Conclusion

This project provides one of the most comprehensive analyses of ultra-marathon history. By combining athlete demographics, event information, and performance metrics across two centuries, the dataset enables deep insights into the evolution of endurance sports. The findings highlight the value of long-term datasets in uncovering both social and athletic trends.
