# Image-Classification-VGG16-Pytorch

Repository contains:
  (1) code file (.ipynb)
  (2) test image file (.jpg)
  (3) ImageNet class label lest (.txt)
Sprocess steps:
  (1) Import pretrained model (VGG16)
  (2) Import ImageNet (datset on which VGG16 is traned) label list
  (3) Read test image
  (4) Transfor image to giev as input to VGG16
  (5) Set model in evaluation mode (deactive batchnormalization, dropout etc. during testing/evaluation model)
  (6) Get out of model
  (7) Extract probility out of generated output
  (8) Display class label along with percentage of likelihood
