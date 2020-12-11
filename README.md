# MAADS-HPDE

HPDE performs AutoML on (training) data streams.  To start HPDE run the command (on both Windows/Linux environments):
1) Command: [HPDE executable] [host] [port]
2) Create unlimited number of HPDE instances for massive scale - fully compatible with microservices architecture for load shedding
3) HPDE can be accessed via MAADS python library or REST API

HPDE will run the following **supervised** algorithms:
1) Neural networks
2) Logistic regressions/Decision Trees
3) Gradient boosting regressions
4) Linear/Non-Linear regressions
5) Mathematic Optimization - if you want to find Global Optimal values for the independent variables and do **prescritive analytics**

HPDE will also fine tune all of the hyperparameters. 

HPDE will also run **unsupervised** algorithms on data streams.  Unsupervised algorithms are especially important for data streams because it is not always possible to classify data for supervised learning.  For example, if doing **Fraud Detection using TML**, then this would require **past** knowledge of fraud, but this is not always possible with real-time data streams.  So HPDE performs advanced unsupervised learning using:
1) Peer Group Analysis (PGA)
2) Break Point Analysis (BPA)

There are enormous advantages to performing unsupervised learning on data streams such as:
1) *At Scale* Fraud (anomaly) detection without classifying data (no knowledge of historical fraud is needed)
2) *Real-Time* Fraud (anomaly) detection
3) *Distributed* Fraud (anomaly) detection

Examples of TML for Fraud (anomaly) detection:
1) **Transactional Banking** - as transactions are done in real-time, TML solutions using HPDE can **detect Fraud (anomalies) is seconds**
2) **IoT predictive asset maintainennce** - detect possible equipment failure on millions of IoT devices in real-time
3) **Product Failure** - detect possible product failure and increase product quality

Lot more use cases for both supervised and unsupervised learning using HPDE with VIPER on data streams.
