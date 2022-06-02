# Build, Train, and Deploy ML Pipelines using BERT

This course teaches how to automate a natural language processing task by building an end-to-end machine learning pipeline using Hugging Face’s highly-optimized implementation of the state-of-the-art BERT algorithm with Amazon SageMaker Pipelines. 

* The pipeline will first transform the dataset into BERT-readable features and store the features in the Amazon SageMaker Feature Store. 

* It will then fine-tune a text classification model to the dataset using a Hugging Face pre-trained model, which has learned to understand the human language from millions of Wikipedia documents. 

* Finally, the pipeline will evaluate the model’s accuracy and only deploy the model if the accuracy exceeds a given threshold.

