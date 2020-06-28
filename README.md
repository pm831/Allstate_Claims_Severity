# Allstate Claims Severity
### Pujan Malavia

![allstate](https://user-images.githubusercontent.com/19572673/85208114-d3501e00-b2fb-11ea-80cb-2c046c0c7982.jpg)

### Link to Dataset:
https://www.kaggle.com/c/allstate-claims-severity/data

### Abstract:
When you’ve been devastated by a serious car accident, your focus is on the things that matter the most: family, friends, and other loved ones. Pushing paper with your insurance agent is the last place you want your time or mental energy spent. This is why Allstate, a personal insurer in the United States, is continually seeking fresh ideas to improve their claims service for the over 16 million households they protect.

Allstate is currently developing automated methods of predicting the cost, and hence severity, of claims. In this recruitment challenge, Kagglers are invited to show off their creativity and flex their technical chops by creating an algorithm which accurately predicts claims severity. Aspiring competitors will demonstrate insight into better ways to predict claims severity for the chance to be part of Allstate’s efforts to ensure a worry-free customer experience.

### Industry:
Insurance

### Company Information:
We are the Good Hands: We help people realize their hopes and dreams through products and services designed to protect them from life’s uncertainties and to prepare them for the future.

The Allstate Corporation is the largest publicly held personal lines property and casualty insurer in America. Allstate was founded in 1931 and became a publicly traded company in 1993.

Allstate offers car insurance, home, property, condo and renters insurance, plus insurance for recreational vehicles like motorcycles, boats and more.

The Allstate family of companies offers financial products including college savings programs, retirement planning and a range of life insurance products including term life and whole life.

https://www.linkedin.com/company/allstate

https://www.allstate.com/

### Use Case:
Creating an algorithm which accurately predicts claims severity

### Tool:
Python (Jupyter Notebook)

### Techniques:

Random Forest

Logistic Regression

### Initial Dataset(s):
train.csv - the training set

### test.csv - the test set. You must predict the loss value for the ids in this file.

### sample_submission.csv - a sample submission file in the correct format

### Data:
Each row in this dataset represents an insurance claim. You must predict the value for the 'loss' column. Variables prefaced with 'cat' are categorical, while those prefaced with 'cont' are continuous.

### Data Fields:
id

cat1

cat2 ......

cat115

cat116

cont1

cont2 ......

cont13

cont14

loss

### Data Visualization:

Python (Jupyter Notebook) Visualizations

https://github.com/pm831/Allstate_Claims_Severity/blob/master/AllState_Claims_Severity.ipynb

Amount of categorical features with X distinct values and Zooming in the [0,30] part of left histogram

<img width="953" alt="output_27_1" src="https://user-images.githubusercontent.com/19572673/85812199-03e5ec80-b72e-11ea-85cc-8d112504a5ad.png">

Loss values per ID

<img width="966" alt="output_29_1" src="https://user-images.githubusercontent.com/19572673/85812200-03e5ec80-b72e-11ea-8988-e25a79813d5f.png">

Train Loss Target Histogram & Train Log Loss Target Histogram

<img width="953" alt="output_32_0" src="https://user-images.githubusercontent.com/19572673/85812201-047e8300-b72e-11ea-9259-7efbee5d028d.png">

Histograms of all Continuous Features

<img width="946" alt="output_33_1" src="https://user-images.githubusercontent.com/19572673/85812202-047e8300-b72e-11ea-9d58-f42e4c16f055.png">

Heatmap (Correlation plot) of Continuous Variables

<img width="846" alt="output_34_1" src="https://user-images.githubusercontent.com/19572673/85812203-047e8300-b72e-11ea-9692-7d9caf6a0873.png">

### Communication of Results to Business Partner:
To a business partner, I would explain that the Random Forest (all else equal) would work better for complex data (high variance, low bias) that’s a bit more unknown in terms of predictors’ effect on the response variable since it looks at all predictor variables equally in terms of its importance.

### Future Work:
Continue to do hyperparameter tuning of the model and creating new features/removing old features to help increase the prediction accuracy of the model

Try other types of models to see if the accuracy rate improves

More data visualization/patterns within the dataset (external sources) that can lead to more insights and decision-making from a business perspective
