## Links to the Shiny App:
* [GitHub](https://github.com/YufanWu147/Shiny-App-Survival-Analysis/)
* [shinyapps.io](https://yufan-wu.shinyapps.io/Survival_Analysis/)

## Instructions


### Data

-   Upload a CSV file
-   Choose `time` and `event` variables for survival analysis

### Analysis Tools

#### 1. Non-Parametric Methods

##### 1.1 Table

Providing a summary table of estimates of survival probability and
cumulative hazard using either the **Kaplan-Meier** or
**Fleming-Harrington** methods. Check the box
`Show Confidence Interval?` to obtain two-sided 95% confidence intervals
(types: linear, log, log-log).

##### 1.2 Plot

Drawing survival and cumulative hazard curves for the data. Customize
your plots by adding a risk table or a number of censored subjects
barplot. You can draw stratified curves by selecting either a discrete
variable or a continuous variable with specified cutpoints.

##### 1.3 Test

Providing results of a collection of weighted logrank tests for
comparing survival distributions for two or more independent groups. For
more information, see
[`survMisc::comp`](https://www.rdocumentation.org/packages/survMisc/versions/0.5.5/topics/comp).

#### 2. Semi-Parametric Methods (Cox Proportional Hazard Model)

##### 2.1 Model Results

Providing a summary table of coefficient and hazard ratio estimates,
standard errors, etc. Also calculating the log-likelihood and AIC of the
model that can be used in model selection.

##### 2.2 Model Diagnosis

Graphically diagnosing the overall fit and proportional hazard (PH)
assumptions of the cox proportional hazard model.

#### 3. Parametric Methods

##### 3.1 Model Results

Calculating coefficients, acceleration factors and hazard ratios of
exponential and weibull model. Also providing informations for model
comparison.

##### 3.2 Model Diagnosis

Graphically diagnosing the distributional assumptions of the models.
