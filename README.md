# ML-Business-Metrics-Evaluation
This repository gives reader a business perspective of ML model metrics and also gives a direction whether a machine learning based solution is helping business use cases or not.

## Model is successfully developed and deployed. Now client ask to prove the worth of the deployed model. What to do?
It is not recommended to explain the technical machine learning metrics (Precision, Recall, etc.) because client only care about the worthiness of the model in terms of monetary aspects. So how to translate ML metrics to business numbers? How to cold start this issue when you are just a data scientist without any business MBA. Generally with big corporation this task is assigned to Business Analysts but in small and agile environment generally a data scientist and team has to do everthing. So, how do we do it and where to start and what question to ask?

### Let's dive into it.
Some concepts: Total revenue generated is an indication of how the company is performing in terms of sales and marketing, effective marketing communication and badly a company is selling it's products and services. Hence to understand such cases we design a **REVENUE METRICS.**

**QUESTION-1:** What is the category of the business, client is operating in? This question is important because here you will be able to sift all the business operations and focus only on one domain. These domains could be:
* Banking, Finance Services and Insurance.
* IT industry.
* Manufacturing.
* E-commerce.
* Online Services and marketing.
* Logistics and Supply Chain Management.
* Telecommunication. <br/>

**QUESTION-2:** Ask about which particular area of business the model is meant for. For eg, Sales & marketing, Operations, Debts, etc.
* Every business measure **3 key metrics:** revenue metrics, metrics related to business operation, metrics pertaining to risk assessment. Ask what business metrics the client is currently measuring. This information always available with the client. Every business has fixed well defined business metrics which are known as **KPI**. KPIs are well defined set of metrics which affect the business in various verticals. These verticals could be Revenue, Marketing, Risk, etc.

* Whenever client says to increase their sales from all sources, ask something which is related to sales and want to estimate the marketing effort whether marketing compaign performing well. Go for **Revenue Metrics** and align your ML metrics with that of client's revenue metrics (Revenue KPI).

* Whenever client says to increase their profitability, ask something which is related to profit and want to enhance the efficiency of the company's operational activity or anything which is operation oriented. Go for **Profitability Metrics** and align your ML metrics with that of client's revenue metrics (Revenue KPI).
