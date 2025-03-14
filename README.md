# Explainable AI for Predicting Student Dropout and Academic Success

## Predict Students' Dropout and Academic Success
Realinho, V., Vieira Martins, M., Machado, J., & Baptista, L. (2021). Predict Students' Dropout and Academic Success [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5MC89.

The dataset includes information known at the time of student enrollment – academic path, demographics, and social-economic factors. 
The problem is formulated as a three category classification task (dropout, enrolled, and graduate) at the end of the normal duration of the course. 

## Features
### 1. Marital Status  
Indicates the student's marital status.  
- `1` = Single  
- `2` = Married  
- `3` = Widower  
- `4` = Divorced  
- `5` = Facto union  
- `6` = Legally separated  

### 2. Application Mode  
Specifies the mode through which the student applied, representing different application phases and contingents.  
- `1` = 1st phase - general contingent  
- `2` = Ordinance No. 612/93  
- `5` = 1st phase - special contingent (Azores Island)  
- `7` = Holders of other higher courses  
- `10` = Ordinance No. 854-B/99  
- `15` = International student (bachelor)  
- `16` = 1st phase - special contingent (Madeira Island)  
- `17` = 2nd phase - general contingent  
- `18` = 3rd phase - general contingent  
- `26` = Ordinance No. 533-A/99, item b2) (Different Plan)  
- `27` = Ordinance No. 533-A/99, item b3 (Other Institution)  
- `39` = Over 23 years old  
- `42` = Transfer  
- `43` = Change of course  
- `44` = Technological specialization diploma holders  
- `51` = Change of institution/course  
- `53` = Short cycle diploma holders  
- `57` = Change of institution/course (International)  

### 3. Application Order  
Represents the student's preference order for the application.  
- `0` = First choice  
- `1-9` = Subsequent choices, with `9` being the last choice  

### 4. Course  
Denotes the specific course or program the student enrolled in, identified by unique codes.  
- `33` = Biofuel Production Technologies  
- `171` = Animation and Multimedia Design  
- `8014` = Social Service (evening attendance)  
- `9003` = Agronomy  
- `9070` = Communication Design  
- `9085` = Veterinary Nursing  
- `9119` = Informatics Engineering  
- `9130` = Equiniculture  
- `9147` = Management  
- `9238` = Social Service  
- `9254` = Tourism  
- `9500` = Nursing  
- `9556` = Oral Hygiene  
- `9670` = Advertising and Marketing Management  
- `9773` = Journalism and Communication  
- `9853` = Basic Education  
- `9991` = Management (evening attendance)  

### 5. Daytime/Evening Attendance  
Indicates the attendance shift.  
- `1` = Daytime  
- `0` = Evening  

### 6. Previous Qualification  
Details the student's prior educational attainment.  
- `1` = Secondary education  
- `2` = Higher education - bachelor's degree  
- `3` = Higher education - degree  
- `4` = Higher education - master's  
- `5` = Higher education - doctorate  
- `6` = Frequency of higher education  
- `9` = 12th year of schooling - not completed  
- `10` = 11th year of schooling - not completed  
- `12` = Other - 11th year of schooling  
- `14` = 10th year of schooling  
- `15` = 10th year of schooling - not completed  
- `19` = Basic education 3rd cycle (9th/10th/11th year)  
- `38` = Basic education 2nd cycle (6th/7th/8th year)  
- `39` = Technological specialization course  
- `40` = Higher education - degree (1st cycle)  
- `42` = Professional higher technical course  
- `43` = Higher education - master (2nd cycle)  

### 7. Previous Qualification (Grade)    
Grade of previous qualification (between 0 and 200)

### 8. Nationality  
Specifies the student's nationality, coded numerically.  
- `1` = Portuguese  
- `2` = German  
- `6` = Spanish  
- `10` = Italian  
- `17` = Dutch  
- `21` = British  
- `22` = Lithuanian  
- `24` = Angolan  
- `25` = Cape Verdean  
- `26` = Guinean  
- `27` = Mozambican  
- `28` = Santomean  
- `29` = Brazilian  
- `32` = Romanian  
- `41` = Moldovan  
- `62` = Ukrainian  
- `100` = Other nationality  

