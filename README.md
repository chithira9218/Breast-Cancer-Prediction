                                      PREDICTING BREAST CANCER IN A PATIENT

   Breast cancer represents one of the diseases that make a high number of deaths every year. It is the most common type of all cancers and the main cause of women's deaths worldwide. Classification and data mining methods are an effective way to classify data. Especially in the medical field, where those methods are widely used in diagnosis and analysis to make decisions.
     Given the details of cell nuclei taken from breast mass, predict whether or not a patient has breast cancer using the Ensembling Techniques. Perform necessary exploratory data analysis before building the model and evaluate the model based on performance metrics other than model accuracy.
     The dataset consists of several predictor variables and one target variable, Diagnosis. The target variable has values 'Benign' and 'Malignant', where 'Benign' means that the cells are not harmful or there is no cancer and 'Malignant' means that the patient has cancer and the cells have a harmful effect.
     
The basic workflow includes:  Analysing the available data and exploring relationships among given variables
                              Data Pre-processing
                              Training SVM classifier to predict whether the patient has cancer or not
                              Assess the correctness in classifying data with respect to efficiency and effectiveness of
                              the SVM classifier in terms of accuracy, precision, sensitivity, specificity and AUC ROC
                              Tuning the hyperparameters of SVM Classifier provided by the scikit-learn library
