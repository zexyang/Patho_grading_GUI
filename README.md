# Patho_grading_GUI
CSE583 Project (AUT 2023) (zexyang_testing)



## System requirements
The following packages are required, many of which come with Python. This code has been tested with the version number indicated, though other versions may also work.
- numpy 1.23.3
- pandas 1.4.4
- matplotlib 3.5.3
- seaborn 0.12.2
- scikit-learn 1.1.3
- scipy 1.9.3


## Data
Number of biopsy (filtered) : 145

Number of patients (filtered) : 52

3 CSV files in the /Data folder:
- `human-observer-study-feedback-2D-2022-9-20.csv`:
        Grades given by 6 pathologists viewing 2D patho images.
- `human-observer-study-feedback-3D-2022-12-20.csv`: 
        Grades given by 6 pathologists viewing 3D patho images.
- `5yrBCR.csv`: BCR outcome for all patients

## Run example:

```bash
python GUI.py 2D
```



