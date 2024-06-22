# Rice_classification
# 1. Introduction 
Neural Network project for classification of 5 different types of rice.\
In this model we have used 250X250 image for trainig the model.\
We have used 5 varities of rice and the image consists of single grain\
and each variety of rice has 15000 different images to train.\
# 2. description of the model
This model consists of 8 hidden layers which can be trained\
in that consista od functions such as convolve 2d with a \
window size of 7X7 and averaging with a window of 2X2.\
# 3. Accuracy and loss
This model performed with an accuracy of 98.7 % with 75000 images as \
dataset for training and used 15000 images for validation.\
Loss calculated was 0.03 with validation data.\
# 4. Storing the model
Once the model was trained the model was stored as "rice_classification_five_variety.keras"\
file. The model canalso be saved as .hdf5 file format.\
# 5. Graphs discussion 
![training the model with 5 epoch](https://github.com/abhiramvenkatesh/Rice_classification/assets/120402992/b00328de-f8b9-4753-924d-3e07d7de8123)\
Training model required 5 epouch with batch size of 100.\
![validation accuracy](https://github.com/abhiramvenkatesh/Rice_classification/assets/120402992/a5abd383-b66e-464e-9abf-0afba732c614)\
Calculated the accuracy after training the model.\
![validation loss](https://github.com/abhiramvenkatesh/Rice_classification/assets/120402992/b96289b4-0605-4f13-a938-1d375472cf3c)\
Calculated the loss after training.\

# 6. accessing the model and dataset:
Please select the branch main in the branch option.\
The dataset is stored as Rice_image_dataset\
and the model is stored as "rice_classification_five_variety.keras".


