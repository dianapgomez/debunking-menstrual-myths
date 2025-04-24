## 1. Dataset Menstrual Cycle Data
[Fuente](https://www.kaggle.com/datasets/nikitabisht/menstrual-cycle-data/data)

### Exploratory data analysis:

📌**NOTE: Only selected columns are included.**


- `ClientID`: Identification number.
- `CycleNumber`: Number of menstrual cycle tracked. 
- `LengthofCycle`: Menstrual cycle duration.
- `MeanCycleLength`: Mean menstrual cycle duration
- `EstimatedDayofOvulation`: Ovulation day stimated.
- `LengthofLutealPhase`: Luteal phase duration.
- `LengthofMenses`: Days of bleeding.
- `MeanMensesLength`: Avg. days of bleeding.
- `MensesScoreDayOne`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDayTwo`: Score for menses in day 2 (from 1 to 3)
- `MensesScoreDayThree`: Score for menses in day 3 (from 1 to 3)
- `MensesScoreDayFour`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDayFive`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDaySix`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDaySeven`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDayEight`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDayNine`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDayTen`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDay11`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDay12`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDay13`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDay14`: Score for menses in day 1 (from 1 to 3)
- `MensesScoreDay15`: Score for menses in day 1 (from 1 to 3)
- `TotalMensesScore`: Score for menses in total.
- `MeanBleedingIntensity`:
- `UnusualBleeding`:
- `PhasesBleeding`
- `Age`:
- `Ethnicity`:
- `BMI`:


### 1. Data type:
```python
RangeIndex: 1665 entries, 0 to 1664
Data columns (total 80 columns):
 #   Column                      Non-Null Count  Dtype 
---  ------                      --------------  ----- 
 0   ClientID                    1665 non-null   object
 1   CycleNumber                 1665 non-null   int64 
 2   Group                       1665 non-null   int64 
 3   CycleWithPeakorNot          1665 non-null   int64 
 4   ReproductiveCategory        1665 non-null   int64 
 5   LengthofCycle               1665 non-null   int64 
 6   MeanCycleLength             1665 non-null   object
 7   EstimatedDayofOvulation     1665 non-null   object
 8   LengthofLutealPhase         1665 non-null   object
 9   FirstDayofHigh              1665 non-null   object
 10  TotalNumberofHighDays       1665 non-null   object
 11  TotalHighPostPeak           1665 non-null   object
 12  TotalNumberofPeakDays       1665 non-null   object
 13  TotalDaysofFertility        1665 non-null   object
 14  TotalFertilityFormula       1665 non-null   object
 15  LengthofMenses              1665 non-null   object
 16  MeanMensesLength            1665 non-null   object
 17  MensesScoreDayOne           1665 non-null   object
 18  MensesScoreDayTwo           1665 non-null   object
 19  MensesScoreDayThree         1665 non-null   object
 20  MensesScoreDayFour          1665 non-null   object
 21  MensesScoreDayFive          1665 non-null   object
 22  MensesScoreDaySix           1665 non-null   object
 23  MensesScoreDaySeven         1665 non-null   object
 24  MensesScoreDayEight         1665 non-null   object
 25  MensesScoreDayNine          1665 non-null   object
 26  MensesScoreDayTen           1665 non-null   object
 27  MensesScoreDay11            1665 non-null   object
 28  MensesScoreDay12            1665 non-null   object
 29  MensesScoreDay13            1665 non-null   object
 30  MensesScoreDay14            1665 non-null   object
 31  MensesScoreDay15            1665 non-null   object
 32  TotalMensesScore            1665 non-null   object
 33  MeanBleedingIntensity       1665 non-null   object
 34  NumberofDaysofIntercourse   1665 non-null   object
 35  IntercourseInFertileWindow  1665 non-null   object
 36  UnusualBleeding             1665 non-null   object
 37  PhasesBleeding              1665 non-null   object
 38  IntercourseDuringUnusBleed  1665 non-null   object
 39  Age                         1665 non-null   object
 40  AgeM                        1665 non-null   object
 41  Maristatus                  1665 non-null   object
 42  MaristatusM                 1665 non-null   object
 43  Yearsmarried                1665 non-null   object
 44  Wedding                     1665 non-null   object
 45  Religion                    1665 non-null   object
 46  ReligionM                   1665 non-null   object
 47  Ethnicity                   1665 non-null   object
 48  EthnicityM                  1665 non-null   object
 49  Schoolyears                 1665 non-null   object
 50  SchoolyearsM                1665 non-null   object
 51  OccupationM                 1665 non-null   object
 52  IncomeM                     1665 non-null   object
 53  Height                      1665 non-null   object
 54  Weight                      1665 non-null   object
 55  Reprocate                   1665 non-null   object
 56  Numberpreg                  1665 non-null   object
 57  Livingkids                  1665 non-null   object
 58  Miscarriages                1665 non-null   object
 59  Abortions                   1665 non-null   object
 60  Medvits                     1665 non-null   object
 61  Medvitexplain               1665 non-null   object
 62  Gynosurgeries               1665 non-null   object
 63  LivingkidsM                 1665 non-null   object
 64  Boys                        1665 non-null   object
 65  Girls                       1665 non-null   object
 66  MedvitsM                    1665 non-null   object
 67  MedvitexplainM              1665 non-null   object
 68  Urosurgeries                1665 non-null   object
 69  Breastfeeding               1665 non-null   object
 70  Method                      1665 non-null   object
 71  Prevmethod                  1665 non-null   object
 72  Methoddate                  1665 non-null   object
 73  Whychart                    1665 non-null   object
 74  Nextpreg                    1665 non-null   object
 75  NextpregM                   1665 non-null   object
 76  Spousesame                  1665 non-null   object
 77  SpousesameM                 1665 non-null   object
 78  Timeattemptpreg             1665 non-null   object
 79  BMI                         1665 non-null   object
dtypes: int64(5), object(75)
memory usage: 1.0+ MB
```


### 2.  Identifying null values:

Null values are empty entries. 

**Number of empty entries by column:**

- `MeanCycleLength`: 1524
- `LengthofMenses`: 4 
- `MeanMensesLength`: 1524
- `MensesScoreDayOne`: 
- `MensesScoreDayTwo`:
- `MensesScoreDayThree`:
- `MensesScoreDayFour`:
- `MensesScoreDayFive`:
- `MensesScoreDaySix`:
- `MensesScoreDaySeven`:
- `MensesScoreDayEight`:
- `MensesScoreDayNine`:
- `MensesScoreDayTen`:
- `MensesScoreDay11`:
- `MensesScoreDay12`:
- `MensesScoreDay13`:
- `MensesScoreDay14`:
- `MensesScoreDay15`:
- `TotalMensesScore`:

### 3.  Identifying duplicates:
There are no duplicates.

