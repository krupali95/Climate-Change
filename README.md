# Climate-Change
Abstract: 
Introduction:
Climate, distinct from weather due to its emphasis on long-term trends over day-to-day fluctuations, is undergoing significant change. Climate change is a reality that demands immediate attention and effective strategies to mitigate its impact. The Intergovernmental Panel on Climate Change (IPCC) is made up of scientists from all across the world. These researchers discovered that the burning of fossil fuels, which emits carbon dioxide and other greenhouse gases into the atmosphere, is to blame for the average 1.1° Celsius (almost 2°F) increase in global surface air temperature between 1900 and 2020. While the numeric change might appear relatively modest, this warming trend is unparalleled when compared to temperature records spanning over two millennia [1] This dissertation delves into the intricate interplay between anthropogenic modifications and natural dynamics, utilizing observations and models to comprehend the historical, current, and future ramifications of climate change.[6] With a focus on escalating temperatures, the urgency of informed mitigation strategies becomes evident. 
Like other countries, the United Kingdom has to contend with the effects of climate change. Weather forecasting in the UK is a complex endeavor marked by its inherent difficulties. The unpredictable and chaotic nature of weather introduces a significant sensitivity to initial conditions, rendering accurate forecasts a challenging pursuit. The journey toward precision is constrained not only by model inaccuracies but also by the errors inherent in measuring initial conditions. [2]Given the scale of its impact, the field of weather forecasting has dedicated considerable human resources and computational power over the past few decades. The outcomes of these endeavors are noteworthy. The British Meteorological Service (2017) asserts that their current four-day forecasts are as accurate as one-day forecasts were three decades ago. This advancement in forecast accuracy aligns with the general trend that forecast horizons have expanded by about one day per decade [3]. These improvements in accuracy have profound implications, especially considering the extensive reliance on weather predictions across the UK. Bauer, Thorpe, and Brunet (2015) contend that the influence of weather forecasts rivals that of any other physical science. The consistent enhancement of forecast accuracy resonates with the growing dependence of individuals, businesses, and governments on reliable weather predictions, ultimately shaping and guiding numerous aspects of society in the UK.[3]
Amid this context, this study leverages machine learning techniques to predict climate data, focusing on maximum temperature trends in diverse UK regions, with Oxford as the epicenter. Utilizing an extensive dataset provided by Met Office UK, spanning from the mid-19th century to the present, the study endeavors to provide crucial insights into historical temperature trends and patterns. The ability to forecast future climate statistics assumes critical importance, aiding environmentalists and policymakers in adapting to and mitigating the effects of climate change.[4] With a concentrated emphasis on the UK, this research aims to harness the power of machine learning to forecast and comprehend future climate metrics, aligning with the broader effort to foster sustainability.
The research methodology encompasses a comprehensive analytical framework, incorporating advanced regression models such as the Random Forest Regressor and Linear Regression, complemented by the specialized time series forecasting technique known as Prophet, developed by Facebook. The Random Forest Regressor adeptly captures complex relationships within climate determinants, while Linear Regression offers insights into linear connections. The incorporation of the Prophet technique enhances temporal trend capture, considering holidays and recurring patterns that influence climate variables. These techniques synergistically enhance prediction accuracy and depth, enabling valuable insights across various sectors and decision-making processes.
Within this context, the study embarks on an experimental evaluation, delving into the prediction efficacy of the employed models. The research explores key elements of temperature change data for each region, laying the foundation for the ensuing analysis. The endeavor seeks not only to forecast climate metrics but also to enhance our understanding of climate dynamics, thus shaping a better-informed approach to climate adaptation and policy formulation. Through the exploration of historical temperature records and the application of cutting-edge modeling techniques, this research advances our comprehension of climate change's impact on the UK region and beyond, contributing to the collective efforts aimed at ensuring a sustainable and resilient future.

