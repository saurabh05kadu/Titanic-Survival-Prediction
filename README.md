# Titanic-Survival-Prediction

01.Industry Name:Lifestyle
 
02.Project Title: Titanic Survival Prediction
 
03.Problem Statement/Opportunity:The sinking  of  RMS Titanic is presumably one  of  the most infamous and  disastrous  shipwrecks  in  history.  During her maiden  voyage  and early  morning  hours  of  April  15, 1912,  the Titanic regrettably sank after colliding with an iceberg, killing an approximate of 1502 passengers and crew  out of  2224  making  it one of many  of the deadliest  commercial  maritime  in  history  till date.  The  entire  international  community  was  deeply  shocked and saddened  after  hearing  the  news  of  this  sensational  disaster which resulted  in improved ship safety legislation.  Her architect, Thomas  Andrews  died  in  the  disaster.  An  eye-opening observation  that  came  forth  from  the  sinking  of  Titanic  is  the fact that some  individuals  had  a  better  chance  at  surviving  than the  others.  Kids  and  women  had  been  given  foremost  priority. Social  classes  were  heavily  stratified  in  the  early  twentieth century,  this  was especially  implemented on  the Titanic  Firstly, the  aim  is  use  and  apply  exploratory  data  analytics  (EDA)  to uncover  previously  unknown  or  hidden  facts  in  the  data  set available.  Then  the  task  is  to  later  anoint  various  machine learning  models  to  conclude  the  study  of  which  types  of individuals are more likely to live. The outcomes of application of the different  machine  learning models were then  set  side  by side and analyzed based upon precision.

04.Project Description:The  disaster  that  occurred  over  a  century  ago  ripped  off many parts of the Titanic during the fateful night. Regrettably, there were not  enough  lifeboats present to rescue all the  2224 passengers  onboard.  The  dead  included  many  men  whose place were given to the children and women.The goal  of  this project is  to correctly  predict who would  survive  the  Titanic  given  a  set  of  demographic information.  A  predictive  model  using  passenger  data  was built so  people’s genders, their  ages,  what class of ticket they belonged from, and their socio-economic class, all contributed to  whether  they  would  be  lucky  enough  to  survive  or tragically  perish  on  the  Titanic.  Predictive  analysis  is  a method of determining  important and useful patterns in broad data  sets by  combining  statistical  approaches. To  determine significant  and  useful  trends  in  large  data.  Survival  is predicted  using  machine  learning  algorithms  based  on different feature combinations.  Aim of this project is thereby to conduct exploratory data analytics to excavate different knowledge existing in available data set and to perceive the  impact of every field with respect to  the  passengers’  survival  by  the  use  of  “Survival”  field analytics  in  between  each  field of  the  data set.  Data analysis on  applied  algorithms  was  performed  and  likewise  the accuracy  was  tested.  Based  on  this,  different algorithms  are compared,  and  the  best  performing  model  was  selected. After  analyzing  the  Titanic  dataset,  two  predictions  were generated. The first  was to see what the  lucky passengers had in common that helped them survive  the shipwreck, while the second was to see if  I would have survived  had I been aboard the fateful ship by applying the tools of machine learning.

05.Primary Azure Technology: AI + Machine Learning, Azure Data Explorer, Azure Machine Learning

Working

![Screenshot (62)](https://user-images.githubusercontent.com/97496451/150307408-5b23dd6c-2fea-4b35-a297-a353221aefab.png)

![Screenshot (66)](https://user-images.githubusercontent.com/97496451/150307484-a959eb56-4a8b-419c-ad16-de46a1915f80.png)

![Screenshot (76)](https://user-images.githubusercontent.com/97496451/150307541-381f8ecc-b062-46bc-9e35-d3e0c2a64c98.png)

![Screenshot (74)](https://user-images.githubusercontent.com/97496451/150307602-a49e7a3c-74ca-4029-b3c0-5eb4153f5c50.png)





What are Bayesian Networks?
In general, Bayesian Networks (BNs) is a framework for reasoning under uncertainty using probabilities. More formally, a BN is defined as a Directed Acyclic Graph (DAG) and a set of Conditional Probability Tables (CPTs). In practice, a problem domain is initially modeled as a DAG.
Naive Bayes assumes that the variables are independent and comes from a Gaussian distribution.




The Bayes theorem

![Thomas_Bayes](https://user-images.githubusercontent.com/97496451/150307943-ede1108a-a56e-4e04-8a0c-4dcdffc10eeb.png)

* P(A|B) is the posterior probability of class (A, target) given predictor (B, attributes).
* P(A) is the prior probability of class.
* P(B|A) is the likelihood which is the probability of predictor given class.
* P(B) is the prior probability of predictor.



What are the Pros and Cons of Naive Bayes?
Pros:
Humans are not good with reasoning in systems with limited or conflicting information. It would be handy if we have something to manage all this limited/conflicting information.
It is easy and fast to predict class of test data set. It also perform well in multi class prediction
When assumption of independence holds, a Naive Bayes classifier performs better compare to other models like logistic regression and you need less training data.
It perform well in case of categorical input variables compared to numerical variable(s). For numerical variable, normal distribution is assumed (bell curve, which is a strong assumption).

Cons:
Probably the most notable weakness of BNs is the designing methodology.There is no standard way of building BNs.
If categorical variable has a category (in test data set), which was not observed in training data set, then model will assign a 0 (zero) probability and will be unable to make a prediction. This is often known as “Zero Frequency”. To solve this, we can use the smoothing technique. One of the simplest smoothing techniques is called Laplace estimation.
On the other side naive Bayes is also known as a bad estimator, so the probability outputs from predict_proba are not to be taken too seriously.
Another limitation of Naive Bayes is the assumption of independent predictors. In real life, it is almost impossible that we get a set of predictors which are completely independent.


Project Working Video:https://user-images.githubusercontent.com/97496451/150315983-515e8eb4-ec79-4f1f-b933-518d83e9c678.mp4

https://user-images.githubusercontent.com/97496451/150315983-515e8eb4-ec79-4f1f-b933-518d83e9c678.mp4




 

