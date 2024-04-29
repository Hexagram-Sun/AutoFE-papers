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
|IEEE Access|Auto-prep: efficient and automated data preprocessing pipeline|[paper](https://ieeexplore.ieee.org/document/9856663)|2022|detects issues, suggests cleaning methods, and boosts model performance significantly
|Neurocomputing|Data imputation in IoT using Spatio-Temporal Variational Auto-Encoder|[paper](https://researchr.org/publication/ZhangCCCH23)|2023|
|Engineering Applications of Artificial Intelligence|MIVAE: Multiple Imputation based on Variational Auto-Encoder|[paper](https://researchr.org/publication/0003LBW0L23)|2023|data imputation with VAE
|Intelligent Automation & Soft Computing|Missing value imputation model based on adversarial autoencoder using spatiotemporal feature extraction|[paper](https://www.techscience.com/iasc/v37n2/53242/html)|2023|data imputation with GAN

### Feature synthesis
| Venue     | Paper                                                        |                            Links                             |   year    | TLDR                                                         |
| :-------- | :----------------------------------------------------------- | :----------------------------------------------------------: | :-------: | :----------------------------------------------------------- |
|Information Sciences|Automatic features generation and selection from external sources: A dbpedia use case|[paper](https://www.sciencedirect.com/science/article/abs/pii/S0020025521009671)|2022|using meta-learning techniques to predict effective transformations
|Machine Learning|Tsfuse: Automated feature construction for multiple time series data|[paper](https://link.springer.com/article/10.1007/s10994-021-06096-2)|2022
|ASCC|Automated feature engineering for fraud prediction in online credit loan services|[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9828336)|2022
|Arxiv|Macfe: A meta-learning and causality based feature engineering framework|[paper](https://link.springer.com/chapter/10.1007/978-3-031-19493-1_5)|2022|Evaluating the Importance of Features Based on Causal Inference
|CIKM|Mining Cross Features for Financial Credit Risk Assessment|[paper](https://link.springer.com/article/10.1007/s10994-021-06096-2)|2021|Feature cross
|ICDE|SAFE: Scalable Automatic Feature Engineering Framework for Industrial Tasks|[paper](https://www.computer.org/csdl/proceedings-article/icde/2020/09101784/1kaMGB3kDJe)|2020
|ECMLPKDD|Automating feature construction for multi-view time series data|[paper](https://link.springer.com/article/10.1007/s10994-021-06096-2)|2019|FE for time series
|AAAI|Feature engineering for predictive modeling using reinforcement learning|[paper](https://arxiv.org/abs/1709.07150)|2018|apply all operations at once to expand feature set and then search for the best features
|Ijcai|Learning feature engineering for classification|[paper](https://www.ijcai.org/proceedings/2017/352)|2017


### Other feature engineerng works
| Venue     | Paper                                                        |                            Links                             |   year    | TLDR                                                         |
| :-------- | :----------------------------------------------------------- | :----------------------------------------------------------: | :-------: | :----------------------------------------------------------- |
|Springer|Evolutionary automated feature engineering|[paper](https://link.springer.com/chapter/10.1007/978-3-031-20862-1_42)|2022|
Briefings in Bioinformatics|Bioautoml: automated feature engineering and metalearning to predict noncoding rnas in bacteria|[paper](https://www.researchgate.net/publication/361568774_BioAutoML_automated_feature_engineering_and_metalearning_to_predict_noncoding_RNAs_in_bacteria)|2022|
|International Conference on Automated Machine Learning|Difer: differentiable automated feature engineering|[paper](https://arxiv.org/abs/2010.08784)|2022
