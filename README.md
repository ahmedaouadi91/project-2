# Project-2
we will work on 2 dataset 
* Dataset 1 : Adulte income

business problem
  
  An individual’s annual income results from various factors. Intuitively, it is influenced by the individual’s education level, age, gender, occupation, and etc.
  All these facteur alow to classify individuals into two groups based on their income 

  Data Source : https://www.kaggle.com/

  Data Description : data contains 15 columns : age ,workclass ,fnlwgt ,education ,educational-num ,marital-status , occupation , relationship , race , gender , capital-gain , capital-loss ,hours-per-week ,native-country and income . and contains 48842 rows 

   analytical insights
   ![téléchargement](https://github.com/ahmedaouadi91/project-2/assets/137283070/f3de71ea-272e-4e5a-a88d-e664103922e0)
   
   the barplot above represents the distribution of income according to capital gain, this barplot shows us a significant difference between the two classes in terms of the value of capital gain (>50K and <=50K)

The higher the capital gain, the higher the income too. So we can conclude that the capital gain is a very important factor in determining income

![téléchargement (2)](https://github.com/ahmedaouadi91/project-2/assets/137283070/f7530e7b-8469-43a6-945c-3dc22994573e) 
The bar plot above represents the distribution of capital gain according to occupation. This barplot shows us that certain occupations have a high capital gain such as prof-speciality, exec-managerial and sales occupation while the other occupations have corresponding low capital gain.

Since we have already determined previously that capital gain is an important factor in determining income.We reveal the importance of occupation for determining income

The metrics for the best model

Accuracy = 0.84
Precision = 0.87
recall = 0.93
f1-score = 0.90 

A description of how well your model would solve your business problem

The Model will predict if a stackholders belongs to the first class (incomes <= 50K ) or to the second class (income > 50K) depending on their age ,workclass ,fnlwgt ,education ,educational-num ,marital-status , occupation , relationship , race , gender , capital-gain , capital-loss ,hours-per-week and their native-country 

recommendations
To have good income people should :
* Having High education level (prof-school and Doctorate )
* Choosing high paid occupation such as prof-speciality ,exec-managerial
  

  
* Dataset 2 : Crop recommendation

Business problem :
  
A crop yield results from various factors. Intuitively, it is influenced by the ratio of Nitrogen ,Phosphorous and Potassium content in soil ,temperature ,humidity ,ph value of the soil and rainfall. this dataset allows the users to build a predictive model to recommend the most suitable crops to grow in a particular farm based on various parameters.

Data Source : https://www.kaggle.com/

Data Description : data contains 8 columns (N,P,K, temperature ,humidity, ph, rainfall and label)  and contains 2200 rows

analytical insights
![téléchargement 3](https://github.com/ahmedaouadi91/project-2/assets/137283070/adf49ace-cccb-47df-9ae8-a25eef1e4c6d)

knowing the needs of the crops and the reserves of the soil is very important for the success of the crop and to guarantee an excellent yield and subsequently economic profitability we will discuss two main factors for plant production which are water(rainfall)and nitrogen (N)

The bar plot above represents the distribution of rainfall according to Labes. in other words the variation in water needs depending on labels. This barplot shows us that certain label need a high water quantity (water demanding plants) such as rice, coconut and jute while the other label have moderate to low water need.

![téléchargement 4](https://github.com/ahmedaouadi91/project-2/assets/137283070/6e034405-3ab5-4e25-a133-1586b0478004)

Nitrogen is an essential element for plant growth and production.The bar plot above represents the distribution of nitrogen according to Labes. in other words the variation in nitrogen needs depending on labels. This barplot shows us that certain label need a high nitrogen quantity such as rice,maize,banana,watermelon,muskmelon and cotton while the other label have low nitrogen need.

The metrics for the best model :
Accuracy = 0.99
Precision = 0.99
recall = 0.99
f1-score = 0.99

A description of how well your model would solve your business problem :

The Model will predict if what kind of crops we should plant under given condition (N,P,K,temperature , ph ,rainfall.These will help us to obtain the best harvest yield and therefore economic profitability

Recommendations :

To have best harvest yield and economic profitability Farmer should :
* Get a clear idea of field environmental conditions (temperature ,rainfall) and soil resources (N , P, K , ph )
* Choose crops according to model predictions
* Choose crops that do not require water for dry areas and crops that do not require mineral elements(N,P,K) given the excessive cost of inputs
* 





