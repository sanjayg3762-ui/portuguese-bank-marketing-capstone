# Portuguese Bank Marketing Capstone

This project analyzes the Portuguese Bank Marketing campaign dataset and compares models that predict whether a customer subscribes to a term deposit. The notebook includes data cleaning, exploratory analysis, model evaluation, threshold comparison, feature importance, marketing recommendations, and limitations.

## Dataset

Download the course dataset from the [PRCP-1000 Portuguese Bank Marketing ZIP](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1000-ProtugeseBank.zip). Extract it and place `bank-additional-full.csv` beside the notebook or in `Data/bank-additional/`. The notebook does not include the dataset file.

## Run the notebook

Install Python with Jupyter, pandas, scikit-learn, and matplotlib. Open `Portuguese_Bank_Marketing_Capstone.ipynb` and run all cells from top to bottom.

The notebook excludes `duration` from the predictive models because it is only known after the call. Results are development findings on historical 2008–2010 data and are not evidence of causal effects or current production performance.
