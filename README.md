# Bank-Scheme-Subscription-Prediction

Logistic regression model focusing on significant features extraction using Somers' D and VIF (Variance Inflation Factor).

> <p style="color:Black; font-size:16px;"><b>MODEL DETAILS</b></p>

> Logistic Regression :
> `statsmodels.formula.api.logit` <br>
> CUT-OFF : 0.43 (BEST Accuracy) <br>
> TRAIN ACCURACY : 0.91 <br>
> TEST ACCURACY : 0.91 <br>
> TEST PRECISION : 0.63 <br>
> TEST RECALL : 0.43 <br>
> TEST F1-SCORE : 0.51
> <br>

> <p style="color:Black; font-size:16px;"><b>SIGNIFICANT VARIABLES</b></p>

> Based on the analysis and the Logistic Regression Model evaluation, while campaigning for new Savings Scheme the bank may focus on :
>
> 1. **previous_savings** : number of contacts performed before this campaign and for this client (numeric)
> 2. **cons_price_idx** : consumer price index. monthly indicator (numeric)
> 3. **nr_employed** : number of employees. quarterly indicator (numeric)
> 4. **duration** : last contact duration, in seconds (numeric)
