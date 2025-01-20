# MCM-2024-Problem C: Momentum in Tennis


In this study, we developed a model aimed at tracking the flow of a match point by point,
identifying which player is performing better at any given moment, and quantifying the degree
of difference in their performance. By utilizing advanced machine learning models like XGBoost, we quantified
momentum based on key variables selected through meticulous feature engineering. This approach
provided a structured framework to measure and analyze momentum shifts during a match, offering
valuable insights into player dynamics.


TODO:

- [x] Data-processing
- [x] Build Momentum model and Using XGBoot to Predict Momentum  
- [x] Build model for Predict the outcome of each point 
- [x] Apply Momentum to Model 2 and give insights



```text
.
Momentum-in-Sport
├── Code
│   ├── Model_1_for_momentum.ipynb
│   ├── Model_2_for_Prediction_Outcome.ipynb
│   ├── Pre_processing_for_model_1.ipynb
│   └── Pre_processing_for_model_2.ipynb
├── Dataset
│   ├── data_dictionary.csv
│   ├── Wimbledon_featured_matches.csv
├── final_report
└── MCM-2024-Problem-C.pdf

```

**Process Execution**  

1. `Data-Processing`: Prepare and process different datasets for each model  
   1. Pre_processing_for_model_1.ipynb  
   2. Pre_processing_for_model_2.ipynb  
   3. Wimbledon_featured_matches.csv: The original and only dataset  
   4. data_dictionary.csv 

2. `Build and Train Each Model`  
   1. Model_1_for_momentum.ipynb  
   2. Model_2_for_Prediction_Outcome.ipynb  

3. `final_report`: Write the report  
