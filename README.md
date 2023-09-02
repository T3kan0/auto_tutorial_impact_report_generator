# auto_tutorial_impact_report_generator
Tekano Mbonani

## System Docs 📃
An automated, user-interactive tutorial attendance impact PDF report generator. Using a combination of ***R*** and ***python*** languages, the code performs hypothesis testing and linear regression/ correlation analysis between student tutorial attendance and their final exam marks. The code requires student tutorial attedance and performance data files to compile a tutorial impact report per faculty, term (semester) and campus. The code is user-interactive, the user must know the faculty, term and campus they want to report on. To achieve this, the data is combined to determine student attendance frequency per module (subject) for the selected faculty, term and campus. The majority of the ***python*** code is modularized through functions to get a clean code, therefore, the user needs to run only one of these. I wrote the report for a large tutorial project for students of the University of Free State, comprised of seven academic faculties and three learning campuses. The code allowed my clients to assess the project's performance and impact on its attendees, in real-time, within minutes.

## Software Requirements 🔌
You will need to install the following software on your system in order to run/edit the Python script.
* Mac OS/ Ubuntu 18.04 OS
* Python 3.10.12
* Textedit/ IDE - spyder or jupyter-notebook
* Python libraries
  * Numpy
  * Matplotlib
  * Sklearn
  * PIL
  * glob
    
### About the Data 💾 
The data used here was generated randomly with the ***numpy python*** library. The data is meant to only help us see how the different Polynomial orders can fit the data. For us to see things to avoid when fitting the data, such as overfitting when the order of the polynomial function gets high. In this case, the data was best fit with a polynomial function of the first order, i.e., Linear. 

<p align="center">
  <img align="center" width="300" height="500" src="https://github.com/T3kan0/auto_tutorial_impact_report_generator/blob/main/report_pg1.png">
</p>

<p align="center">
  <img align="center" width="300" height="500" src="https://github.com/T3kan0/auto_tutorial_impact_report_generator/blob/main/report_pg3.png">
</p>

<p align="center">
  <img align="center" width="300" height="500" src="https://github.com/T3kan0/auto_tutorial_impact_report_generator/blob/main/report_pg4.png">
</p>