### 9. Mother's Qualification    
- `1` = Secondary Education - 12th Year of Schooling or Equivalent  
- `2` = Higher Education - Bachelor's Degree  
- `3` = Higher Education - Degree  
- `4` = Higher Education - Master's  
- `5` = Higher Education - Doctorate  
- `6` = Frequency of Higher Education  
- `9` = 12th Year of Schooling - Not Completed  
- `10` = 11th Year of Schooling - Not Completed  
- `11` = 7th Year (Old)  
- `12` = Other - 11th Year of Schooling  
- `14` = 10th Year of Schooling  
- `18` = General Commerce Course  
- `19` = Basic Education 3rd Cycle (9th/10th/11th Year) or Equivalent  
- `22` = Technical-Professional Course  
- `26` = 7th Year of Schooling  
- `27` = 2nd Cycle of the General High School Course  
- `29` = 9th Year of Schooling - Not Completed  
- `30` = 8th Year of Schooling  
- `34` = Unknown  
- `35` = Can't Read or Write  
- `36` = Can Read Without Having a 4th Year of Schooling  
- `37` = Basic Education 1st Cycle (4th/5th Year) or Equivalent  
- `38` = Basic Education 2nd Cycle (6th/7th/8th Year) or Equivalent  
- `39` = Technological Specialization Course  
- `40` = Higher Education - Degree (1st Cycle)  
- `41` = Specialized Higher Studies Course  
- `42` = Professional Higher Technical Course  
- `43` = Higher Education - Master (2nd Cycle)  
- `44` = Higher Education - Doctorate (3rd Cycle)  

### 10. Father's Qualification   
- `1` = Secondary Education - 12th Year of Schooling or Equivalent  
- `2` = Higher Education - Bachelor's Degree  
- `3` = Higher Education - Degree  
- `4` = Higher Education - Master's  
- `5` = Higher Education - Doctorate  
- `6` = Frequency of Higher Education  
- `9` = 12th Year of Schooling - Not Completed  
- `10` = 11th Year of Schooling - Not Completed  
- `11` = 7th Year (Old)  
- `12` = Other - 11th Year of Schooling  
- `14` = 10th Year of Schooling  
- `18` = General Commerce Course  
- `19` = Basic Education 3rd Cycle (9th/10th/11th Year) or Equivalent  
- `22` = Technical-Professional Course  
- `26` = 7th Year of Schooling  
- `27` = 2nd Cycle of the General High School Course  
- `29` = 9th Year of Schooling - Not Completed  
- `30` = 8th Year of Schooling  
- `34` = Unknown  
- `35` = Can't Read or Write  
- `36` = Can Read Without Having a 4th Year of Schooling  
- `37` = Basic Education 1st Cycle (4th/5th Year) or Equivalent  
- `38` = Basic Education 2nd Cycle (6th/7th/8th Year) or Equivalent  
- `39` = Technological Specialization Course  
- `40` = Higher Education - Degree (1st Cycle)  
- `41` = Specialized Higher Studies Course  
- `42` = Professional Higher Technical Course  
- `43` = Higher Education - Master (2nd Cycle)  
- `44` = Higher Education - Doctorate (3rd Cycle)

### 11. Mother's Occupation
- `0` = Student  
- `1` = Representatives of the Legislative Power and Executive Bodies, Directors, and Executive Managers  
- `2` = Specialists in Intellectual and Scientific Activities  
- `3` = Intermediate Level Technicians and Professions  
- `4` = Administrative Staff  
- `5` = Personal Services, Security and Safety Workers, and Sellers  
- `6` = Farmers and Skilled Workers in Agriculture, Fisheries, and Forestry  
- `7` = Skilled Workers in Industry, Construction, and Craftsmen  
- `8` = Installation and Machine Operators and Assembly Workers  
- `9` = Unskilled Workers  
- `10` = Armed Forces Professions  
- `90` = Other Situation  
- `99` = (Blank)  
- `122` = Health Professionals  
- `123` = Teachers  
- `125` = Specialists in Information and Communication Technologies (ICT)  
- `131` = Intermediate Level Science and Engineering Technicians and Professions  
- `132` = Technicians and Professionals, Intermediate Level of Health  
- `134` = Intermediate Level Technicians from Legal, Social, Sports, Cultural, and Similar Services  
- `141` = Office Workers, Secretaries in General, and Data Processing Operators  
- `143` = Data, Accounting, Statistical, Financial Services, and Registry-Related Operators  
- `144` = Other Administrative Support Staff  
- `151` = Personal Service Workers  
- `152` = Sellers  
- `153` = Personal Care Workers and the Like  
- `171` = Skilled Construction Workers and the Like, Except Electricians  
- `173` = Skilled Workers in Printing, Precision Instrument Manufacturing, Jewelers, Artisans, and the Like  
- `175` = Workers in Food Processing, Woodworking, Clothing, and Other Industries and Crafts  
- `191` = Cleaning Workers  
- `192` = Unskilled Workers in Agriculture, Animal Production, Fisheries, and Forestry  
- `193` = Unskilled Workers in Extractive Industry, Construction, Manufacturing, and Transport  
- `194` = Meal Preparation Assistants  

