# PredictDeaths
Given the population of an area, the deaths history, and the 
predictions from my Cases Prediction project, I can accurately 
predict the number of CoVID deaths in the next week for that 
area. The files pertaining to this project is collected here.

The project predicts the number of deaths in the next week.
You can keep adding newer data To the dataset and the AI 
does quite an accurate job of predicting. At some point, then, 
One can see that the number of deaths have reduced significantly 
or even gone close to Zero, indicating that COVID-19 is under 
control. The AI can predict deaths for each county in CA. 
Initially, the project started off to do just that. Along the 
way, I realized I could just use the population of an area, 
it’s death history and integrate the cases predicted from my
CasesPrediction project to predict future deaths for that area, 
regardless of county info. It would, therefore, work for any 
area.

The dataset attached 'COVID_CA_DEATHS_RAW.csv' is a raw dataset 
and not available anywhere, I spent considerable effort collecting 
the weekly information from the CA COVID-19 dedicated website. 
This dataset consists of number of deaths from March - May 17th, 
2020 for each county in CA. Newer data can continue to be added 
to this dataset and my AI will correctly predict the number of 
deaths next week.

Since the dataset is raw, I have attached python code to do feature 
engineering as well as Create a new dataset which feeds the project 
as input. This new dataset has basic FE as well as an added feature 
'Cases Predicted',Which can be used. 

After deaths predictions are obtained, I Have generated another csv 
which contains the deaths predictions as an added feature. This file
Has population of an area, all the deaths history, as well as Cases 
Predicted for next week, And deaths predicted for next week. Data 
Visualization and comparisons graphs can be generated from this file.
