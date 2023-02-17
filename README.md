Vithersan Somasundaram | January 2023 | vithersan.somasundaram@uzh.ch

MASTER THESIS
----------------------------------------------------------------------------

## About the project:

This project is a master thesis project for the master program in biostatistics at the University of Zurich, Switzerland with the project title:

- **From a "Spiel Popeye und miss Deine Greifkraft" activity to Swiss norms for handgrip strength**

This master thesis assess the validity of existing Swiss norms for adults. Further, it assess whether handgrip strength values are stable independent of the posture-elbow position. Finally,  this master thesis provides recommendations for the development of norms and optimal posture-elbow position of children and adults.

Involved in this project are: 

- Master Student **Vithersan Somasundaram**, vithersan.somasundaram@uzh.ch

- Supervisor **Prof. Dr. med. Susi Kriemler**, susanne.kriemlerwiget@uzh.ch 
- Supervisor **PD PhD Malgorzata Roos**, malgorzata.roos@uzh.ch

## Description of the subfolder

Folder **Bilder**

- Contains graphics and pictures used or taken at the DOOD for the report

Folder **code**

- Contains the R files used for this master thesis report

Folder **data**

- Contains raw data and clean data of the analysis

Folder **report**

- Contains the Rnw files which was used to generate the reproducible master thesis report with knitr

## Where to find the master thesis?

- The master thesis can be found as a pdf-file on the [Homepage](https://www.biostat.uzh.ch/index.php?id=master_theses&L=1) of the Master’s program in Biostatistics with open access to R code and data analysis.

- Another option is to use this received file ("Master Thesis Hand Grip Strength")

  1. Open the file and go to the folder **report**. In this folder you will see the R project which is named **report.Rproj**.
 
  2. Open the Project  **report.Rproj** in R-Studio
 
  3. Check your R Version. (For this report Version 4.1.2, 2021-11-1, was used)
 
  4. If necessary, see the following code to install all the required R packages: 
    
      - install.packages(c("xtable", "vtable", "BlandAltmanLeh", "rstatix", "lme4", "lmerTest",          "DescTools", "ggpubr", "kableExtra", "tidyverse"))
    
  5. Check in RStudio if knitr is used for compiling:
 
      - Tools > Global Options > Sweave > **Weave Rnw files using:** *knitr*
      
  6. **IOS User:** Open the script with the name MSc_Report.Rnw and press the *compile PDF* button.
  
      **Windows user:** Open the script with the name MSc_Report.Rnw and press *build all* to get a pdf file.
     
----------------------------------------------------------------------------------------------------------  

## Installation instruction for LaTex and knitr setting for (Windows User)

  **Note:** In order to compile the report without errors, latex must be installed on your computer. 
  
  **I.) How to install LaTex (MiKTex) in RStudio:**
  
  - Download and install MiKtex via: https://miktex.org
  
  - **For IOS user** there is usually no error.
  
  - **For Windows user**, it can happen that an error message occurs, for example : *Rstudio pdflatex.exe did not succeed*. 
    
    - This happens because with the new installation of MiKTeX, many style files needed to knit a RMarkdown file to PDF are not installed. You need to allow MiKTeX to install them on the fly.
  
    - Open the MiKTeX console and go to the Settings tab
  
    - There is an option that says you can choose whether missing packages are to be installed automatically (on-the-fly)
  
    - Make sure that this is set to always to allow the necessary style files to be installed
    
    - Make sure to check for updates and install them 
    (see explanation here: https://miktex.org/howto/update-miktex)

  **II.) How to install make in RStudio:**
 
  - First, install chocolately in the administrative shell [PowerShell]( https://www.howtogeek.com/194041/how-to-open-the-command-prompt-as-administrator-in-windows-8.1/)
  
    - explained here step-by-step: https://chocolatey.org/install#individual
  
  - Afterwards, install make, by run the following command in the administrative shell:
  
   > choco install make
  
  - Finally, install Perl see: https://strawberryperl.com 
  

  

