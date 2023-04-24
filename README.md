# Airflow-Forex-Data-Pipeline

Created the fully functional data pipeline that interacts with openexchangerates.org to get the latest exchange rates with base currency of USD. In this project, compared the exchange price of USD with CAD, HKD, ISK, PHP, DKK, GBP, JPY, CHF, EUR, NZD, USD, SGD, AUD.

Pipeline workflow:

First, check the availability of forex rates (for demo purposes, I downloaded an example exchange rates and stored in S3)

Used the below set of operators:

HttpSensor

FileSensor

PythonOperator

BashOperator

HiveOperator

SparkSubmitOperator

EmailOperator

SlackWebhookOperator 
