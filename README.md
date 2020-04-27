# MAT496-project

This is the project repo for the course MAT496. The main purpose of this project is to apply the BERT model for sequence classification. The main structure of this project is inspired by the example ["A Hands-On Guide To Text Classification With Transformer Models (XLNet, BERT, XLM, RoBERTa)"](https://towardsdatascience.com/https-medium-com-chaturangarajapakshe-text-classification-with-transformer-models-d370944b50ca) done by [Thilina Rajapakse](https://towardsdatascience.com/@chaturangarajapakshe).         

- The [`data.py`]() contains the dataset we used: the yelp review data.     
- The [`utils.py`]() contains some useful functions & classes for the training, e.g. `InputFeature`, `DataProcessor`, `convert_example_to_feature`, and `convert_examples_to_features`, etc.      
- The [`model_config.py`]() contains the structure of the model, as well as the training and evaluation. **Train_with_early_stopping** and **freezing the bert layers** can be found here.      
- The [`gradient_clip.py`]() and [`transfer_learning.py`]() are 2 tutorial notes from [pytorch](https://pytorch.org). The tricks of early stoppings and layer freezing are inspired by these 2 notes.         
