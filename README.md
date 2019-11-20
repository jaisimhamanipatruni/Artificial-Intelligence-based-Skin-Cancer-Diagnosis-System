# Artificial Intelligence Based Skin Cancer Diagnosis System

## Diagnosis of Skin Cancer Using Deep Learning AI model



### Cases of Study

The increasing incidences of skin cancer significantly raises pressure of healthcare costs and creates more demands of specialist services. The diagnosis of skin cancer usually requires dermoscopic analysis followed by a biopsy and pathological examination. By applying machine-learning techniques, it has a great chance to change the landscape of skin cancer diagnosis and reshape the role of dermatologists. 

Deep convolutional neural network (CNN) has been proven its terrific capability on classification of various images through extracting key features. Therefore, in this project, a dataset included 10015 dermatologic related with pigmented skin images with seven well labelled classes (Melanocytic Nevi, Melanoma, Benign Keratosis, Actinic Keratoses, Dermatofibroma, Vascular Skin Lesion, Basal Cell Carcinoma) was used to train several CNN models with different architectures.  The final model will be deployed online to allow users to predict skin cancer categories.

Data
Skin cancer mnist. Dermatoscopic images were from different populations, acquired and stored by different modalities. The final dataset consists of 10015 dermatoscopic images which can serve as a training set for academic machine learning purposes. Cases include a representative collection of all important diagnostic categories in the realm of pigmented lesions: Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec), basal cell carcinoma (bcc), benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl), dermatofibroma (df), melanoma (mel), melanocytic nevi (nv) and vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc).

More than 50% of lesions are confirmed through histopathology (histo), the ground truth for the rest of the cases is either follow-up examination (follow_up), expert consensus (consensus), or confirmation by in-vivo confocal microscopy (confocal). The dataset includes lesions with multiple images, which can be tracked by the lesion_id-column within the HAM10000_metadata file.


### Method

Convolutional Neural Networks architectures:

AlexNet: AlexNet has 8 layers consisting 5 convolutional and 3 fully-connected that was first CNN architecture to implement Relu as activation functions.

VGG-16: Very deep CNN built on AlexNet with 13 convolutional and 3 fully-connected layers. 

Inception: the inception network is designed to solve the salient parts of image and prevents overfitting.  The architecture limits the number of input channels by adding 1x1 convolution before 3x3 and 5x4 convolutions, and adds 1x1 convolution after 3x3 max pooling. It was 22 layers deep but the design is constantly evolved. 


### Evaluation Metrics

Accuracy, precision, recall, f1 score

### Conclusion

On-going

