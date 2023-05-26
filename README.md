# Faster R-CNN On Google Colab
Using this repo you can easily train Faster R-CNN model on google colab.

## How to Use
1. Clone the repo in google colab using ```!git clone {COPY THE HTTP LINK FOR THIS REPO}```
2. Upload your data to the data directory(Directory already has a format in place, you can utilize that).
3. Make changes in the <b>config.py</b> file(Update the Dataset paths in the config file to yours, also change hyperparameters such as epochs etc to your desired needs).
4. Run ```!python train.py``` to train the model
5. Run ```!python inference.py``` to test the model on test data(Data in test directory)
  

  
Repo was created from reference of this Web : https://debuggercafe.com/a-simple-pipeline-to-train-pytorch-faster-rcnn-object-detection-model/
