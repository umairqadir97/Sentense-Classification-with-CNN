# Sentense-Classification-with-CNN
Sentence Level Text Classification with Convolutional Neural Networks

### Project: Text Classification using Convolutional Neural Network


### Details:

 - This is a **multi-class text classification (sentence classification)** problem.
 - The goal of this project is to **classify Consumer Complaints into classes**. 
 - Also Extract if some Maintenance issue is mentioned in customer reivew.
 - The model was built with **Convolutional Neural Network (CNN)** and **Word Embeddings** on Tensorflow.


## Requirements

- Python 3
- Tensorflow
- Numpy
- Pandas


### Data Format:

 - Input: **consumer_complaint_narrative**
 
 - Output: **product**

### Train:

 - Command: python3 train.py training_data.file parameters.json
 - Example: ```python3 train.py ./data/consumer_complaints.csv.zip ./parameters.json```
 
 A directory will be created during training, and the trained model will be saved in this directory. 

### Predict:

 Provide the model directory (created when running ```train.py```) and new data to ```predict.py```.
 - Command: python3 predict.py ./trained_model_directory/ new_data.file
 - Example: ```python3 predict.py ./trained_model_1479757124/ ./data/small_samples.json```
 
 
 ## References

- [Convolutional Neural Networks for Sentence Classification](http://arxiv.org/abs/1408.5882)
- [A Sensitivity Analysis of (and Practitioners' Guide to) Convolutional Neural Networks for Sentence Classification](http://arxiv.org/abs/1510.03820)
