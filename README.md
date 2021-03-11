# DistilBERT-based emotions' classifier

## Description
We use a pre-trained transformer-based network *DistilBERT* to generate embeddings for our input sentences.
Then, we use a 4-layers neural network to predict a target emotion.
We predict 5 emotions: *happiness*, *sadness*, *worry*, *uncertainty*, *neutral*.

Our model reached **0.9624** as training accuracy, and **0.9627** as test accuracy.
We generate a more detailed evaluation report (accuracy, precision, recall, F-score) in the notebook.

See [this notebook](./5Emotions_deep_DistilBert.ipynb) for more details about the implementation and evaluation.

## Project structure
The project contains these 2 files:
* [5Emotions_deep_DistilBert.ipynb](./5Emotions_deep_DistilBert.ipynb): A notebook that contains all the implementation details: data gathering, preprocessing, model implementation, evaluation and predictionm etc.
* [combined_data.csv](./combined_data.csv): This *CSV* file contains the processed data collected from different sources. The data has the following format: 
**sentence, [happiness, sadness, worry, undertain, neutral]**

## Links
See [this document](https://drive.google.com/file/d/1aiPrTkQnRxBmuwV2CygcV0MU1kBbpPU5/view?usp=sharing) for more information about this project.

The pre-trained model is available at [this link](https://drive.google.com/file/d/1NtYegiwOOLRNz8k187McBHyediLIYh6q/view?usp=sharing).
