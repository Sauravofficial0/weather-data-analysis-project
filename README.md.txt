# Weather Data Analysis using Python (Pandas)

This project answers 15 real-world data analysis questions on a weather dataset using Python and Pandas.

Dataset file: `unstructured_weather_10000_rows.csv`  
Total rows: 10,000

---

## Questions & Answers

### Q1) Find all the unique 'Wind Speed' values in the data.

Answer:  
Wind Speed values range from **0.0 km/h to 60.0 km/h** (in steps of 0.1).

---

### Q2) Find the number of times when the Weather is exactly Clear.

Answer:  
**943 records**

---

### Q3) Find the number of times when the Wind Speed was exactly 4 km/h.

Answer:  
**16 records**

---

### Q4) Find out all the Null values in the data.

Answer:

| Column | Null values |
|------|-----------|
| Date time | 0 |
| Temp_C | 300 |
| Dew Point Temp_C | 0 |
| Rel Hum_% | 300 |
| Wind Speed_KM/h | 0 |
| Visibility_Km | 300 |
| Press_KPA | 0 |
| Weather | 0 |

---

### Q5) Rename the column name Weather to Weather Condition.

Answer:  
The column **Weather** was successfully renamed to **Weather Condition**.

---

### Q6) What is the mean Visibility?

Answer:  
**15.3279 km**

---

### Q7) What is the Standard Deviation of Pressure in this data?

Answer:  
**1.4423 kPa**

---

### Q8) What is the Variance of Relative Humidity in this data?

Answer:  
**667.9018**

---

### Q9) Find all instances when Snow was recorded.

Answer:  
**903 records**

(All records where Weather Condition = Snow are displayed in the notebook.)

---

### Q10) Find all instances when Wind Speed is above 24 and Visibility is 25.

Answer:  
**19 records**

---

### Q11) What is the Mean value of each column against each Weather Condition?

Answer:  
Mean values of all numeric columns were calculated for each weather condition using groupby.

(Full grouped mean table is available in the notebook output.)

---

### Q12) What is the Minimum & Maximum value of each column against each Weather Condition?

Answer:

Minimum and maximum values of all numeric columns were calculated for each weather condition.

(Full grouped minimum and maximum tables are available in the notebook output.)

---

### Q13) Show all the records where Weather Condition is Fog.

Answer:  
**897 records**

(All Fog records are displayed in the notebook.)

---

### Q14) Find all instances when Weather is Clear or Visibility is above 40.

Answer:  
**943 records**

Note:
In this dataset, Visibility never exceeds 40 km.  
Therefore, the result mainly contains records where Weather Condition is Clear.

---

### Q15) Find all instances when  
A. Weather is Clear and Relative Humidity is greater than 50  
OR  
B. Visibility is above 40

Answer:  
**513 records**

Note:
Visibility never exceeds 40 km in this dataset, so the result comes from the first condition only.

---

## Tools Used

- Python
- Pandas
- Jupyter Notebook