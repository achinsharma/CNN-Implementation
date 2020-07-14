# CNN-Implementation

Convulation Neural Network implemented on two datasets. 1. Fashion MNIST 2. CRIFAR 10 dataset.
A basic approach was taken for Fashion MNIST, a 3 layer CNN was created which produced a good accuracy, however the model was found to be overfitting in some situations. The validation loss was increasing with time and the validation accuracy remaind sort of constant (fluctuating around 83%). This means that the model was becoming more confident of the wrong predictions it was making. With increase in EPOCHS the validation loss would have increase to a certain point and then converged.
For CRIFAR 1O the same approach was taken as the mentioned above. As execpted the results were the same. The model was overfitting however in this case the accuracy was also lower than that of the Fashion MNIST dataset. This is expected as this dataset is far more complex than FASHION MNIST.

Approaches taken to impove accuracy and prevent overfitting.

- BATCH NORMALIZATION -  A layer of batch normalization was added between every two CNN layers.
- DATA AUGMENTATION 

The notebook attached has only batch normalization, due to system limitations could not run the model for the desired EPOCHS. I will be uploading a GooleColab file with both batch normailization and data augmentation.
