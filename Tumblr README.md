# Christian_Portfolio
Data Science Portfolio

# Project 1: Tumblr Acqusition Project 

Tumblr Users grew at 5.47% per month since inception, but only 1.52% per month in last 12 months

<img width="825" alt="image" src="https://user-images.githubusercontent.com/69988837/183987748-7db49bc3-8382-4264-bc48-bec192209876.png">

Forecast based on historic user growth indicates likely plateau of users around 200M on all models tested. TBATS has lowest margin of error. 

<img width="817" alt="image" src="https://user-images.githubusercontent.com/69988837/183987915-7f6b7f1a-3b0e-48aa-a2b8-5d1b47d7b6aa.png">

When using a window of 12 months, TBAT model has the lowest MAPE and best apparent performance​

<img width="789" alt="image" src="https://user-images.githubusercontent.com/69988837/183988249-b2f67fc2-9276-4d36-a334-f7df00aac9cb.png">

TBAT forecast estimates users will remain below 150M in worst case, and only reach 195M in the base case​

<img width="779" alt="image" src="https://user-images.githubusercontent.com/69988837/183988554-ef930438-247d-401f-900b-fe9ce8f5bf23.png">

According to TBAT model forecast, Tumblr is only worth $570M in the best case (95% high confidence interval), hence Yahoo has overpaid

<img width="739" alt="image" src="https://user-images.githubusercontent.com/69988837/183988675-eef1b9d7-b1f5-4a9d-9ed5-6acca8c8e45f.png">

**Assumptions & Take-Aways**

Model Choice: TBAT model appeared to perform best with the smallest cone and the lowest MAPE according to some models, hence preferred choice of model. ​

Dampening: Used dampening on all models assuming that the User growth will taper off as the market becomes more saturated. E.g. there is a natural ceiling on users in the US, that cannot exceed the internet using population​

Seasonality: Initial testing on ETS models did not appear to show strong effect of seasonality​

Arima: Arima models performed quite poorly in initial testing, seeming to predict constant growth of users well beyond other models. Hence discarded​

Users: In none of the models that we tested did user growth come close to what was forecast by Yahoo, indicating that their forecast was likely very overoptimistic​

Valuation: Valuation choice very sensitive to assumptions regarding future growth. E.g.  choice of using growth over 36 months vs growth over 12 months has a very strong impact on potential valuation.

