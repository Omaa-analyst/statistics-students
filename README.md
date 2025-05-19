statistics-students

 📊 AI Anxiety & Career Outlook: Statistics Students 

This project explores how **undergraduate statistics students** from public universities Turkey perceive the impact of Artificial Intelligence (AI) and automation on their future careers. The data was gathered from students at:

Hacettepe University
Ankara University
Gazi University
Middle East Technical University (METU)

 Dataset

The dataset used: 
It includes survey responses from students and contains:

* `University`
* `Concern Level` about AI
* `Anxiety Level`
* `Internship Experience` (Yes/No)
* `GPA`
* `Year of Study`


 Project Objectives

* Measure concern and anxiety levels about AI across universities.
* Investigate how factors like **GPA**, **internships**, and **year of study** influence attitudes toward AI.
* Use statistical tests (Chi-square) to identify significant relationships.
* Visualize student responses by category and university.


 Key Analyses

 1. Crosstab Analysis

* Grouped responses by `University` and `Concern Level`.
* Normalized tables used to show percentage distributions (e.g., 59.4% Yes, 40.6% No).

 2. Chi-Square Test of Independence

* Tested if students' concern levels are significantly associated with their university.
* Used `scipy.stats.chi2_contingency`.

 3. Visualizations

* Bar plots to compare concern levels across universities.
* Conditional tagging (e.g., labeling balanced responses like 50/50 as `"Yes"` for neutrality).
* Heatmaps to visually highlight variations in perception.


 Notable Findings

* METU students tend to be more evenly split in their concern about AI (balanced responses).
* Hacettepe and Gazi students show stronger leanings toward concern.
* Internship experience slightly lowers anxiety levels.
* Students with higher GPAs tend to view AI more positively.


 Requirements

* Python 3.7+
* Libraries:

  ```bash
  pandas
  numpy
  matplotlib
  seaborn
  scipy
  plotly
  ```


