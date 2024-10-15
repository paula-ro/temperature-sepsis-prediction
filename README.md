# Using temperature data to predict late-onset sepsis in preterm infants
By Paula Romero Jiménez

## Project Information
This repository contains the code developed for my master’s thesis in **Applied Data Science** at the **University Medical Center (UMC) Utrecht**. The project investigates the potential of using machine learning to detect **late-onset sepsis (LOS)** in preterm infants through the analysis of continuous temperature monitoring data.

The study primarily focuses on **temperature variability** as a key predictive feature. Specifically, it evaluates the **mean temperature difference** and **standard deviation** of temperature changes over time to assess LOS risk. Patient data was matched by gestational age, time of birth, and gender to isolate the predictive power of temperature. A **logistic regression model** was then used to quantify the risk of LOS.

The dataset utilized in this study includes temperature data from preterm infants admitted to the neonatal intensive care unit (NICU) at **Wilhelmina Children's Hospital** between **April 2008 and May 2019**. Due to privacy restrictions, the dataset cannot be shared. However, the machine learning pipeline, including all data preprocessing, feature engineering, and model training steps, is provided in the Jupyter notebook within this repository.

This project was conducted under the supervision of researchers at **UMC Utrecht** and aims to contribute to the ongoing efforts to improve early sepsis detection in neonatal care settings.
