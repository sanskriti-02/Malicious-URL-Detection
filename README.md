# Optimizing Malicious URL Detection through Ensemble Meta-Learning Techniques

The The proliferation of malicious Uniform Resource Locators (URLs) poses a significant threat to network and cyber security, necessitating robust detection mechanisms. Utilizing machine learning techniques seems to offer a promising solution to this challenge, especially to enhance URL detection accuracy. In this study, we proposd a novel approach utilizing stacking classifiers to improve the identification of malicious URLs, utilizing the ISCX-URL-2016 dataset provided by the Canadian Institute for Cyber Security.

The proposed approach focuses on utilizing URL strings as the primary source of information for detecting malicious content. The performance of different machine learning algorithms, including Histogram-based Gradient Boosting Classification Tree, XGBoost Classifier, CatBoost Clas- sifier, Random Forest Classifier and more, were compared for the detection of malicious URLs. The two best performing base classifiers were identified and evaluated as potential meta-classifiers. Various combinations of base classifiers were then tested in conjunction with these two selected meta-classifiers. 

Our results demonstrated significant advancements, with the combination of all base classifiers and the XGBoost meta-classifier achieving an impressive accuracy rate of 98.25%. Additionally, the combination of the three best base classifiers with XGBoost yields a commendable accuracy of 98.2%. These findings highlighted the efficacy of our approach in strengthening URL detection accuracy, offering a promising solution to combat the evolving cyber threats. 
