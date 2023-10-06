# Chance-of-Admission-Prediction
## Overview

This repository contains code and data for a linear regression model to predict the chances of admission for prospective students. The model uses various features such as GRE Score, TOEFL Score, University Rating, SOP (Statement of Purpose), LOR (Letter of Recommendation), CGPA (Cumulative Grade Point Average), and Research experience to make predictions.

## Dataset

The dataset used for training and testing the model includes the following columns:

- `Serial No`: A unique identifier for each data point (not used in modeling).
- `GRE Score`: The applicant's GRE (Graduate Record Examination) score.
- `TOEFL Score`: The applicant's TOEFL (Test of English as a Foreign Language) score.
- `University Rating`: The rating associated with the university the applicant is applying to.
- `SOP`: The applicant's Statement of Purpose.
- `LOR`: The applicant's Letter of Recommendation.
- `CGPA`: The applicant's Cumulative Grade Point Average.
- `Research`: A binary variable indicating whether the applicant has research experience (1 for yes, 0 for no).
- `Chance of Admit`: The target variable representing the chances of admission.
