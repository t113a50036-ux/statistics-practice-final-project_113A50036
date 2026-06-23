# Final-Project_113A50036

## Project Repository
https://github.com/t113a50036-ux/statistics-practice-final-project_113A50036

## Presentation Video
https://youtu.be/WDqhUruRBAk?si=CTSZlqL7ruMrEcBX

## Members:
| Name | Student ID |
| :--- | :--- |
| 賴映彤 | 113A50036 |

## Project Overview
This project utilizes the 2007 Youth Risk Behavior Survey (YRBS) dataset to analyze health-related behaviors and physical metrics among US high school students. The primary analysis focuses on daily sleep duration and weekly aerobic exercise frequency to determine whether intensive physical activity significantly impacts adolescent rest patterns. Evaluated through a comprehensive nationwide sample ($N = 12,042$) and inspired by personal, real-world experience, this study investigates whether the heavy physical demands of commitments—such as dance clubs or school sports teams—compromise or promote overall sleep health under the structural constraints of rigid academic schedules.

## Research Question
Does Weekly Aerobic Exercise Frequency Significantly Affect Daily Sleep Hours in High School Students?

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
* **Summary**: Analyzing 12,042 samples, the One-way ANOVA yielded extreme significance ($F = 41.2666, p = 1.3781 \times 10^{-18}$), rejecting the hypothesis that exercise compresses sleep. The intensive group (**High**, e.g., dance clubs/sports teams) achieved the highest daily sleep (**6.93 hours**), while the sedentary group (**Low**) slept the least (**6.67 hours**). This proves that high-frequency physical exertion triggers a powerful biological drive for recovery, allowing active students to negotiate an extra 15 to 20 minutes of crucial sleep under rigid school schedules, whereas non-exercising peers suffer from worse sleep deprivation.

---

## Project Structure
* `README.md/`: Project overview and summary.
* `data/raw/`: Contains the original `YRBS_2007.csv` file.
* `data/processed/`: Contains the cleaned or recoded data.
* `notebooks/`: Contains the Python code for data loading, recoding, and statistical analysis.
* `outputs/`: final figures and summary tables.
