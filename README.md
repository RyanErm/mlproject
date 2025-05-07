# Impacts of COVID and Other Large-Scale Phenomenons on Crime and Predictive Models
## DS 3021 Final Project:
by: Ryan Ermovick, Carissa Chen, Iliana Vasslides, Yuthi Madireddy, Kayla Kim

## Abstract

This study focuses on analyzing how large-scale national or global phenomena can affect the accuracy and method of representing statistical data and predicting results using machine learning models. While there have been many global societal phenomena over the decades, the most recent widely influential event, COVID-19, was chosen to compare and analyze the effects on calculations and predictions using machine learning models. To explore this, crime data was compiled through different sources, including the FBI, containing murders throughout the United States from 1976 to 2023. For this analysis question, the year range was narrowed to start from 2016. It contained data about what state and city the crime took place in, what the data source was, when it happened, the nature of the homicide, including the situation, weapon & victim count, victim’s age, race, sex, and ethnicity, as well as the offender’s age, sex, and race. 

Using this data set, a decision tree was created using factors of year, offender age, month, state, offender race, and situation to predict the victim’s race for murder and non-negligent manslaughter. After the model was trained, it would predict the victim's race. Several comparisons were made, comparing white vs. Black victims, Asian vs. White victims, Asian vs. Black victims, and Asian vs. Native American and Alaskan Native victims. The decision tree made the most incorrect predictions when compared to White victims, no matter which combination, likely because a large proportion of victims are White among all data observations. The dataset for both pre- and post-COVID was split into training and testing datasets. For the prediction, both decision tree models were tested for accuracy on the post-COVID testing data. 

Another set of graphs were created comparing COVID-19 cases with the crime data set, starting from 2020-2023, filtering for crimes against Asian individuals. The results only had data in California, Arizona, Alaska, Alabama, and Arkansas. Throughout these five states, California seemed to have some clear trends in cases and crimes against Asians. Specifically, when there was a spike in COVID-19 cases, there would usually be a spike in crimes against Asians 1-2 months following. These factors may be correlated with each other, but without more testing, it is not possible to state as such.


## Changelog

Changes were made from the Original methods plan. It was decided to test the accuracy of each model on the post-COVID test dataset set, and then compare these results to determine which model was better. Determining which model performed better gave useful insight onto when data should be implemented into models following large-scale global phenomena