### 12. Father's Occupation
- `0` = Student  
- `1` = Representatives of the Legislative Power and Executive Bodies, Directors, and Executive Managers  
- `2` = Specialists in Intellectual and Scientific Activities  
- `3` = Intermediate Level Technicians and Professions  
- `4` = Administrative Staff  
- `5` = Personal Services, Security and Safety Workers, and Sellers  
- `6` = Farmers and Skilled Workers in Agriculture, Fisheries, and Forestry  
- `7` = Skilled Workers in Industry, Construction, and Craftsmen  
- `8` = Installation and Machine Operators and Assembly Workers  
- `9` = Unskilled Workers  
- `10` = Armed Forces Professions  
- `90` = Other Situation  
- `99` = (Blank)  
- `122` = Health Professionals  
- `123` = Teachers  
- `125` = Specialists in Information and Communication Technologies (ICT)  
- `131` = Intermediate Level Science and Engineering Technicians and Professions  
- `132` = Technicians and Professionals, Intermediate Level of Health  
- `134` = Intermediate Level Technicians from Legal, Social, Sports, Cultural, and Similar Services  
- `141` = Office Workers, Secretaries in General, and Data Processing Operators  
- `143` = Data, Accounting, Statistical, Financial Services, and Registry-Related Operators  
- `144` = Other Administrative Support Staff  
- `151` = Personal Service Workers  
- `152` = Sellers  
- `153` = Personal Care Workers and the Like  
- `171` = Skilled Construction Workers and the Like, Except Electricians  
- `173` = Skilled Workers in Printing, Precision Instrument Manufacturing, Jewelers, Artisans, and the Like  
- `175` = Workers in Food Processing, Woodworking, Clothing, and Other Industries and Crafts  
- `191` = Cleaning Workers  
- `192` = Unskilled Workers in Agriculture, Animal Production, Fisheries, and Forestry  
- `193` = Unskilled Workers in Extractive Industry, Construction, Manufacturing, and Transport  
- `194` = Meal Preparation Assistants  

### 13. Admission Grade
Admission grade (between 0 and 200)

### 14. Displaced  
Indicates whether the student is displaced from their usual place of residence.  
- `1` = Yes  
- `0` = No  

### 15. Educational Special Needs  
Specifies if the student has special educational needs.  
- `1` = Yes  
- `0` = No  

### 16. Debtor  
Indicates if the student has any outstanding debts to the institution.  
- `1` = Yes  
- `0` = No  

### 17. Tuition Fees Up to Date  
Specifies if the student's tuition fees are paid up to date.  
- `1` = Yes  
- `0` = No  

### 18. Gender  
The student's gender.  
- `1` = Male  
- `0` = Female  

### 19. Scholarship Holder  
Indicates if the student is a scholarship recipient.  
- `1` = Yes  
- `0` = No  

### 20. Age at Enrollment  
The student's age at the time of enrollment.  

### 21. International  
Specifies if the student is an international student.  
- `1` = Yes  
- `0` = No  

### 22. Curricular Units (Per Semester)  
Curricular Units (credited)
Number of courses/subjects in the semester for which the student is awarded credits without needing to complete them again. This often happens if a student transferred from another institution or received credit for prior learning.

Curricular Units (enrolled)
How many courses the student is officially registered for the semester.

Curricular Units (evaluations)
Out of the courses the student enrolled in, how many actually had some form of evaluation (exams, graded assignments, etc.) completed.

Curricular Units (approved)
Number of semester courses that the student passed (i.e., earned a passing grade).

Curricular Units (grade)
The average grade for the student’s semester courses

Curricular Units (without evaluations)
Number of courses the student enrolled in but never took any assessments (i.e., no exams or major assignments submitted).

### 23. Economic Indicators  
- **Unemployment Rate**: Unemployment rate in the student's residential area.  
- **Inflation Rate**: Inflation rate in the student's residential area.  
- **GDP**: Gross Domestic Product per capita in the student's residential area.  

### 24. Target (Student Academic Outcome)
- `0` = Dropped out  
- `1` = Enrolled  
- `2` = Graduated

# Methodology

## 1. Data Cleaning
- **Missing Values:** No missing values found.  
- **Data Types:** All columns are numerical except the target column.  
- **Conclusion:** No data cleaning required.  

## 2. Data Exploration and Feature Selection
- Transformed the target column:  
  - Dropout → `0`  
  - Enrolled → `1`  
  - Graduate → `2`  
- Used a **Seaborn heatmap** to analyze feature correlations and reduce redundancy among curriculum-related features.  
- Finalized feature selection before proceeding with modeling.  

## 3. Model Selection and Training
- Implemented **XGBoost** and **Random Forest**, selecting the model with higher accuracy.  
- If both models have equal accuracy, either one is chosen.  

## 4. Model Interpretation
- Utilized **SHAP** for both local and global interpretability.  
- Used **LIME** for additional local interpretability.  