References:
1.	UCAR Center for Science Education. (n.d.). Predictions for the Future of Global Climate. Retrieved from https://scied.ucar.edu/learning-zone/climate-change-impacts/predictions-future-global-climate
2.	Stensrud, D. J., Brooks, H. E., Du, J., Tracton, M. S., & Rogers, E. (1999). Using ensembles for short-range forecasting. Monthly Weather Review, 127(4), 433-446.
3.	Nurmi, V., Perrels, A., Nurmi, P., Michaelides, S., Athanasatos, S., & Papadakis, M. (2012). Economic value of weather forecasts on transportation–Impacts of weather forecast quality developments to the economic effects of severe weather. Retrieved from https://ewent.vtt.fi/Deliverables%20D5%20and%20D6.pdf
4.	Met Office UK. (n.d.). Climate Change in the UK. Retrieved from https://www.metoffice.gov.uk/weather/climate-change/climate-change-in-the-uk
5.	World Bank. (n.d.). Climate Data Historical. Retrieved from https://climateknowledgeportal.worldbank.org/country/united-kingdom/climate-data-historical
6.	IPCC. (2021). Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Masson-Delmotte, V., et al. (eds.)]. Cambridge University Press. Retrieved from https://www.ipcc.ch/report/ar6/wg1/
7.	UK Met Office. (n.d.). Climate Data. Retrieved from https://www.metoffice.gov.uk/research/climate/maps-and-data/data/hadukp

LITERATURE REVIEW:

This section delves into the diverse landscape of climate forecasting techniques employing regressor and prophet methodologies:

The realm of weather forecasting research has witnessed a panorama of investigations into predictive models. Mathur et al. (2008) laid the foundation with a feature-based neural network, envisioning it as an alternative to conventional meteorological methods. In 2012, the utilization of backpropagation neural networks unlocked the potential to capture intricate nonlinear temperature relationships.[1] Troncoso et al. (2015) carved a path by employing innovative regression tree structures, culminating in accurate short-term wind speed forecasts. These studies collectively illuminate the exploration of avant-garde approaches in weather prediction, from neural networks unraveling intricate connections to specialized regression trees enhancing wind speed predictions.[2]

1.	Mathur S, Kumar A, Ch M (2008) A feature-based neural network model for weather forecasting. Int J Comput Intell
2.	Troncoso A, Salcedo-Sanz S, Casanova-Mateo C, Riquelme JC, Prieto L (2015) Local models-based regression trees for very short-term wind speed prediction. Renew Energy 81:589–598. https://doi.org/10.1016/j.renene.2015.03.071

Marzban, Leyton, and Colman (2007) embarked on an extensive analysis of cloud ceiling and visibility data across the Pacific Northwest from 2001 to 2005. Their focus was to prognosticate the likelihood of low or high cloud ceilings over a 6 to 12-hour forecast horizon. The exploration spanned 39 weather stations, revealing neural networks' superior predictive prowess over Model Output Statistics (MOS) and logistic regression, for stations with sufficient data. It's noteworthy that individual station results are depicted graphically, while comprehensive summary statistics remain absent [Reference: Provided source]. Notably, for six-hour predictions, neural networks outperformed MOS on 9 out of 14 stations, with a 64% success rate. For twelve-hour forecasts, neural networks outshone MOS on all 34 stations (100%), hinting that non-linear methods outshine linear ones when predicting non-linear trends manifesting as forecasting biases over extended intervals. These findings posit the dominance of non-linear techniques in day-ahead weather predictions, aligning with the present study's objectives.[3]

3.	Marzban, C., Leyton, S., & Colman, B. (2007). Ceiling and visibility forecasts via neural networks. Weather and forecasting, 22(3), 466-479.

In the realm of this research, temperature's pivotal role in indicating climate shifts and ecosystem dynamics is undeniable, with far-reaching impacts spanning agriculture, transportation, and more. Temperature forecasting emerges as a linchpin in predicting atmospheric conditions, driven by shifting parameters. The study delves into the realm of machine learning models — Ridge, Random Forest, Linear Regression, and Decision Tree — to herald temperature prediction. Evaluation grounded in RMSE scores showcases Decision Tree's preeminence (0.036), trailed by Random Forest (0.208), whereas Logistic Regression and Ridge register lower scores (0.759). The paramount importance of precise temperature prediction resonates across multifarious sectors, underlining the need for adept predictive methodologies.[4]

4.	Performance Evaluation of Machine Learning Models for Weather Forecasting | Institute of Electronics and Computer (iecscience.org)

