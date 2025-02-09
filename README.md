# 🏥 Hospital Patient Analysis

Welcome to the **Hospital Patient Analysis** project! This repository contains a detailed analysis of patient data using advanced Excel techniques such as Power Query, Power Pivot, and DAX. The primary goal of this project is to provide meaningful insights into patient trends, satisfaction levels, and operational efficiency.

![hospital dashboard](https://github.com/user-attachments/assets/75a55271-509d-4b99-9c05-07b6ad11dacd)

---



## 🛠️ Skills and Tools Used

- **Microsoft Excel**: Advanced features like Power Query, Power Pivot, and Data Modeling.
- **Data Cleaning**: Extensive data preparation and handling of missing or inconsistent records.
- **Power Query**: For data transformation, merging, and cleaning.
- **Power Pivot**: Building relationships between tables for data modeling.
- **DAX (Data Analysis Expressions)**: Creating calculated columns and measures.
- **Visualization**: Creating interactive and informative charts and graphs.
- **Date Table**: Custom date table for managing non-continuous and missing dates.
- **Categories & KPIs**: Classifying age groups and delay status.
- **Python**: Used Python script to make date usable format.

---

## 📝 Project Overview

The **Hospital Patient Analysis** project focuses on understanding patient data and hospital performance across several dimensions, including:

- **Gender**: Distribution of patients by gender.
- **Age Groups**: Categorizing patients into predefined age groups.
- **Satisfaction**: Measuring patient satisfaction levels.
- **Operational Metrics**: Analyzing average waiting time, daily visits, and delay occurrences.
- **Department Analysis**: Understanding where patients are referred to for treatment.

### Objectives:
1. Understand patient demographics.
2. Assess operational efficiency (e.g., delays and average waiting time).
3. Monitor patient satisfaction trends.
4. Enable actionable insights through data visualization.

---

## 📊 Graphs and Visualizations

### 1. **Patient Satisfaction**
   - A bar graph representing overall patient satisfaction levels. The data reveals trends such as the percentage of satisfied, neutral, and dissatisfied patients.

   - ![Screenshot 2025-02-09 183751](https://github.com/user-attachments/assets/14a7adbf-b4f2-4ba0-a428-4d4282bc11ac)


### 2. **Daily Visits**
   - A line chart illustrating the number of patients visiting the hospital daily. This analysis highlights peaks and troughs in patient traffic.

   - ![Screenshot 2025-02-09 183751](https://github.com/user-attachments/assets/b187eaf5-a1d3-4df5-be5a-1c0fcade7247)
![Screenshot 2025-02-09 183739](https://github.com/user-attachments/assets/60b93015-2c36-4ea8-8ce0-48b9a07acac7)


### 3. **Average Waiting Time**
   - A column graph depicting the average waiting time for patients. Includes insights into how waiting time correlates with patient satisfaction and delays.

   - ![Screenshot 2025-02-09 183739](https://github.com/user-attachments/assets/d8681d54-003f-4858-b6ed-118f55fcabfb)
![Screenshot 2025-02-09 183751](https://github.com/user-attachments/assets/7315be62-30b9-4e92-b17c-ec2583c3ee68)
![Screenshot 2025-02-09 183728](https://github.com/user-attachments/assets/5b37ddb6-8e0a-4b58-b0ac-e0ccb40de717)


### 4. **Gender Distribution**
   - A pie chart visualizing the gender breakdown of patients.

### 5. **Age Group Distribution**
   - A histogram representing the proportion of patients in different age brackets (e.g., 0-18, 19-35, 36-50, etc.).

### 6. **Department Referral**
   - A bar chart analyzing which departments patients are referred to most frequently.

---

## 🔍 Data Cleaning and Modeling

### **1. Data Cleaning in Power Query**
   - Removed duplicates and handled missing data.
   - Transformed non-continuous date records into usable formats.
   - Standardized inconsistent data entries (e.g., gender values such as "M/F" standardized to "Male/Female").
     
![image](https://github.com/user-attachments/assets/29e385e7-a2fb-49eb-a33d-0a9dafcd6a89)
![Screenshot 2025-02-09 183751](https://github.com/user-attachments/assets/986d96c7-8edf-4694-9bc1-ffad9b387b59)
![Screenshot 2025-02-09 021447](https://github.com/user-attachments/assets/b3bd4851-2a24-4889-a1c3-8fa8253d3c3e)



### **2. Data Modeling in Power Pivot**
   - **Date Table Creation**: A separate date table was created to manage missing and non-continuous dates. This table was linked to the main dataset via relationships, ensuring accurate time-based analysis.
   - **Relationships**: Connected multiple tables (e.g., patient records, satisfaction data, and department data) for seamless data analysis.
   - **Calculated Columns**: 
      - **Age Groups**: DAX formulas were used to classify patients into age categories.
      - **Delay Status**: A calculated column was added to flag if a patient experienced a delay (waiting time > 30 minutes).

![Screenshot 2025-02-09 032142](https://github.com/user-attachments/assets/bce906bc-ffaa-43cd-a634-80035961bc0d)
![Screenshot 2025-02-09 183751](https://github.com/user-attachments/assets/90005c2a-5699-45c9-b444-a2648828f823)


---

## 📈 Insights and Results

- A significant percentage of patients experienced delays, which impacted their satisfaction levels.
- Age groups 19-35 and 36-50 were the most frequent visitors.
- The average waiting time varied by department, with some departments experiencing more delays than others.
- Male and female patients were almost equally distributed in visits, with slight variances in satisfaction trends.

---

## 🚀 Conclusion

This project demonstrates how powerful Excel features like Power Query and Power Pivot can transform raw hospital data into actionable insights. By using data visualization, we identified areas for improvement in hospital operations, such as reducing patient delays and addressing satisfaction issues. 

---

## 🌟 Key Highlights

- **Advanced Excel Techniques**: Power Query, Power Pivot, and DAX were extensively used for cleaning, modeling, and analyzing data.
- **Interactive Charts**: Visualization of patient satisfaction, delays, and demographics for effective storytelling.
- **Operational Insights**: Identification of bottlenecks in waiting times and their impact on patient satisfaction.

---

Feel free to explore the repository and provide feedback or suggestions. 😊
