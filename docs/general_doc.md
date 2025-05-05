# Dataset Documentation: `discharged_f.csv`

## General Description
This dataset contains aggregated information on hospital discharges of female patients, categorized by the main diagnosis (using the ICD-10-MC coding system), the reason for discharge, and the total number of recorded cases.

## :receipt: Columns

| Column                          | Type              | Description                                                                 |
|---------------------------------|-------------------|------------------------------------------------------------------------------|
| *(Implicit index)*              | Integer           | Sequential row number (appears to be a row identifier, though unnamed).     |
| `Main Diagnosis (ICD-10-MC)`    | Text              | Code and description of the main diagnosis according to the ICD-10-MC system. Example: `0212 Leiomyoma uterine D25`. |
| `Sex`                           | Text              | Gender of the patients. This file contains only `"Female"`.                 |
| `Reason for Discharge`          | Text              | The reason for the medical discharge. Examples: `"total"`, `"recovery or improvement"`. |
| `Total`                         | Numeric (decimal) | Total number of hospital discharges for that diagnosis and reason. Uses a comma as the decimal separator in the original CSV. Example: `19.987`. |

# 📄 Dataset Documentation: `discharged_fm.csv`

## General Description  
This dataset contains hospital discharge data categorized by diagnosis group (ICD-10-MC), patient sex (both sexes), reason for discharge, and total number of discharges.

## 🧾 Columns

| Column                          | Type              | Description                                                                 |
|---------------------------------|-------------------|------------------------------------------------------------------------------|
| *(Implicit index)*              | Integer           | Sequential row number (appears to be a row identifier, though unnamed).     |
| `Main Diagnosis (ICD-10-MC)`    | Text              | Diagnosis group with ICD-10-MC code and description. Example: `0400 ENDOCRINE, NUTRITIONAL AND METABOLIC DISEASES E00-E89`. |
| `Sex`                           | Text              | `"Both sexes"` in this dataset.                                             |
| `Reason for Discharge`          | Text              | The reason for hospital discharge. Examples: `"total"`, `"recovery or improvement"`. |
| `Total`                         | Numeric (decimal) | Total number of discharges. Uses comma as decimal separator. Example: `95.934`. |

# 📄 Dataset Documentation: `mens_cycle.csv`

## General Description  
This dataset likely originates from a menstrual health tracking application. It contains personal health metrics including stress, sleep, and exercise, along with menstrual cycle details.

## 🧾 Columns

| Column              | Type    | Description                                                                 |
|---------------------|---------|------------------------------------------------------------------------------|
| `User ID`           | Integer | Anonymized user identifier.                                                  |
| `Age`               | Integer | Age of the individual.                                                      |
| `BMI`               | Float   | Body Mass Index.                                                            |
| `Stress Level`      | Integer | Numeric scale of perceived stress.                                          |
| `Exercise Frequency`| Text    | Frequency of exercise (e.g., `"Moderate"`).                                 |
| `Sleep Hours`       | Float   | Average hours of sleep per night.                                           |
| `Cycle Length`      | Integer | Length of the menstrual cycle in days.                                      |
| `Period Length`     | Integer | Duration of menstruation in days.                                           |
| `Symptoms`          | Text    | Reported symptoms during the cycle (e.g., `"Headache"`, `"Fatigue"`).       |

# 📄 Dataset Documentation: `pcos.csv`

## General Description  
This dataset includes clinical indicators for evaluating potential Polycystic Ovary Syndrome (PCOS) in women, based on hormone levels and reproductive markers.

## 🧾 Columns

| Column                        | Type    | Description                                                                 |
|-------------------------------|---------|------------------------------------------------------------------------------|
| `Age`                         | Integer | Age of the individual.                                                      |
| `BMI`                         | Float   | Body Mass Index.                                                            |
| `Menstrual_Irregularity`      | Text    | Indicates if the patient has irregular periods (`Yes`/`No`).               |
| `Testosterone_Level(ng/dL)`   | Float   | Testosterone hormone level in nanograms per deciliter.                     |
| `Antral_Follicle_Count`       | Integer | Number of antral follicles observed via ultrasound.                        |
| `PCOS_Diagnosis`              | Text    | Whether the patient was diagnosed with PCOS (`Yes`/`No`).                  |

