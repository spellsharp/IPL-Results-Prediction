# IPL Results Prediction
## Description
IPL-Results-Prediction is a basic machine learning project that is made using the basics of `pandas`, `numpy`, `seaborn` and different in-built functions and model classes from `scikit-learn`. It has two individual components: Match Outcome Prediction and Final Score Prediction.

Match Outcome Prediction is a classification problem that predicts the winning chance of one of the teams, whereas Final Score Prediction is a regression problem that calculate the final score of a team. Take a look at the jupyter notebooks for better understanding! 

**DISCLAIMER**
This is an undergrad college semester project and was made public for educational purposes, specifically targeted at other undergrad college students who are just starting out in Machine Learning. There are several improvements that can be made to these notebooks. Feel free to make an issue if needed. You may also look at the project report, although I would not recommend it ;)

## Dataset links
### Match Outcome Prediction

[Dataset1](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020?select=matches.csv)

[Dataset2]()

[Dataset3](https://www.kaggle.com/datasets/vora1011/ipl-2008-to-2021-all-match-dataset?select=IPL_Matches_2008_2022.csv)

### Final Score Prediction

[Dataset](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020?select=deliveries.csv)

## Future Scope
For those interested to develop on top of this project, do consider this: Iterate through the entire dataset that's used for Final Score Prediction and pass each match teams and other details through the Match Outcome Prediction to get a seeding of sorts to get more accurate final score prediction. The other way may work as well, although it may not be as easy, due to dataset constraints.