# Anomaly Detection
---

___Anomaly detection___ _is a technique used to identify unusual patterns that do not conform to expected behavior, called outliers. It has many applications in business, from intrusion detection (identifying strange patterns in network traffic that could signal a hack) to system health monitoring (spotting a malignant tumor in an MRI scan), and from fraud detection in credit card transactions to fault detection in operating environments._

_Anomalies can be broadly categorized as:_

1. ___Point anomalies___ _: A single instance of data is anomalous if it's too far off from the rest. Business use case: Detecting credit card fraud based on "amount spent."_

2. ___Contextual anomalies___ _: The abnormality is context specific. This type of anomaly is common in time-series data. Business use case: Spending $100 on food every day during the holiday season is normal, but may be odd otherwise._

3. ___Collective anomalies___ _: A set of data instances collectively helps in detecting anomalies. Business use case: Someone is trying to copy data form a remote machine to a local host unexpectedly, an anomaly that would be flagged as a potential cyber attack._

_Anomaly detection is similar to — but not entirely the same as — __Noise Removal__ and __Novelty Detection__._

___Novelty Detection___ _is concerned with identifying an unobserved pattern in new observations not included in training data — like a sudden interest in a new channel on YouTube during Christmas, for instance._ 

___Noise removal (NR)___ _is the process of immunizing analysis from the occurrence of unwanted observations; in other words, removing noise from an otherwise meaningful signal._

___Most common causes of outliers/anomaly on a data set:___
* _Data entry errors (human errors)_
* _Measurement errors (instrument errors)_
* _Experimental errors (data extraction or experiment planning/executing errors)_
* _Intentional (dummy outliers made to test detection methods)_
* _Data processing errors (data manipulation or data set unintended mutations)_
* _Sampling errors (extracting or mixing data from wrong or various sources)_
* _Natural (not an error, novelties in data)_

_Also, when starting an outlier detection quest you have to answer two important questions about your dataset:_
* _Which and how many features am I taking into account to detect outliers ? (__univariate / multivariate__)_
* _Can I assume a distribution(s) of values for my selected features? (__parametric / non-parametric__)_

__Some of the most popular methods for outlier detection are:__
* _Z-Score or Extreme Value Analysis (parametric)_
* _Probabilistic and Statistical Modeling (parametric)_
* _Linear Regression Models (PCA, LMS)_
* _Proximity Based Models (non-parametric)_
* _Information Theory Models_
* _High Dimensional Outlier Detection Methods (high dimensional sparse data)_

#### ___Few techniques already covered in OUTLIERS in Data-Preprocessing___

#### ___Techniques discussed in this Space:___
* ___Mahalanobis Distance___
* ___DBSCAN___
* ___Isolation Forests___
* ___Local Outlier Factor___
* ___Elliptic Envelope___
* ___One-Class Support Vector Machines___