In the vanguard of weather prediction, this study undertakes the classification of weather conditions into hot, cold, or rainy, propelled by machine learning algorithms. Decision Tree, Random Forest, and K-Nearest Neighbors (K-NN) are harnessed alongside Neural Networks, with accuracy being their common measure. Notably, the Random Forest algorithm towers in accuracy among the trio. However, the ambit of these algorithms, rooted in supervised learning, might not fully encompass diverse weather attributes or future periods. Subsequent work might enfold the exploration of additional attributes and algorithms such as Support Vector Machines, Naïve Bayes, and Artificial Neural Networks to widen the scope.[5]

5.	Forecasting Meteorological Analysis using Machine Learning Algorithms | IEEE Conference Publication | IEEE Xplore

This study amplifies the significance of precise weather and temperature prediction in everyday life and disaster readiness. Through Multi Linear Regression (MLR), Polynomial Regression (PR), and Support Vector Regression (SVR), the prediction of temperature changes is actualized. The study underscores the pivotal role of weather prediction in disaster management, showcasing comparable performance levels among MLR, PR, and SVR. Distinctiveness is unveiled through Mean Square Error (MSE), with PR triumphing, boasting an MSE of 0.275822 — marking a 67.5% reduction from MLR's 0.900937 and an 86.4% reduction from SVR's 2.022358. This study resonates with the paramount importance of accurate weather prediction in the realm of disaster management.[6]

6.	Temperature Prognosis Using Regression Techniques | IEEE Conference Publication | IEEE Xplore
 
 Amidst the escalating air temperatures and climate shifts attributed to Jakarta's urbanization-driven reduction in green spaces, this study unfurls. It crafts precise air temperature prediction models wielding Long Short-Term Memory (LSTM) and Prophet, tailor-made for stochastic air temperature data. LSTM captures short-term patterns (RMSE: 0.31-0.69 for 2-48 hours), while Prophet excels in protracted forecasts (RMSE: 0.80-0.89 for 72-168 hours). Amidst Jakarta's dense populace and limited green cover, these models surmount the less adaptive Numerical Weather Prediction. While LSTM, a sophisticated Recurrent Neural Network, emboldens long-term information retention, Prophet, creation of Facebook, amalgamates trends, seasons, and holidays.[7]

7.	Air Temperature Forecasting with Long Short-Term Memory and Prophet: A Case Study of Jakarta, Indonesia | IEEE Conference Publication | IEEE Xplore

