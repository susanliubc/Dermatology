# Dermatology

## Machine learning project using Random Forest, Extra-Trees Classifier, XgBoost and Support Vector Machines(SVM) conducted classification prediction of erythemato-squamous diseases from 12 clinical and 22 histopathological attributes.

## In age attribute, there are eight missing values. After filling these missing values with median age, the best accuracy was achieved with XgBoost and SVM with 96.36%, while the rest of two methods got 95.45% accuracy. Although someone commented SVM is not suitable for qualitative variable analysis, it is superising to see the high performance in this scenario. StandardScaler was used to normalize tha data, so MinMaxScaler could be tried next time to see if it performs better.
