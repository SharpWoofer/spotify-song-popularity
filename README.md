![image](https://user-images.githubusercontent.com/127273523/233362488-c313a575-baef-447d-ae40-7f178541c62c.png)

### <p align="center"> Spotify songs analysis Mini-Project for SC1015 - Introduction to Data Science and Artificial Intelligence </p>
### <p align="center"> Full Notebook: [Deepnote](https://deepnote.com/@sharpwoofer/Spotify-Song-fbb651de-0180-4974-bf12-6b77f183dd37)  | [Github Pages](https://sharpwoofer.github.io/spotify-song-popularity/) | [Presentation slides](https://www.canva.com/design/DAFfARgqvcs/cMUSk1pxaLH1cBAjkfyZ4w/view?utm_content=DAFfARgqvcs&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)</p>

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on songs from The Spotify Dataset. We have organized our notebook according to the following sections:
- Data preparation/Cleaning
- EDA/Data visualization
- Machine Learning Techniques(Multiple Linear Regression and Random Forest)
- Data driven Insights/Conclusion

## Problem Definition

Are we able to predict the popularity of a song based on its attributes? Which model would be the best to predict it?

## Models Used
- Multiple Linear Regression
- Random Forest

## Conclusion
- Duration has little to no correlation with popularity
- Acousticness is the strongest predictor for a song’s popularity
- Removing outliers did help to improve the accuracy of our MLR(Multiple Linear Regression) model but did not help with the Random Forest. This   helped us understand that Random Forest is indeed robust to outliers
- Random Forest performed much better than the MLR in predicting a song’s popularity
- We found that we can indeed predict a song’s popularity based on its attributes with an acceptable amount of accuracy

## What did we learn from this project?
- How to identify and remove outliers from datasets such that accuracy of models is improved
- How to use the Multiple Linear Regression and Random Forest models
- The Random Forest model is robust to outliers
- How to use GitHub to collaborate 
- The concept of n estimators in relation to the Random Forest model

## References
- https://datascience.fm/fun-analysis-of-spotify-dataset-to-gain-insights-on-music-industry/
- https://medium.com/machine-learning-with-python/multiple-linear-regression-implementation-in-python-2de9b303fc0c
- https://www.scribbr.com/statistics/multiple-linear-regression/#:~:text=What%20is%20multiple%20linear%20regression,variables%20using%20a%20straight%20line.
