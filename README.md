# Chennai-Housing-Sales-Price
Chennai-Housing-Price-Prediction
Business Task
To analyse Chennai Housing Price Dataset and predict the cost price of various houses.

Business Objective
What factors contribute to a costly selling price.
Which area in chennai is the cheapest to buy a house.
Build a Machine Learning model to predict the housing prices.
Dataset Used
Chennai Housing Price dataset contains the following attribute:-

PRT_ID : object
AREA 17: object
INT_SQFT: int64
DIST_MAINROAD: int64
N_BEDROOM: float64
N_BATHROOM: float64
N_ROOM: int64
SALE_COND: object
PARK_FACIL: object
BUILDTYPE: object
UTILITY_AVAIL: object
STREET: object
MZZONE: object
QS_ROOMS: float64
QS_BATHROOM: float64
QS_BEDROOM: float64
QS_OVERALL: float64
COMMIS: int64
SALES_PRICE: int64
This dataset contains 7109 housing data and 19 columns.
Analysis
sqfeet area and the price of house are linearly correlated to eachother.
The price of house and the commission that the broker asks are also correlated.
Family Land has more mean distance from main road which is a good thing.
Parking Facility is equally distributed in all the areas and buildtype in chennai.
Karrapakkam, Adayar and chrompet have low sales( low sqfeet ) price and the rest have a high sale price( high sqfeet).
Machine Learning Models used
linear_reggression:
Score=0.954449 , Best Params={'normalize': False}
lasso:
Score=0.954449 , Best Params={'alpha': 2, 'selection': 'random'}
decision_tree:
Score=0.970032 , Best Params={'criterion': 'friedman_mse', 'splitter': 'random'}

Disclammier
Dataset Sourse:
This dataset was download from :https://www.kaggle.com/code/varunsaikanuri/chennai-houses-sales-analysis-and-prediction
