# Marketing analyiss project

Marketing analysis project

1. Problem Definition

First, we will conduct exploratory data analysis (EDA) and descriptive statistics. Then, we will try different models that can predict whether the person will apply for a deposit based on the data features. After optimizing the models, we will chose the best one and draw the ROC curve and AUC for the best performing model.

2. Data

The data is downloaded from https://archive.ics.uci.edu/ml/machine-learning-databases/00222/.

The dataset was donated in 2012, and is based on direct marketing campaigns via phone calls of a Portuguese banking institution. The classification goal of the dataset is to predict whether the client will subscript a term deposit. The dataset includes 45,211 entries.

3. Features

The data consists of the following features (attributes):

Age
Job
Marital : marital status
Education
Default: has credit in default?
Housing: has housing loan?
Loan: has personal loan?
Contact: contact communication type
Month: last contact month of year
Day: last contact day of the week
Duration: last contact duration, in seconds
Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

Campaign: number of contacts performed during this campaign and for this client
Pdays: number of days that passed by after the client was last contacted from a previous campaign
Note: 999 means client was not previously contacted

Previous: number of contacts performed before this campaign and for this client
Poutcome: outcome of the previous marketing campaign
Y - has the client subscribed a term deposit?
4. Approach

First, we are going to conduct EDA (Exploratory Data Analysis) and descriptive statistics (Problem 1 and Problem 2). Second, we are going construct a classification model to predict whether the client will subscribe to the term deposit, based on the dataset features (Problem 3). Then, we are going to evaluate our models, and choose the best-perforoming one. For the best model, we are going to plot a ROC curve and AUC (Problem 4).
