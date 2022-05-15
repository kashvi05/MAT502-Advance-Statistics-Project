### Introduction

This project is done as a part of the course MAT502 Advance Statistics and is done in order to have strong hold on the concepts taught. This project includes the use of concepts such as Data Collection through sampling and surveys, Data processing, Data analytics or Visualization and lastly Hypothesis Formulation and Testing.

#### Team Members
* Malav Doshi
* Sameep Vani
* Kavya Patel
* Kashvi Gandhi

#### Sampling Method and Data Collection

The data is collected to analyse the usage and willingness to pay for sanitizers due to pandemic. For data collection we have used a method called "Survey". We distriuted this survey to numerous people majorly university students and asked them to fill it out and also try to circulate it to anyone they knew. The survey considered questions on Age-Groups, Gender, Maximum Willingness to pay for a bottle of sanitizers before and after covid and quantity of sanitizer used before and after covid. Based on these we wish to gain some useful insights about the usage and price of sanitizers. The sampling method chosen was voluntary sampling. People wishing to participate in the survey only need to fill the form. However, once a person chooses to fill the form, he or she is required to answer each and every question. This was our way of eliminating non-response bias as much as possible. However, there will definitely be high levels of selection bias as the survey was only circulated to university students and does not take into account general population.

#### Data processing

Once the required survey was conducted and data was collected, we processed it. Since there were many categorical features such as gender, age-groups etc. we used scikit-learn's label encoder to convert these "Object" Data type to "int" or "float" data type. This was done so as to make data visualizations easier. Below shown is the image of encoded features.

#### Data Analytics and Visualization

Below are some of the visualizations that might be useful for hypothesis formulation and testing

#### Hypothesis Formulation

For the sake of simplicity, we have formulated two hypothesis which needs to be tested.

**Hypothesis 1**
* Null Hypothesis (H0): The increase in average maximum willingness to pay for a bottle of sanitizer is only due to chance error and not a direct implication of the pandemic.
* Alternate Hypothesis (H1): The increase in avergage maximum willingness to pay for a bottle of sanitier is not due to chance error but an implication of the pandemic.
* To test this hypothesis, we used the z-test. Based on the z-statistics and p-value, we would either reject or accept the null hypothesis

**Hypothesis 2**
* Null Hypothesis (H0): The chemical preferences of a person is independent of gender.
* Alternate Hypothesis (H1): There is some association between chemical preferences and gender.
* To test this hypothesis, we used the chi-square test because of multiple categories that are involved. After completion, based on the chi-square-statistics and p-value, we would either reject or accept the null hypothesis.