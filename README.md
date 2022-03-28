# Text classification on GLUE.

Repository contains my research research on training different classifiers to achieve the best metrics on `GLUE` datasets.

# Implemented tasks
- ## SST-2
    - BERT as feature extraction, the classifier are classical machine learning methods. 
    - Implemented fine-tuning DistilBert model with custom classifier on PyTorch.
- ## RTE
    - BERT as feature extraction, the classifier are gradient boosting methods.
    - Implemented fine-tuning Bert-base model with custom classifier on PyTorch.
- ## CoLA
    - Implemented fine-tuning Bert-base model with `HuggingFace` Trainer API (model with parameters attached above)
    - Implemented fine-tuning Bert-base model with custom classifier on PyTorch.
  
___
### Completed version with results: [click!](https://github.com/grgera/GLUE/blob/main/GLUE.ipynb)
### Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/grgera/GLUE/blob/main/GLUE.ipynb)
___

<!-- https://colab.research.google.com/github/girafe-ai/ml-mipt/blob/21f_basic/week0_02_linear_reg/week0_02_linear_regression_and_sgd.ipynb -->