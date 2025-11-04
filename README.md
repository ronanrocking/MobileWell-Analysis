# MobileWell400+ Data Analysis Project

## Course
**Data Analytics**

## Project Question
Identify missing values, duplicates, and inconsistencies across sensor readings (WiFi, light, noise, screen) and survey responses.  
Apply imputation or interpolation for missing continuous variables (e.g., light, noise) and mode imputation for categorical data (e.g., connectivity type).  
Normalize data for comparison across time and participants.  
Generate association rules linking survey-based mental health indicators (PHQ-9, GAD-7, FS) with sensor-based lifestyle features (activity, WiFi connections, light).  
Discuss which environmental conditions frequently co-occur with reported negative or positive moods.

---

## Project Description
This project performs data analysis on the **MobileWell400+ dataset** to explore the relationship between smartphone-based sensor readings and mental health indicators. The objectives include identifying and addressing missing values, duplicates, and inconsistencies across sensor data (WiFi, light, noise, screen) and survey responses.

Continuous variables such as *light* and *noise* are treated using imputation or interpolation techniques, while categorical variables such as *connectivity type* are handled using mode imputation. The processed data is then normalized to facilitate comparison across different participants and time intervals.

Finally, **association rule mining** is conducted to link survey-based mental health indicators with lifestyle features derived from sensor data (e.g., activity, WiFi connections, light intensity). The results highlight environmental and behavioral conditions that frequently co-occur with positive or negative mood states.

---

## Team Members
| Name | Roll No. |
|------|-----------|
| Ronan Madan |   2409     |
| Aishwarya Mangalore | 2409      |
| Ishita T  | 240953074 |
| Nikita Mukta| 240953202 |
| Avani Muniyangla | 240953742 |

---

## Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **mlxtend** (for Apriori, FP-Growth, and Association Rule Mining)

## Dataset

MobileWell400+ Dataset
The repository includes the complete MobileWell400+ dataset, containing multiple CSV files with both sensor and survey data. 
The dataset provides a comprehensive view of participants’ smartphone usage patterns, environmental conditions, and self-reported mental health metrics.


## Results

Cleaned and normalized dataset integrating sensor and survey data.

Association rules generated between lifestyle factors and mood indicators.

Visualizations showing correlations between environmental conditions and reported moods.

