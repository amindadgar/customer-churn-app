# customer-churn-app
This is my first app created to predict customer churn. (Using ML Logistic Regression model)

We predict the value of customer churn in this application. <br>
Example customer input: <br>
```customer = {"contract": "two_year", "tenure": 12, "monthlycharges": 10}```<br>
output:<br>
```{'churn': False, 'churn_probability': 0.1754496030637589}```
<br>
We've saved our model and the DictVectorizer in _churn-model.bin_ file. <br>
We've used Procfile for heroku app to be able to run. <br>
Files such as [Pipfile](https://github.com/amindadgar/customer-churn-app/blob/main/Pipfile), [Pipfile.lock](https://github.com/amindadgar/customer-churn-app/blob/main/Pipfile) and [Dockerfile](https://github.com/amindadgar/customer-churn-app/blob/main/Dockerfile) was not needed for the heroku app.
