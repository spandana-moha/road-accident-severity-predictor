# Road Accident Severity Predictor

This project applies machine learning to predict the severity of road traffic accidents (Slight, Serious, Fatal) using a real-world dataset from the UK.  
By analyzing environmental, temporal, and vehicular features, the model helps identify factors contributing to accident severity and provides insights for improving road safety.

---

## Project Objective
To build a predictive model that classifies the severity of road accidents based on historical accident data and contributing factors such as speed limit, weather, lighting, and road surface conditions.

---

## Technologies & Tools
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Model Used:** Random Forest Classifier

---

## Results
- Achieved **~85–89% accuracy** on test data.  
- Identified **lighting conditions** and **weather** as critical predictors of accident severity.  
- Visualizations: Confusion Matrix, Severity Distribution, Feature Importance, and Correlation Heatmaps.

## Repository Structure
📂 Road-Accident-Severity-Predictor

 ┣ 📜 README.md        ← clean project overview
 
 ┣ 📜 Road_Accident_Severity_Predictor.ipynb  ← main code
 
 ┣ 📜 Accident.csv      ← dataset 
 
 ┣ 📜 Report.pdf        ← final project report

## Future Work
- Handle class imbalance with SMOTE / class weights.
- Try Gradient Boosting and Deep Learning models.
- Deploy as a web dashboard for real-time predictions.

## References
- K. Kumar and A. Toshniwal, "A data mining framework to analyze road accident data," Journal of Big Data, vol. 2, no. 1, pp. 1-15, 2015.
- P. Chien, J. Hsu and C. H. Huang, "A road traffic accident severity prediction model using machine learning," IEEE Access, vol. 7, pp. 64410-64418, 2019.
- S. Sharma, S. K. Goyal, and A. K. Pandey, "Accident severity prediction using ensemble techniques," Procedia Computer Science, vol. 132, pp. 895–902, 2018.
- A. Baharudin and M. Al Mamun, "Analyzing accident data using machine learning approaches," Transportation Research Procedia, vol. 45, pp. 74-81, 2020.
- T. Yoon, K. Cho and J. Park, "Machine learning-based traffic accident severity analysis using high-dimensional data," IEEE Transactions on Intelligent Transportation Systems, vol. 22, no. 7, pp. 4085-4095, 2021.
