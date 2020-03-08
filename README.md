# CBMS2020
Machine Learning Early Warning System: a Multicenter Validation in Brazilian Hospitals

**Author:** Jhonatan Kobylarz, Henrique Santos, Felipe Barletta, Mateus Silva, Renata Vieira and Cristian Rocha

**Abstract:** Early recognition of clinical deterioration is one of the main steps for reducing inpatient morbidity and mortality. The challenging task of clinical deterioration identification in hospitals lies in the intense daily routines of healthcare practitioners, with the unconnected patient data stored in the Electronic Health Records (EHRs) and the usage of low accuracy scores. Since hospital wards are given less attention compared to the Intensive Care Unit, we hypothesized that when a platform is connected to a stream of EHR, awareness of dangerous situations would improve drastically and could thus assist the healthcare team. With the application of machine learning, the system is capable to consider all patient's history and through the use of high-performing predictive models, an intelligent early warning system is enabled. In this work, we used six Brazilian hospitals with 121,089 medical encounters and 7,540,389 data points and we benchmark six different scalable machine learning methods; three classic machine learning models (tree, logistic and simple probabilistic based models) and also three gradients boosted models, against popular wards protocols. The results showed an advantage in AUC of 25 percentage points in the best Machine Learning model result compared to the current state-of-the-art protocols, this is shown by the generalization of the algorithm with leave-one-group-out (AUC of 0.949) and the robustness through cross-validation (AUC of 0.961). We also perform experiments to compare several window sizes to justify the use of 5 patient timestamps. A sample dataset, experiments, and code are available for replicability purposes.

**Keywords:** Early Warning System, Predictive medicine, Machine Learning, Explainable AI, Healthcare, Vital Signs

Full Text, BibText (soon)

### Online Experiments
##### Run our experiments online with Binder
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/laura-health/cbms2020/master)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/laura-health/cbms2020/blob/master/colab_experiments.ipynb)

### Data Share
A publicly available sample of one of the biggest Cancer Hospitals in southern Brazil with 13,652 attendances previously approved by the Erasto Gaertner Hospital Research Ethics Committee - n 99706718.9.0000.0098