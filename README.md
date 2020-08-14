# Pima Indians Diabetes Classification with Gaussian Naive Bayes

<img src="/image.jpg" width="1000" height="300" />
<div align="justify">
  
## Naïve Bayes Theory
Naïve Bayes is a classification technique based on Bayes theorem with an assumption of independence among features. It is a way to figure out conditional probability. 
Conditional Probability is the probability of an event happening given that it has some relationship to one or more other events.<br />

Given a hypothesis H and evidence E, Bayes theorem states that the relationship between the probability of the hypothesis before getting the evidence P(H) and the probability of the hypothesis after getting the evidence P(H|E) is<br />

<div align="center">P(H|E) = P(E|H). P(H) / P(E) </div><br />

**Prior Probability P(H):** How probable was our hypothesis before observing the evidence?<br />
**Posterior Probability P(H|E):** How probable is our hypothesis, given the observed evidence?<br />
**Likelihood:** How probable is the evidence given that our hypothesis is true?<br />
**Marginal:** How probable is the new evidence under all possible hypothesis?<br /> 

### Types of Naïve Bayes Model
**Gaussian:** It is used in classification and it assumes that features follow a normal distribution.<br />
**Multinomial:** It is used for discrete counts.<br />
**Bernoulli:** The binomial model is useful if your feature vectors are binary (i.e., zeros and ones).<br />

## Dataset
This dataset describes the medical records for Pima Indians and whether or not each patient will have an onset of diabetes within +ve years.<br />
Data Source: [Diabetes Dataset](https://www.kaggle.com/kumargh/pimaindiansdiabetescsv)<br /><br />

*Pregnancies:* Number of times pregnant<br />
*Glucose:* Plasma glucose concentration a 2 hours in an oral glucose tolerance test<br />
*BloodPressure:* Diastolic blood pressure (mm Hg)<br />
*SkinThickness:* Triceps skin fold thickness (mm)<br />
*Insulin:* 2-Hour serum insulin (mu U/ml)<br />
*BMI:* Body mass index (weight in kg/(height in m)^2)<br />
*DiabetesPedigreeFunction:* Diabetes pedigree function<br />
*Age:* Age (years)<br />
*Class:* Class variable (1: tested positive for diabetes, 0: tested negative for diabetes)<br />

</div>
