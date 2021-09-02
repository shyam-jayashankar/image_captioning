# image_captioning

"Show and tell" : Image Captioning using neural networks

Inspired from the "show and tell " research paper, built an Image captioner, which, when fed with an input image, generates a caption describing the image supplied.

The model deployed had a CNN+RNN architecture, with the CNN aiding in fetching the feature vectors of the input image, and the RNN helping in generating the captions in a sequential manner

Pre-trained Inception V3 model was used for fetching image vectors and LSTM's were deployed to generate captions . The dataset used was Flickr Dataset
