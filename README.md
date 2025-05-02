# Gaining an Advantage in the NFL
## Project Description
This project analyzes play-by-play data from the NFL to see if we're able to build a model that predicts the offensive play call result based on the game situation (downs, distance, time remaining) and offensive and defensive personnel.

<b>Feature Variables</b>
- Yardline
- Downs
- Distance
- Time remaining in quarter, half, game
- Quarter
- Score Differential
- Offensive Formation/Personnel
- Defensive Formation

<b>Target Variable</b>
The play call result is either a pass or run.
- Pass: Short, Medium, or Long AND Left, Middle, or Right
- Rush: Left or Right AND End, Tackle, Guard 

To try and predict the play call using the features, we used a Random Forest Classifier and a Neural Network.

## File Breakdown
- prelim_data_analysis.ipynb: Contains the Preliminary Data Analysis, including meaningful graphs and statistical significance tests
- random_forest_classifier_model.ipynb: Contains Random Forest Classifier
- neural_network_model.ipynb
- ./output/: Miscellaneous output files for reference 
- prev_model.ipynb: Previous model idea - irrelevant for current product

## Set-Up Instructions
- Use Python 3.12.3 Interpretter/Environment
- pip install -r requirements.txt

## Questions?
Contact Andrew Bonsted (abonsted@vols.utk.edu) or Bryce Richards (bricha37@vols.utk.edu) if you have any further questions.