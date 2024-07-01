# __Animal Detection System__

### __Project Overview__
This project uses a Convolutional Neural Network (CNN) to classify images of animals into three categories: Beaver, Moose, and Cat. The model is trained using TensorFlow and Keras.
__Important__: The following code/data is a basic format for this sort of image detection project. Significant improvements must be made in order to design a reliable system. Improvements can be through: higher quality images (zoom into animals, eliminate drawings/ai generated images), more images (using zoom/crop techniques to reuse the same image) and longer training time (increase epoch).

### __Dataset__
- **'dataset'**: Contains subdirectories for each class (beaver, moose, cat) taken from Bing with respective images for training and validation.
- **Test images**: Images used to test the model predictions.

### __Requirements__
- Python 3.x
- numpy
- tensorflow
- matplotlib

### __Usage__
1. Clone the repository and navigate to the project directory.
2. Ensure your dataset is organized as follows:
dataset/
├── beaver/
├── moose/
└── cat/
3. Place your test images in the project directory.
4. Run the notebook to train the model and make predictions.

### __Acknowledgements__
This project utilizes TensorFlow and Keras for building and training the CNN model.