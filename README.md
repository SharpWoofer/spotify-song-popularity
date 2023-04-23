![image](https://user-images.githubusercontent.com/127273523/233362488-c313a575-baef-447d-ae40-7f178541c62c.png)

### <p align="center"> Spotify songs analysis Mini-Project for SC1015 - Introduction to Data Science and Artificial Intelligence </p>
### <p align="center"> Full Notebook: [Deepnote](https://deepnote.com/@sharpwoofer/Spotify-Song-fbb651de-0180-4974-bf12-6b77f183dd37)  | [Github Pages](https://sharpwoofer.github.io/spotify-song-popularity/) | [Presentation Video](https://entuedu-my.sharepoint.com/:v:/g/personal/hcai005_e_ntu_edu_sg/EYEalbfJ6FxPre_yhef-dBQBhB8Lg9ouVjxHUhOA14cLaQ?e=pVZMYo)</p>

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on songs from The Spotify Dataset. We have organized our notebook according to the following sections:
- Data preparation/Cleaning
- EDA/Data visualization
- Machine Learning Techniques(Multiple Linear Regression and Random Forest)
- Data driven Insights/Conclusion

## Problem Definition

Are we able to predict the popularity of a song based on its attributes? Which model would be the best to predict it?

## Models Used
- Multiple Linear Regression (MLR)
- Random Forest

## Conclusion
- Acousticness is the strongest predictor for a song’s popularity using Random Forests
- Duration has little to no correlation with popularity using Multiple Linear Regression Model
- Removing outliers did help to improve the accuracy of our Multiple Linear Regression model but did not help with the Random Forest. This helped us understand that Random Forest is indeed robust to outliers
- Random Forest performed much better than the MLR in predicting a song’s popularity when the trees are generated in high quantities and depths
- We found that we can indeed predict a song’s popularity based on its attributes with an acceptable amount of accuracy

## What did we learn from this project?
- How to identify and remove outliers from datasets such that accuracy of models is improved
- How to use the Multiple Linear Regression and Random Forest models
- The Random Forest model is robust to outliers
- The concept of n estimators, random state and feature importances for each model
- R^2 is used to tell how good a regression model fits whereas accuracy score is used to tell how good a classifier model fits
- How to use GitHub to collaborate 

## Acknowlegements & Contributors

Special thanks to our TA (Ju Ce) for his guidance throughout the course
- [@SharpWoofer](https://github.com/SharpWoofer)
- [@AaronnF](https://github.com/AaronnF)
- [@Advika07](https://github.com/Advika07)

## References
- [Kaggle Dataset](https://www.kaggle.com/datasets/lehaknarnauli/spotify-datasets?ref=datascience.fm)
- https://datascience.fm/fun-analysis-of-spotify-dataset-to-gain-insights-on-music-industry/
- https://medium.com/machine-learning-with-python/multiple-linear-regression-implementation-in-python-2de9b303fc0c
- https://www.investopedia.com/terms/m/mlr.asp
- https://www.youtube.com/watch?v=yN7ypxC7838
- https://plotly.com/python/subplots/
- https://www.scribbr.com/statistics/multiple-linear-regression/#:~:text=What%20is%20multiple%20linear%20regression,variables%20using%20a%20straight%20line.
- https://stackabuse.com/random-forest-algorithm-with-python-and-scikit-learn/
- https://tfr.news/opinionarticles/predicting-which-song-will-be-popular-can-we-do-that
- https://www.kaggle.com/code/vatsalmavani/music-recommendation-system-using-spotify-dataset
- https://youtu.be/LQlTO5uhCQ8
- https://pypi.org/project/kaleido/
- https://youtu.be/ibSQmC3h85A
- https://community.plotly.com/t/how-to-display-plotly-graph-on-github-pages/44398/4
