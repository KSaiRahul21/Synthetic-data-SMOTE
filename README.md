# Synthetic Data Generation using SMOTE 

This project is a variant of __Synthetic Minority Over-sampling Technique (SMOTE)__ for the sake of generating synthetic data.<br> 

This technique is generally used to create synthetic data for imbalanced classes but have shown good results for generating synthetic data.

It is implemented from scratch by referring the algorithms present in the [research paper](https://jair.org/index.php/jair/article/view/10302/24590) :<br>

- __SMOTE__  can be used __only__ for continuous data and is already implemented but it __cannot__ be used for datasets containing categorical features.
- __SMOTE-NC__ method can be used for this purpose.

It has shown good results on [Adult Dataset](http://archive.ics.uci.edu/ml/datasets/Adult) of UCI ML Repository
