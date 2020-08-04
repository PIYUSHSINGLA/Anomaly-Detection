# Anomaly Detection
---

___Anomaly detection___ is a technique used to identify unusual patterns that do not conform to expected behavior, called outliers. It has many applications in business, from intrusion detection (identifying strange patterns in network traffic that could signal a hack) to system health monitoring (spotting a malignant tumor in an MRI scan), and from fraud detection in credit card transactions to fault detection in operating environments.
_Anomalies can be broadly categorized as:

1. ___Point anomalies___ : A single instance of data is anomalous if it's too far off from the rest. Business use case: Detecting credit card fraud based on "amount spent."

2. ___Contextual anomalies___ : The abnormality is context specific. This type of anomaly is common in time-series data. Business use case: Spending $100 on food every day during the holiday season is normal, but may be odd otherwise.

3. ___Collective anomalies___ : A set of data instances collectively helps in detecting anomalies. Business use case: Someone is trying to copy data form a remote machine to a local host unexpectedly, an anomaly that would be flagged as a potential cyber attack.

Anomaly detection is similar to — but not entirely the same as — __Noise Removal__ and __Novelty Detection__.

___Novelty Detection___ is concerned with identifying an unobserved pattern in new observations not included in training data — like a sudden interest in a new channel on YouTube during Christmas, for instance. 

___Noise removal (NR)___ is the process of immunizing analysis from the occurrence of unwanted observations; in other words, removing noise from an otherwise meaningful signal.

___Most common causes of outliers/anomaly on a data set:___
* Data entry errors (human errors)
* Measurement errors (instrument errors)
* Experimental errors (data extraction or experiment planning/executing errors)
* Intentional (dummy outliers made to test detection methods)
* Data processing errors (data manipulation or data set unintended mutations)
* Sampling errors (extracting or mixing data from wrong or various sources)
* Natural (not an error, novelties in data)

_Also, when starting an outlier detection quest you have to answer two important questions about your dataset:_
* Which and how many features am I taking into account to detect outliers ? (__univariate / multivariate__)
* Can I assume a distribution(s) of values for my selected features? (__parametric / non-parametric__)

__Some of the most popular methods for outlier detection are:__
* Z-Score or Extreme Value Analysis (parametric)
* Probabilistic and Statistical Modeling (parametric)
* Linear Regression Models (PCA, LMS)
* Proximity Based Models (non-parametric)
* Information Theory Models
* High Dimensional Outlier Detection Methods (high dimensional sparse data)

#### ___Few techniques already covered in OUTLIERS in Data-Preprocessing___

#### ___Techniques discussed in this Space:___
* ___Mahalanobis Distance___ _-Non-Paramteric_
* ___DBSCAN___ _[Available in Unsupervised Learning]_ _-Non-Paramteric_
* ___Isolation Forests___ _-Non-Paramteric_
* ___Local Outlier Factor___ _-Non-Paramteric_
* ___Elliptic Envelope___ _-Paramteric_
* ___One-Class Support Vector Machines___ _-Non-Paramteric_
