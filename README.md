# Code of the paper: Three-dimensional modelling using spatial regression machine learning and hydrogeological basement VES

https://doi.org/10.1016/j.cageo.2021.104907
![image](https://github.com/MendoVeirana/ML-spatial-regression-testing/assets/69166739/31c346a2-11ad-42e7-b214-002680134676)

Abstract:
In the last decade, machine learning algorithms have demonstrated their superior performance in spatial interpolation of environmental properties compared to classical interpolation models. In particular, the random forest (RF) ensemble model has provided the best fit. In different artificial intelligence applications, the extremely random forest (ERF) algorithm has outperformed several machine learning methods, including RF. In this paper, we compare the performance of support vector machines (SVM), simple trees (ST), RF and ERF on a spatial regression problem presented in geophysics. In a sedimentary basin in Argentina, the depth of the hydrogeologic basement was determined using a vertical electrical sounding (VES). The coordinates of the survey are not gridded but almost aligned. Our goal is to find the best algorithm to perform the task of spatial regression of basement depths, as well as to find out why some algorithms perform better than others for this task. To the best of our knowledge, we report here the first spatial regression application of the novel ERF algorithm, which predicted - even better than RF - values for which it had not been trained with an average R2 score of 97.6%. This allowed us to obtain a satisfactory generalization of the VES depths in the form of a three-dimensional representation of the basement. The ERF algorithm also outperformed RF in terms of computation time and smoothness of the generated surface. The primary importance of the results reported here lies in the relative independence offered by this technique, considering the area of application and coordinate gridding. Finally, the nature of the method by which the depths are obtained is also independent, as these can be derived not only from the VES technique, but also from borehole data or from different geophysical inversions.
