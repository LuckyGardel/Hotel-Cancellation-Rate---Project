# PREDICTING AND REDUCING THE IMPACT OF HOTEL RESERVATIONS CANCELLATION RATE-

The purpose of this project is to analyze customer behavior when performing hotel reservations and cancellations in order to minimize the negative impact of these cancellations in the different properties.  

#### BACKGROUND AND DATA

Background:

There are millions of Hotel cancellations in different countries every year, this is a huge concern for Hotel owners that are seing how their revenue is negatively impacted by this issue.  

I am going to try to modify and adapt our cancellation policies thanks to Data Analysis to correctly address this matter. For this we are going to: 

        Analayze different different parameters to identify useful trends. 
        Build Machine learning models to predict Reservations Cancellation rate. 
        
Data: 

I have chosen a dataset of two Hotels located in Portugal. One is a Resort Hotel located in Algarve (Typical Holiday destination for Leisure) and the other one is a city Hotel located in Lisbon (More Corporate Travel). 
We have more than 100.000 reservations from july 2015 to August 2017 to perform the analysis. 

The originial dataset can be found here: https://www.kaggle.com/datasets/mathsian/hotel-bookings

Extra information about the dataset can be found here: https://www.researchgate.net/publication/329286343_Hotel_booking_demand_datasets

#### DATA PROCESSING

. Data Loading. 

. Standarizing Headers, Checking info and Dtypes.

. Checking and Dropping duplicates.

. Checking and Dealing with NaN values.

. Splitting between Numerical and Categorical Variables to perform Deeper cleaning.

. Concatenating cleaned data as a new Dataset. 

. Performing Hypothesis Testing (Hypothesis Test of proportions).

. Saving the cleaned Data to export to Tableau and create connection with SQL. 

. Building different Machine Learning Models. 

. Plotting different graphs to obtain other useful information.

. Analyze Results and extract Conclusions.

#### CONCLUSIONS

. Both hotels have more guests and cancellation % during high seasons. The peak season for the City Hotel goes from March to May and for the Resort Hotel from June to August. Both hotels lower season is Winter. We should apply more restrictive cancellation policies during high seasons. 

. The percentage of cancellations is higher in the City Hotel than in the Resort. The city Hotel should be the main focus, but if we can reduce the Resort cancellation % applying this policies, this would be beneficial for the property as well. 

. The company should focus on growing other market segments rather than Online TA. Direct and Corporate segments have a much lower cancellation rate than Online TA. Focusing the Sales dep. effort to attract more corporate negotiated rates and performing marketing campaigns and special offers to attract clients to our direct website would result in a lower cancellation rate as well. 

. The longer the stay is, the higher is the probability of a cancellation. This trend is more clear in the City Hotel. Apply more restrictive cancellation policies for reservations staying longer than a week. 

. The longer the lead time is, the higher is the probability of a cancellation. Again the trend is steeper in the City Hotel. Here we can send reminding emails to our clients so they dont forget about their stay with us. Accompany this with more restrictive cancellation policies for reservations made with more than a month in advance.  

. We have obtained an accurate Machine Learning Model available in order to perform predictions. 
        
        # Logistic Regression test scores: 0.7423891757165747

                        # precision-->  0.5199477731031481
                        # recall-->  0.7764298093587522
                        # f1-->  0.6228169258840908

                # Logistic Regression confusion matrix

                        # [8926, 3309]
                        # [1032, 3584]

        # MLPClassifier test scores: 0.81087175835262

                        # precision-->  0.6278861643100053
                        # recall-->  0.7599653379549394
                        # f1-->  0.687640889934333

                # MLPClassifier confusion matrix

                        # [10156,  2079]
                        # [ 1108,  3508]
