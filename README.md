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
* 




  
* Dataset 2 : Crop recommendation

business problem
  
A crop yield results from various factors. Intuitively, it is influenced by the ratio of Nitrogen ,Phosphorous and Potassium content in soil ,temperature ,humidity ,ph value of the soil and rainfall. this dataset allows the users to build a predictive model to recommend the most suitable crops to grow in a particular farm based on various parameters.

Data Source : https://www.kaggle.com/
