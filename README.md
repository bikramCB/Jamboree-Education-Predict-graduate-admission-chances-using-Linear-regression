# Jamboree-Education:Predict graduate admission chances using Linear regression

## Business Model:
Student register in Jamboree education website to see their admission chances to IVY League university. So their should be some registration fees. This way their business run.

## Problem statement:
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

## Data:
Serial No. (Unique row ID)
GRE Scores (out of 340)
TOEFL Scores (out of 120)
University Rating (out of 5)
Statement of Purpose and Letter of Recommendation Strength (out of 5)
Undergraduate GPA (out of 10)
Research Experience (either 0 or 1)
Chance of Admit (ranging from 0 to 1)

## Tech Used:
Linear Regression

## Tools Used:
Numpy, Pandas, matplotlib, seaborn, Scikit_Learn

## Solutions :
1 .Approx 600 students data were collected from Jamboree website.
2. Perform EDA to see distribution of data of every feature and eliminate highly corelated features using Statmodels and VIF score.
3.Implemented Linear regression With R2 score 0.83 and RMSE of 0.068
4. from Q-Q plot we understand model correctly predicted high probability students with higher accuracy but failed to predict lower probability students. SO we need to feed more data to model with lower probavility.
