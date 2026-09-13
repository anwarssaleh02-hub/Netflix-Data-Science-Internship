\# Netflix Data Science Internship Project



\## Project Overview



This project was completed as part of a Data Science Internship. The project uses a Netflix dataset to perform data cleaning, exploratory data analysis, recommendation system analysis, trend prediction, machine learning classification, and business insights visualization.



The main goal is to demonstrate practical Data Science skills using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.



\## Dataset



The dataset contains Netflix titles with information such as:



\* Show ID

\* Content Type

\* Title

\* Director

\* Country

\* Date Added

\* Release Year

\* Rating

\* Duration

\* Categories



The original raw dataset (`Dataset.csv`) is not included in this public repository because it is excluded through `.gitignore`.



A cleaned version of the dataset is provided as:



`Netflix\_cleaned.csv`



\## Technologies Used



\* Python

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* Scikit-learn

\* Jupyter Notebook

\* Git and GitHub



\## Tasks Completed



\### Task 1 — Data Cleaning \& Preprocessing



The dataset was inspected and cleaned by:



\* Checking dataset structure and data types

\* Identifying missing values

\* Checking duplicate records

\* Converting date-related columns

\* Separating movie duration and TV show seasons

\* Extracting year and month information

\* Cleaning text columns

\* Creating a cleaned dataset



Output:



`Netflix\_cleaned.csv`



\### Task 2 — Exploratory Data Analysis



The dataset was analyzed to understand Netflix content distribution.



The analysis included:



\* Movies vs TV Shows

\* Top countries

\* Top content categories

\* Content ratings

\* Titles added by year

\* Movie duration

\* Release-year distribution



Visualizations were created using Matplotlib and Seaborn.



\### Task 3 — Recommendation System Analysis



A content-based recommendation system was developed using:



\* TF-IDF vectorization

\* Content features

\* Cosine similarity



The recommendation system uses metadata such as:



\* Content type

\* Director

\* Country

\* Categories

\* Rating



The system can recommend titles that are similar to a selected Netflix title.



\### Task 4 — Trend Prediction Analysis



A Linear Regression model was used to analyze and predict the yearly number of titles added to Netflix.



The model achieved:



\* MAE: 346.07

\* RMSE: 390.31

\* R²: 0.75



Future yearly title additions were also estimated using the model.



\### Task 5 — Machine Learning Classification



Machine Learning models were developed to classify Netflix content as either:



\* Movie

\* TV Show



The models evaluated were:



\* Logistic Regression

\* Decision Tree

\* Random Forest



The best-performing model was Random Forest.



| Model               | Accuracy | Precision | Recall | F1-Score |

| ------------------- | -------: | --------: | -----: | -------: |

| Logistic Regression |    0.706 |     0.583 |  0.105 |    0.178 |

| Decision Tree       |    0.709 |     0.525 |  0.409 |    0.460 |

| Random Forest       |    0.720 |     0.547 |  0.445 |    0.491 |



The Random Forest model achieved the highest overall accuracy and F1-score among the tested models.



\### Task 6 — Business Insights Dashboard



A business insights dashboard was created to summarize important patterns in the Netflix dataset.



The dashboard presents:



\* Content type distribution

\* Top countries

\* Top categories

\* Content additions over time



Output:



`Netflix\_Business\_Insights\_Dashboard.png`



\## Key Findings



Some important findings from the analysis include:



1\. Movies represent the majority of Netflix content in the dataset.

2\. International content is highly represented.

3\. Dramas and comedies are among the major content categories.

4\. Netflix content additions increased strongly over the analyzed period, reaching a peak around 2019.

5\. TV-MA and TV-14 are among the most common content ratings.

6\. Random Forest performed best among the classification models tested.

7\. The recommendation system demonstrates how metadata can be used to find similar titles.



\## Project Structure



```text

Netflix-Data-Science-Internship/

│

├── Netflix.ipynb

├── Netflix\_cleaned.csv

├── Netflix\_Business\_Insights\_Dashboard.png

├── DATA SCIENCE TASK LIST.pdf

├── Screenshot output/

│   ├── Clean Dataset.png

│   ├── Context By Type.png

│   ├── Context by ranting.png

│   ├── Copmarison classification.png

│   ├── Dashborad.png

│   ├── Duplicate.png

│   ├── Missing Value.png

│   ├── Movie duration.png

│   ├── Released year.png

│   ├── Similarty scores .png

│   ├── Title added by Year.png

│   ├── Top 10 Countries.png

│   └── Trend and prediction.png

│

└── .gitignore

```



\## How to Run the Project



1\. Clone or download this repository.

2\. Open `Netflix.ipynb` using Jupyter Notebook or JupyterLab.

3\. Make sure the required Python libraries are installed.

4\. Run the notebook cells in order.

5\. The notebook contains the complete analysis for Tasks 1–6.



\## Limitations



\* The recommendation system uses available metadata rather than full descriptions or plot information.

\* The trend prediction model is based on a limited number of yearly observations and uses a simple Linear Regression approach.

\* The classification task predicts content type using available non-duration features, so the model is intended as a demonstration of machine-learning classification rather than a production system.



\## Conclusion



This project demonstrates an end-to-end Data Science workflow, from data preprocessing and exploratory analysis to recommendation systems, trend prediction, machine learning classification, and business visualization.



The project provides practical experience in applying Python and Machine Learning techniques to a real-world dataset.



\## Author



\*\*ANWAR SALEH\*\*



GitHub: `anwarssaleh02-hub`



