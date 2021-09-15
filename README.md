# Face-mask-detection

In this project, we will be working on the Face Mask detection problem.

The Dataset contains images of people wearing masks and people not wearing masks. The database contains 10,000 colored images in the training folder, 800 images in the validation folder, and 992 images in the test folder.
I have used CNN model with Transfer Learning to classify.

### Steps to follow
1. Download the dataset.
2. Created test, train, and validation directory variables
3. Created train and validation data generator with target size (128,128)
4. Trained a CNN model
5. Trained a model with VGG19 model
6. Used callbacks to save your model at every step
7. Training may take several hours, so I have used 5 to 10 epochs only
