## PROJECT_IMAGE_CAPTIONING
With the help of this project, machine can generate its own captions related to the image. The model uses Flickr dataset for training data and uses LSTM for training.
## Dataset
The link for flickr dataset that i have used while training my model is [here](https://drive.google.com/file/d/15JBxy8bxT1l7ru63kOSq0_tVdZKF_PpR/view?usp=sharing)
## The Model made contains:
Image model: for reducing image of high dimensions into selected features using Transfer Learning (Resnet50)

Language model: for creating output as embeddings to reduce complexity of model.

Final model: which will concatenate results of both this model and will use LSTM layer and Time Distributed layer for doing final_predicttions.
## One of example of final prediction:
