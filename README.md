# auto_tutorial_impact_report_generator
Tekano Mbonani

## System Docs 📃
An automated, user-interactive tutorial attendance impact PDF report generator. Using a combination of ***R*** and ***python*** languages, the code performs hypothesis testing and linear regression/correlation analysis between student tutorial attendance and their final exam marks, to determine the tutorial impact on students. The code requires student tutorial attedance and performance data files to compile a tutorial impact report per faculty, term (semester) and campus. The code is user-interactive, the user must know the faculty, term and campus they want to report on. To achieve this, the data is combined to determine student attendance frequency per module (subject) for the selected faculty, term and campus. The majority of the ***python*** code is modularized through functions to get a clean code, therefore, the user needs to run only one of these. I wrote these codes for a large tutorial project for students of the University of Free State, comprised of seven academic faculties on three learning campuses. The code allowed my clients to assess the project's performance and impact on its attendees, in real-time, within minutes.

## Software Requirements 🔌
You will need to install the following software on your system in order to run/edit the Python and R scripts.
* Mac OS/ Ubuntu 18.04 OS
* Python 3.10.12
* R 4.3.1
* Textedit/ IDE - spyder, jupyter-notebook or R-studio
* libraries
  * pandas
  * numpy
  * scipy
  * pyreadr
  * datetime
  * fpdf
  * matplotlib
  * seaborn
  * glob
  * dplyr

### About the Data 💾 
The data used here was collected between 2019 and the first term of 2022, by the tutorial project of students on the University of Free State. The data was collected and stored weekly, where I have access to perform statistical analysis and reporting.
### Running the code
As mentioned, the first step is to load, combine the tutorial attendance and performance data files, as well as calculating student tutorial frequency, this is done by the ***R*** code:

> $ source("dataCompile.R")

Once the data is prepared and freuency is determined, the user must open the code ***pyttea.ipynb*** on **jupyter-notebook**. Run the entire code on "Run All", enter the FACULTY, TERM, CAMPUS and wait, a PDF report will be the output. In the example below, the report is for the faculty of LAW, for the first terms, i.e., SEM1 on the MAIN campus. The full document is available here https://github.com/T3kan0/auto_tutorial_impact_report_generator/blob/main/Faculty_Reports/A_STEP_IR_LAW_SEM1_MAIN_2019_2022.pdf

<p align="center">
  <img align="center" width="300" height="500" src="https://github.com/T3kan0/auto_tutorial_impact_report_generator/blob/main/report_pg1.png">
</p>

<p align="center">
  <img align="center" width="300" height="500" src="https://github.com/T3kan0/auto_tutorial_impact_report_generator/blob/main/report_pg3.png">
</p>

<p align="center">
  <img align="center" width="300" height="500" src="https://github.com/T3kan0/auto_tutorial_impact_report_generator/blob/main/report_pg4.png">
</p>

