# DL VQA basic
 A basic VQA model that takes in image and text and output answer.
 
In short, here we train a model that takes in visual features extracted from Inception model and the text embedding of the question and try to answer the (yes/no) question.
 
Here we only use a subset of COCO dataset (20,000 samples) and the text is also preprocessed (in "mini-vqa_starter2.csv").

- preprocessing: extract images contained in "mini-vqa_starter2.csv" and resize the images so they fit in Inception-v3 model.
- VQA_basic: the whole preprocessing pipeline (including unzip the dataset from google drive), the model and training, checkpoint using tf.
- original_code: the original homework files that contains all the information.
