# 🐾 **Analysis of Dog Rehoming Times Using Statistical Methods in R**

## 📚 **Project Overview**  
This repository contains the **MATH5741M coursework project**, focused on analyzing **dog rehoming times** across different breeds using **statistical methods and R programming**. The objective was to investigate whether rehoming times vary significantly between breeds and identify patterns to aid in improving adoption strategies for animal shelters.

## 🎯 **Project Objectives**
- Analyze **rehoming times** for three dog breeds.  
- Perform **hypothesis testing (z-tests, t-tests)** to assess differences in mean rehoming times.  
- Use **graphical summaries (histograms, QQ plots)** to visualize data distributions.  
- Provide insights into **breed-specific rehoming trends** to inform better adoption strategies.

## 📊 **Data Description**
- **Dataset:** `Dog Rehoming Time Analysis.RData` (Generated from `rehoming.Rdata` via student-specific sampling).  
- **Variables Included:**  
   - `Rehomed`: Total rehoming time (weeks).  
   - `Visited`: Time until the first visit by a potential owner (weeks).  
   - `Health`: Health score (0-100).  
   - `Breed`: Dog breed (3 specific breeds).  
   - `Age`: Age category (Puppy/Fully Grown).  
   - `Reason`: Reason for being taken to the shelter.  
   - `Returned`: Binary indicator for prior returns to the shelter.  

## 🛠️ **Tools and Techniques Used**
- **Programming Language:** R  
- **Statistical Techniques:** Hypothesis Testing (z-tests, t-tests), Confidence Intervals  
- **Data Visualization:** Histograms, QQ Plots  
- **Data Cleaning:** Removal of missing or irrelevant values  
- **Libraries Used:** `ggplot2`, `dplyr`, `stats`, `tidyr`

## 📈 **Key Analysis Steps**
1. **Data Cleaning:** Removed rows with invalid or missing data (`99999` or `NA`).  
2. **Data Exploration:** Generated numerical and graphical summaries for each breed.  
3. **Modeling and Estimation:** Proposed suitable distributions for rehoming times and estimated parameters.  
4. **Hypothesis Testing:** Calculated confidence intervals for mean rehoming times using **z-tests** and **t-tests**.  
5. **Comparative Analysis:** Compared mean rehoming times between breed pairs.  
6. **Insights and Discussion:** Identified trends, strengths, and limitations in the analysis.

## 📑 **Project Structure**
- **/report:** Final coursework report in PDF format (`MATH5741M_report.pdf`)  
- **README.md:** Project documentation (This file)  

## 🎓 **Learning Outcomes**
- Gained hands-on experience in **statistical analysis using R**.  
- Applied **hypothesis testing methods (z-tests, t-tests)** to real-world datasets.  
- Enhanced proficiency in **data visualization** techniques for insightful reporting.  
- Developed clear and concise reporting skills to effectively communicate findings.

## 🤝 **Acknowledgements**
- **University of Leeds, School of Mathematics**  
- **Dr. Stuart Barber** for guidance throughout the coursework.


🚀 Thank you for exploring this project! Feel free to contribute, share feedback, or reach out for further discussions. 🐕📊



