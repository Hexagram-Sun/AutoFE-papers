# AutoFE papers
This is a collection of significant papers on Automated Feature Engineering (AutoFE), an essential process in machine learning (ML) that involves automatically selecting and transforming the input features to improve the performance of ML models.

## Introduction

Feature engineering is a crucial step in the development of machine learning models. It involves the creation, selection, and transformation of raw data into features that can be used in machine learning algorithms. However, manual feature engineering is time-consuming, requires domain expertise, and is often considered more of an art than a science. Automated Feature Engineering (AutoFE) aims to automate this process, making it more efficient and accessible to practitioners without deep domain knowledge.

AutoFE techniques leverage algorithms to discover feature transformations and interactions that are most relevant to the model's predictive performance. This automation helps in significantly reducing the time and effort involved in manual feature selection and transformation, thus speeding up the model development process and potentially uncovering complex patterns in the data that might not be evident through manual analysis.

The core idea behind AutoFE is not just to automate the feature engineering process but also to optimize it in a way that maximally enhances the performance of machine learning models. This involves a combination of search algorithms, statistical techniques, and machine learning methods to evaluate and select the best features.

Automated feature engineering can broadly be categorized into three main components: automated data preprocessing, feature synthesis, and feature selection.

Automated data preprocessing encompasses tasks such as data cleaning, handling missing values, and normalization. This initial step ensures that the data is in a suitable format for further analysis and model building. By automating these preprocessing steps, practitioners can save valuable time and reduce the risk of introducing human error into the data preparation process.

Feature synthesis involves the creation of new features from existing ones or by combining multiple features in meaningful ways. This step aims to capture complex relationships and patterns in the data that may not be immediately apparent. Automated techniques use algorithms to explore various feature combinations and transformations, allowing for the discovery of novel features that can improve model performance.

Feature selection focuses on identifying the subset of features that are most relevant for predicting the target variable. Automated methods employ different strategies, such as statistical tests, model-based evaluations, or heuristic search algorithms, to efficiently explore the feature space and identify the most informative features. By automating this process, practitioners can avoid the tedious and error-prone task of manually evaluating numerous feature combinations.

Additionally, some efforts in the field of automated machine learning (AutoML) incorporate feature engineering as part of a larger framework for automating the entire machine learning pipeline. These comprehensive AutoML solutions aim to streamline the model development process from data preprocessing to model deployment, further enhancing the accessibility and efficiency of machine learning for practitioners across domains.

## Paper List

### Automated data preprocessing


| Venue     | Paper                                                        |                            Links                             |   year    | TLDR                                                         |
| :-------- | :----------------------------------------------------------- | :----------------------------------------------------------: | :-------: | :----------------------------------------------------------- |
|/|PyChemFlow: an automated pre-processing pipeline in Python for reproducible machine learning on chemical data|[paper](https://chemrxiv.org/engage/chemrxiv/article-details/64b9082aae3d1a7b0d0a53dc)|2023|
|IEEE Access|Auto-prep: efficient and automated data preprocessing pipeline|[paper](https://ieeexplore.ieee.org/document/9856663)|2022
|Neurocomputing|Data imputation in IoT using Spatio-Temporal Variational Auto-Encoder|[paper](https://researchr.org/publication/ZhangCCCH23)|2023|
|Engineering Applications of Artificial Intelligence|MIVAE: Multiple Imputation based on Variational Auto-Encoder|[paper](https://researchr.org/publication/0003LBW0L23)|2023|
|Intelligent Automation & Soft Computing|Missing value imputation model based on adversarial autoencoder using spatiotemporal feature extraction|[paper](https://www.techscience.com/iasc/v37n2/53242/html)|2023|