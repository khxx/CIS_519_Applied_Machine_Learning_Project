# CIS_519_Applied_Machine_Learning_Project
##              Finding Your Mrs/Mr.Right with Machine Learning

### For this project, we study the problem of predicting tinder swipes using historical behavior, which is important for providing tinder users with a more personalized and comfortable user experience and studying the seriousness of online dating by looking into factors that influence the swipes. The most relevant work to our project is Charles F. Jekel, and Raphael T. Haftka, “Classifying Online Dating Profiles on Tinder using FaceNet Facial Embeddings”. https://github.com/cjekel/tindetheus. 

### Our primary target contribution is to enhance data that is used to train the predictive model. Second, we would like to improve the model using more suitable hyperparameters. We have combined image data with metadata (bio, age, distance,  occupation, education, etc) for better modeling. In addition, we extracted the image embeddings with different aggregation methods and facial extraction models. Furthermore, we performed gridsearch on the hyperparameters to increase the AUC of testing results. A weighted logistic model using minimum or maximum of 512 embeddings of images per profile along with user biographies output the best result with AUC of 0.96. Impressively, even by taking 5% of data as a training set, the model has a high AUC of 0.91.

