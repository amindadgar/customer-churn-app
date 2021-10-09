# customer-churn-app
This is my first app created to predict customer churn. (Using ML Logistic Regression model)

We predict the value of customer churn in this application. <br>
Example customer input:
```customer = {"contract": "two_year", "tenure": 12, "monthlycharges": 10}```
output:
```{'churn': False, 'churn_probability': 0.1754496030637589}```
<br>
We've saved our model and the DictVectorizer in _churn-model.bin_ file.
We've used Procfile to add dependencies for heroku app. The Dockerfile was to run the code in docker(No need for heroku app).

