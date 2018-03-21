# GrantCheck

This code checks grant applications. It uses Python 3 and a number of libraries - see requirements.txt.

## Contents 

**(1) Raw data** - the zip can be extracted either manually or programmatically with Python shutil

**(2) report.xlsx** - an open format Excel template to be used for the final report

**(3) Python scripts**

To note that the main Python script contains clearly demarcated sections which can (if desired) be run in parallel to improve speed.

- *dw.py* - module with data analysis functions (imported programmatically by other scripts) 

- *extractExcel.py* - extract grant application spreadsheets and into a small number of neat tables

- *riskScript.py* - this produces risk flags and inserts them into the Excel report


## Contact:

This code is maintained by [insert email address]



