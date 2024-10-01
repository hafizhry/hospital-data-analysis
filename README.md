# Hospital Patient Data Analysis

## Project Overview
This a final project for SI544 - Introduction to Statistics and Data Analysi at UMich. The project aims to analyze hospital patient data to explore how financial class (Medicare, Private Insurance, etc.) influences patient waiting times and revenue generation. The analysis employs multiple regression models and hypothesis testing using R. 

## Dataset Information
- **Source**: [Kaggle - Hospital Patient Data](https://www.kaggle.com/datasets/abdulqaderasiirii/hospital-patient-data)
- **Data Description**: 
  - Contains information such as financial class, waiting times, and revenue generation.
  - Granularity: daily data and patient-level data.
  - **Key Columns**:
    - Financial Class
    - Entry Time, Completion Time
    - Medication Revenue, Lab Cost
    - Patient ID

## Key Objectives
1. Investigate how financial class impacts revenue generation and waiting times.
2. Compare patient waiting times and medication revenue between Medicare and Private Insurance.

## Methodology
- **Data Wrangling**:
  - Processed the data by adding `Waiting Time` (difference between consultation times) and `Insurance Type` (Federal or Non-Federal).
  
- **Analysis**:
  - Conducted multiple regression to model the relationship between `Lab Cost` and `Medication Revenue` with respect to different financial classes.
  - Performed hypothesis testing to compare waiting times between Medicare and Private Insurance patients.

## Results
1. **Regression Analysis**: Found varying relationships between `Lab Cost` and `Medication Revenue` for different financial classes, indicating that revenue generation patterns differ by insurance type.
2. **Hypothesis Testing**: Discovered significant differences in waiting times between Medicare and Private Insurance patients, with Medicare patients having longer average wait times.

## Conclusion
This analysis reveals that financial class affects both the revenue generated and waiting times for patients, with noticeable differences between Medicare and Private Insurance.

## Requirements
- **R** and **RStudio**
- **Libraries**: 
  - `readxl`
  - `dplyr`
  - `ggplot2`
  - `moderndive`
  - `skimr`
  - `infer`

## How to Run
Clone the repository:
   ```bash
   git clone https://github.com/your-username/hospital-patient-data-analysis.git

## Contact
For further questions or collaboration, feel free to contact me at hafizhry@umich.com.