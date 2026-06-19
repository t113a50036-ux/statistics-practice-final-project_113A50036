# Final-Project_113A50036

## Project Repository
https://github.com/t113a50036-ux/statistics-practice-final-project_113A50036

## Presentation Video


## Members:
| Name | Student ID |
| :--- | :--- |
| 賴映彤 | 113A50036 |

## Research Question
Does the frequency of weekly aerobic exercise have a statistically significant impact on the daily sleep hours of high school students?

---

## Variables and Definitions
* **Group Variable**: `AerobicExercise` 
  * **Group 1**: Engages in aerobic exercise 0–1 days per week (Original Code 1,2)
  * **Group 2**: Engages in aerobic exercise 2–4 days per week (Original Code 3,4,5)
  * **Group 3**: Engages in aerobic exercise 5–7 days per week (Original Code 6,7,8)
* **Response Variable**: `Sleep`
  * Represents the actual daily sleep duration, expressed as integer values ranging from 4.0 to 10.0 hours(Original Code 1,2,3,4,5,6,7)

---

## Methodology
* **Statistical Method**: One-way ANOVA
* **Significance Level**: 0.05
* **Assumptions Considered**:
    1. **Independence**:Data collected via independent random sampling from the nationwide YRBS_2007 system.
    2. **Normality**:With a massive sample size ($N = 12,042$), the Central Limit Theorem guarantees that the normality assumption for ANOVA is fully satisfied..
    3. **Homogeneity of Variance**: Checked via group distribution variances prior to running the inferential models.
        

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
