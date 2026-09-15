# brain-tumor-detection-vgg16
Brain tumor detection from MRI scans using VGG16 feature extraction, SMOTE, and classical machine learning classifiers, evaluated with cross-validation and a held-out test set.
This project classifies brain MRI images as containing a tumor or not, using a Kaggle brain MRI dataset. Images are preprocessed and augmented, then passed through a pretrained VGG16 network to extract features. SMOTE is applied to address class imbalance before training Logistic Regression, Random Forest, and Decision Tree classifiers. Models are evaluated with Stratified 5-Fold Cross-Validation and again on a held-out test set for a reliable performance estimate.

Results: Logistic Regression performed best, with 88% test accuracy and an F1-score of 0.91. Random Forest reached 80% test accuracy, and Decision Tree reached 76%. Cross-validation and test set results are consist