Background:
In this section, we provide an in-depth exploration of the methodologies employed in this study, their alignment with the research problem, and the theoretical foundations that underpin their usage. The methodologies encompass Random Forest Regressor, Linear Regression, hyperparameter tuning, and the utilization of the Facebook Prophet library for time series forecasting.
Regression Method:
Regression analysis is a pivotal technique within the realm of data analysis, serving as a cornerstone for understanding relationships between variables and making predictions based on observed data. It is a versatile approach applicable across various domains, including economics, social sciences, healthcare, engineering, and weather forecasting [1].
For temperature prediction, the selection of these two methods, the Random Forest Regressor and Linear Regression, is guided by specific considerations that align with the nature of the data and the research objectives. The rationale for opting for these methods can be further elaborated as follows:
References:
Montgomery, D. C., Peck, E. A., & Vining, G. G. (2012).
**Random Forest Regressor:**
The choice of the Random Forest Regressor stems from its ability to handle complex relationships within data and effectively manage intricate patterns. Given the intricate and potentially non-linear relationships inherent in temperature data, the ensemble nature of this method allows it to capture and combine insights from numerous decision trees, mitigating the risk of overfitting. Moreover, the Random Forest Regressor's adaptability to diverse domains makes it a suitable candidate for predicting temperature patterns across various contexts, such as climate modeling, environmental monitoring, and more.
**References:**
1. NumPy Ninja. (n.d.). Regression Algorithm Part 6: Random Forest Regression Using R Language. [Link](https://www.numpyninja.com/post/regression-algorithm-part-6-random-forest-regression-using-r-language)
2. Serokell. (n.d.). Random Forest Classification. [Link](https://serokell.io/blog/random-forest-classification)
3. Medium. (n.d.). Random Forest Regression. [Link](https://levelup.gitconnected.com/random-forest-regression-209c0f354c84)
**Linear Regression:**
The inclusion of Linear Regression is warranted by its simplicity and interpretability, attributes that can be advantageous when analyzing temperature prediction. While Linear Regression assumes linear relationships, it provides valuable insights into the direction and magnitude of associations between variables. In cases where temperature changes exhibit a linear trend, Linear Regression can offer a clear and concise representation of this trend. Additionally, Linear Regression's computational efficiency facilitates quick model development, making it a valuable tool in temperature prediction scenarios.
**Reference:**
[1] WallStreetMojo. (n.d.). Linear Regression Examples. [Link](https://www.wallstreetmojo.com/linear-regression-examples/)
By combining the strengths of both methods, your research aims to harness the benefits of Random Forest Regressor's complexity handling and Linear Regression's straightforward interpretability to provide a comprehensive and accurate approach to temperature prediction. This tailored selection demonstrates a strategic approach to addressing the complexities of temperature forecasting while maintaining a practical and understandable framework.

Time Series Forecasting with Facebook Prophet: Beyond traditional regression techniques, this study extends to time series forecasting using the Facebook Prophet library. Time series data with temporal dependencies presents distinct challenges and opportunities.
Facebook Prophet: Facebook Prophet is a specialized tool designed for time series forecasting, suited to capture patterns in data displaying seasonality and trends. It's handling of missing data, outliers, and holidays makes it potent for meteorological predictions. Taylor, S. J., & Letham, B. (2017). Forecasting at scale. The American Statistician, 72(1), 37-45. https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1380080


Dataset: 
This study's analysis was derived from the Met Office's comprehensive repository of historic station data, available through the public domain at https://www.metoffice.gov.uk/research/climate/maps-and-data/historic-station-data. This repository has proven invaluable for examining transformations in the UK's climate over the span of more than 150 years. The central objective of this endeavor was to uncover patterns within climate variations, with a specific focus on temperature fluctuations, across distinct temporal intervals. Significantly, the dataset in question encompasses meticulously archived historical climate records, an extensive collection amassed by the Met Office. The analysis specifically narrowed its scope to the Oxford region, considering monthly temperature metrics in degrees Celsius. This dataset encompasses a range from 1853 to July 2023 and encompasses pivotal variables including 'year,' 'month,' 'tmax,' 'tmin,' 'af' (indicating air frost recorded in each month), 'rainfall,' and 'sun.' Notably, the 'sun' column, deemed irrelevant to the analysis due to its limited informational value, was prudently excluded from the subsequent analytical processes.

For the initial regression analysis, a series of meticulous transformations were performed during the preprocessing phase to ensure data consistency and facilitate subsequent analyses. The temporal variables 'year' and 'month' were converted into integer representations, while other pertinent columns underwent conversion to float values, enabling Exploratory Data Analysis (EDA) due to their original object data type. An additional column, 'tavg,' was introduced to enrich insights. This calculated the average of 'tmax' and 'tmin,' thereby providing a more visual representation and enhanced differentiability. To address the presence of missing data points, a pivotal step in this preparatory phase, the versatile 'fillna()' function was strategically employed. This judicious utilization revitalized the dataset, ensuring that it was robust and complete. A paramount consideration was the meticulous preservation of the temporal sequence, a feat accomplished through meticulous data-driven imputation techniques. By harmonizing these transformational steps, the data preparation phase established a sturdy foundation for ensuing analyses, seamlessly aligning with the overarching objectives of the study.

Transitioning to the time series modeling aspect, a distinctive approach emerged. This necessitated the inclusion of a 'day' column, as the input structure required by the Prophet framework invariably consists of two core columns: 'ds' (datestamp) and 'y' (numeric measurement for forecasting). Adhering to the expected Pandas format, 'ds' was converted into a datetime represenDateTimewherein the day component was consistently set to '01,' remaining congruent with the original dataset's month and year specifications. This coherent structure, exemplified as (01-01-1853, 01-02-1853, and so on), served as the bedrock for the subsequent phases of the modeling process.


Methodology :

 
DATA COLLECTION AND PREPROCESSING :
we delve into the implementation and evaluation of the Regressor model for temperature prediction using the provided dataset. The primary goal is to harness the predictive capabilities of the Regressor algorithm to forecast maximum temperatures based on historical data spanning over 150 years. The dataset contains temperature records alongside year, month, and various meteorological parameters.
The dataset consists of historical temperature records along with relevant features such as minimum temperature (tmin), rainfall, average temperature (tavg), and air frost (af). Let's denote the dataset as D, where each record is represented as a tuple (x_i, y_i), with x_i as the input feature vector and y_i as the target output. The feature vector x_i is composed of the features tmin, rainfall, tavg, and af, along with other temporal features. Mathematically:
D={(x1,y1),(x2,y2),…,(xn,yn)}									(1)
For the purpose of temperature prediction, the dataset is preprocessed to include the relevant features. Let
 	xi=[tmini,rainfalli,tavgi,afi] 									(2)				
represent the feature vector for record i. The target variable is denoted as  tmaxi, which represents the maximum temperature for record i.
To evaluate the model's performance, we split the dataset into training and testing subsets. Data from years before the split condition (2000) are used for training, while data from years after the split condition are reserved for testing. Specifically, records from 1853 to 2000 are used for training, and records from 2001 to the present are used for testing. This ensures that the model is evaluated on unseen data.
Several regression models are considered for comparison in temperature prediction. These models are implemented using the scikit-learn library in Python. For each model, we train it on the training data and evaluate its performance using the coefficient of determination (R-squared) metric on the test data.
Model Selection and Evaluation:

+--------------------+-------------+
| Model              |   R-squared |
+====================+=============+
| RF Regressor       |    0.980267 |
+--------------------+-------------+
| Linear Regression  |    0.982422 |
+--------------------+-------------+
| ElasticNet         |    0.966579 |
+--------------------+-------------+
| GBoost Regressor   |    0.976652 |
+--------------------+-------------+
| SVR                |    0.952136 |
+--------------------+-------------+
| CatBoost Regressor |    0.980684 |
+--------------------+-------------+
| Lasso Regression   |    0.966519 |
+--------------------+-------------+
| Ridge Regression   |    0.982417 |
+--------------------+-------------+
Table 1 the results of the model comparison based on 
the R-squared values for different regression techniques.

Table 1 presents the results of the model comparison based on the R-squared values for different regression techniques. The R-squared values indicate the proportion of variance in the dependent variable that is predictable from the independent variables. The models were evaluated using a comprehensive dataset and rigorous analysis. As shown in the table, the Linear Regression and Random Forest Regression models demonstrate the highest R-squared values, indicating their effectiveness in capturing the underlying relationships within the data. These results play a crucial role in guiding the selection of the most suitable regression model for accurate temperature predictions.

4.2 Random Forest Regressor Model:
we delve into the implementation and evaluation of the Random Forest Regressor model for temperature prediction using the provided dataset. The Random Forest Regressor, an ensemble learning algorithm, is particularly potent in capturing intricate relationships in data and delivering accurate predictions. It achieves this by combining the predictive power of multiple decision trees, a process that involves randomization during both tree construction and aggregation. in 2001, Breiman elucidates the algorithm's mechanics and highlights its effectiveness in improving prediction accuracy while mitigating overfitting. The idea of combining decision trees through aggregation to achieve enhanced predictive capabilities has since become a cornerstone of modern machine-learning practices.[ Breiman, L. (2001). Random Forests. Machine Learning, 45(1), 5-32.]
The Random Forest Regressor operates on the principle of ensemble learning, which is the practice of training multiple models and combining their predictions to achieve enhanced accuracy. In this context, the individual models are decision trees. A decision tree segments the input feature space into distinct regions, making decisions based on a series of feature-specific conditions. By integrating the outputs of multiple decision trees, the Random Forest Regressor addresses the shortcomings of a single decision tree and yields more robust predictions.
[Liaw, A., & Wiener, M. (2002). Classification and Regression by randomForest. R News, 2(3), 18-22.]
Randomized Search:
The Random Forest Regressor's performance is further optimized through hyperparameter tuning. Hyperparameters are adjustable settings that govern the behavior of the model. In this context, we employ the technique of Randomized Search, a method introduced by James Bergstra and Yoshua Bengio 
[Bergstra, J., & Bengio, Y. (2012). Random Search for Hyper-Parameter Optimization. Journal of Machine Learning Research, 13, 281-305. https://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a.pdf]
The prediction equation for a Random Forest Regressor is a bit more complex than that of a linear regression because it involves the aggregation of predictions from multiple decision trees. The general equation for predicting the target variable using a Random Forest Regressor can be written as follows:
y^=N1∑i=1Nfi(x)		(5)
According to temperture prediction related to project :
For your temperature prediction,
(tmin,tavg,rainfall,af)tmax^=N1∑i=1Nfi(tmin,tavg,rainfall,af)
Where:
•	^tmax^ is the predicted maximum temperature.
•	N is the number of trees in the Random Forest ensemble.
•	(tmin,tavg,rainfall,af)fi(tmin,tavg,rainfall,af) is the prediction made by the i-th decision tree based on the input features "tmin," "tavg," "rainfall," and "af."
This equation captures the essence of how the Random Forest Regressor combines the outputs of individual decision trees to arrive at a prediction for the target variable "tmax."
4.3 Linear Regression Model
In this section, we delve into the implementation and evaluation of the Linear Regression model for temperature prediction using the provided dataset. Linear Regression is a foundational machine learning algorithm that models the relationship between a dependent variable and one or more independent variables. In the context of temperature prediction, we utilize Linear Regression to establish a predictive model that estimates maximum temperatures based on relevant meteorological parameters.
the performance of the Linear Regression model through hyperparameter tuning using Randomized Search Cross-Validation. Hyperparameters play a crucial role in shaping the behavior of the model, and to find the best configuration, we perform a randomized search across a predefined grid of hyperparameters. The grid encompasses options such as including an intercept term, normalization, and feature copying. With a fixed random seed for reproducibility, we utilize the RandomizedSearchCV technique, creating an instance of Linear Regression, specifying the hyperparameter grid, and setting parameters for cross-validation folds and iterations. The model is then trained on the training data, and the best hyperparameters are identified.
Bergstra, J., & Bengio, Y. (2012). Random Search for Hyper-Parameter Optimization. Journal of Machine Learning Research, 13, 281-305. https://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a.pdf
equation (1), shown below is used for building the prediction model for regression analysis of weather data.
Y′=∝+β1X1+β2X2+⋯βnXn         (1)

The Linear Regression model aims to predict the maximum temperature (tmax) based on selected input features including minimum temperature (tmin), average temperature (tavg), rainfall, and growing degree days (af). The model formulates predictions by establishing a linear equation that relates the input features to the target variable. Mathematically, the prediction equation can be represented as follows:
tmax = α + β1 * tmin + β2 * tavg + β3 * rainfall + β4 * af
Where:
•	tmax is the predicted maximum temperature.
•	tmin, tavg, rainfall, and af are the input features.
•	α represents the intercept of the linear equation.
•	β1, β2, β3, and β4 are the coefficients associated with each input feature.
4.4 Prophet model:
the equation that defines the Prophet model for time series forecasting in the context of your project. Which is developed by Facebook in 2017 [B. Vishwas and A. Patel, Hands-on Time Series Analysis with Python., Springer, 2020] The equation for the Prophet model is as follows:
y(t)=g(t)+s(t)+h(t)+εt
Where:
•	y(t) represents the observed value at time t.
•	g(t) is the trend component that captures the overall direction of the data over time.
•	s(t) is the seasonal component that accounts for periodic patterns in the data.
•	h(t) is the holiday component that captures irregular events and holidays.
•	εt represents the error term that the model cannot account for.
The equation outlines how the observed value at a specific time t is composed of the trend, seasonality, holiday effects, and the residual error.
Additionally, for each of the components:
•	g(t) is described by a specific model equation that considers growth rate (k), offset (m), and adjustment (x) parameters.
•	s(t) is a sum of trigonometric terms that capture seasonal patterns with period (P).
Overall, the Prophet model decomposes the time series data into these components to make accurate forecasts by considering trends, seasonal patterns, and holiday effects. This modeling approach is particularly useful when dealing with data affected by varying factors such as seasons, trends, outliers, and holidays.
