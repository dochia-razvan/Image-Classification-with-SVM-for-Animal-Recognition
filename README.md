# Image-Classification-with-SVM-for-Animal-Recognition

Classification of animal images using the Support Vector Machine (SVM) algorithm. The dataset used for this task consists of 5,000 images categorized into 10 different animal classes. The images were preprocessed to a uniform size and normalized for the model training, followed by feature extraction using Histogram of Oriented Gradients (HOG)

The SVM algorithm with a linear kernel was chosen. The features extracted from the images through HOG were used as input to the SVM classifier. The model was trained on 80% of the dataset (4,000 images) and tested on the remaining 20% (1,000 images). The resolution of the images was set to 128x128 pixels.

The results of the classification showed a general accuracy of 36%, with notable difficulties in differentiating between similar animal species such as spiders and butterflies, and dogs and horses. 


