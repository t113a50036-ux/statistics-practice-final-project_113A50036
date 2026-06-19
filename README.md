# Final-Project_113A50036

## Project Repository
https://github.com/t113a50036-ux/statistics-practice-cycle3-group2

## Presentation Video
https://drive.google.com/file/d/1u6xUp8odpDos-jYxNLHEVuJzCgugs81t/view?usp=drivesdk

## Members:
| Name | Student ID |
| :--- | :--- |
| 吳婕綾 | 113370205 |
| 賴映彤 | 113A50036 |

## Research Question
* **Selected Question**: Question 1 
* **Research Question**: Is the proportion of current cigarette use different between male and female students?

---

## Variables and Definitions
* **Group Variable**: `WhatIsYourSex` 
   **Group 1**: Male students (Original Code 1)
   **Group 2**: Female students (Original Code 2)
 **Response Variable**: `CurrentCigaretteUse`
   **Success (1)**: Currently uses cigarettes (Original Codes 2-7)
   **Failure (0)**: Does not currently use cigarettes (Original Code 1)

---

## Methodology
* **Statistical Method**: Two-proportion z-test
* **Significance Level**: 0.05
* **Assumptions Considered**:
    1. Independent observations between groups.
    2. Appropriate response variable (Binary/Categorical).
    3. Large enough sample size for the z-test.
        

---

## Final Conclusion
* **Summary**: Our analysis shows a statistically [significant] difference in the proportion of current cigarette use between male and female students (p-value = [5.138341623910967e-10]). Specifically, [Female] students had a higher smoking proportion of [21.576384662203288]% compared to [17.31454005934718]% in the other group.

---

## Project Structure
* `README.md/`: Project overview and summary.
* `data/raw/`: Contains the original `YRBS_2007.csv` file.
* `data/processed/`: Contains the cleaned or recoded data.
* `notebooks/`: Contains the Python code for data loading, recoding, and statistical analysis.
* `outputs/`: final figures and summary tables.
