# Pore Pressure Prediction In Northern Carnarvon Basin

This project employs machine learning models to predict pore pressure in the Northern Carnarvon Basin. Utilizing advanced computational methods and comprehensive geological data, it aims to enhance precision for informed decision-making in drilling and reservoir management within the region's petroleum industry.

## Executive Summary
The main focus of this study is to evaluate machine learning models in predicting pore pressure values, which is a crucial aspect of drilling operations. The goal is to create strong machine-learning models by leveraging drilling data, with a specific emphasis on target pore pressure. Once developed, these models will play a pivotal role in predicting pore pressure with high accuracy. The ultimate aim is to implement these models as valuable tools to guide and optimize future drilling activities, thereby enhancing operational efficiency.

## Methodology
The subsurface pressure regime can be divided into distinct categories that depend on the prevailing conditions. Each classification has significant implications for the drilling process and the production of natural resources. Terzaghi (1943) identified three primary types of subsurface pressure: overburden pressure, pore pressure, and effective pressure. Pore pressure, which is a critical parameter, represents the difference between overburden pressure and effective pressure. This pressure is created by fluids, such as oil, gas, and water, that are present within the gaps between rock formations.
![image](https://csegrecorder.com/assets/images/articles/2006-04-velocity-fig01.jpg)

For this research, the methodology used to calculate pore pressure follows the principles outlined by the Eaton method, which is a recognized and validated approach in the field.

## Data Collection
<a href="https://wapims.dmp.wa.gov.au/wapims" target="_blank">
<img src="https://catalogue.data.wa.gov.au/uploads/group/2020-10-07-052505.314296DMIRS-datawa.svg" width="260" height="200" border="10" />
</a>

The study utilized a dataset from the open-access repository provided by the **Government of Western Australia Department of Mines, Industry Regulation, and Safety**.

![image](https://www.ga.gov.au/__data/assets/image/0019/87040/Fig13_PP-2973-40_Rankin_Regional_2020.png)

The objective of this project is to explore the Northern Carnarvon Basin. The accompanying image highlights the research area's geographical boundaries, with a particular focus on the Rankin Platform. The study's primary points of interest are the WILCOX-1 well, WILCOX-2 well, and GOODWYN-6, all of which are critical areas of investigation in this comprehensive study.

<a href="https://www.ga.gov.au/scientific-topics/energy/province-sedimentary-basin-geology/petroleum/acreagerelease/northerncarnarvon" target="_blank">
<img src="https://www.ga.gov.au/__data/assets/image/0006/109869/PP-3978-9_Strat_Rankin.jpg" width="560" height="1000" border="10" />
</a>

In examining the GOODWYN-6 and WILCOX wells' stratigraphy, geological period congruence exists, but ages differ.

## Pre-processing
Extensive drilling data was collected from WILCOX-1, WILCOX-2, and GOODWYN-6 wells to commence the research. Shale and non-shale zones were identified to conduct a precise analysis of the Normal Compaction Trend (NCT), which is crucial for assessing pressure regimes. The overburden pressure was determined by density logs, and the Eaton equation was used to predict pore pressure. The use of artificial intelligence, implemented in Python on Google Collaboratory, significantly accelerated the predictions.

Before starting the modeling, exploratory data analysis (EDA) and data pre-processing were done to ensure data integrity. Three supervised machine learning models, namely Random Forest Regressor, MLP Regressor, and XGBoost Regressor, were designed and optimized through hyperparameter tuning. The performance of these models was evaluated using R2 score and MAPE metrics. The computational efficiency of the models was also assessed through runtime evaluations.

The research culminated in a blind test using the GOODWYN-6 dataset, which confirmed the models' predictive ability. The streamlined approach of integrating field data, advanced modeling techniques, and machine learning highlights the efficiency of predicting pore pressure in drilling operations.

## Conclusion
*  The prediction analysis involves training and testing on two wells, WILCOX-1 and WILCOX-2, with GOODWYN-6 designated for blind testing.
*  Three models, namely Multi-Layer Perceptron, Random Forest, and XGBoost were used for prediction.
*  Before tuning hyperparameters, Random Forest achieved superior performance with an R2 score of 0.9997.
*  After hyperparameter tuning, the Multi-Layer Perceptron was identified as the optimal model, achieving an improved R2 score of 0.9998.
*  During the blind test of the GOODWYN-6 well, the Multi-Layer Perceptron achieved an exceptional R2 score of 0.9999, demonstrating its superior predictive capability.


# Contact Me
For further inquiries or to initiate a discussion, please feel free to contact me via <a href="mailto:salmanarkan020@gmail.com"><span class="label">email</span></a>. Additionally, you can visit my professional website (click the image/gif).

<a href="https://salmanarkan.github.io/" target="_blank">
<img src="https://github.com/SalmanArkan/SalmanArkan/blob/main/GithubBanner.gif" width="400" height="200" border="10" />
</a>
