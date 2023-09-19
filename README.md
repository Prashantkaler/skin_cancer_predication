# skin_cancer_predication
# Diagnosis of Skin Cancer Using Machine Learning and Image Processing Techniques

## Description

This project focuses on the classification of skin lesions for the early detection of skin cancer using deep learning techniques.Skin lesions are abnormal growths in the epithelium layer of the skin, 
and there are nine primary types: Actinic Keratoses (AK), Basal Cell Carcinoma (BCC), Dermatofibroma (DF), Melanoma (MEL), Melanocytic Nevi (MV), Benign Keratosis (BK), Vascular Lesions (VASC),
Squamous Cell Carcinoma (SCC), and Pigmented Benign Keratosis (PBK).The project employs Convolutional Neural Networks (CNN) and specifically uses the ResNet-50 architecture for skin lesion classification.
Dermoscopic images, collected using digital devices like smartphones attached to lenses, are the primary data source. The dataset comprises over 25,000 skin lesion images obtained from Kaggle.
Using the ResNet-50 CNN model, this project has achieved an impressive 93% accuracy in skin cancer detection, surpassing previous work that achieved 73% accuracy using different models and considering 
only two types of skin lesions. In contrast, this project classifies nine types of skin lesions, including Actinic Keratosis, Basal Cell Carcinoma, Dermatofibroma, Melanoma, Melanocytic Nevi, Benign Keratosis,
Vascular Lesions, Squamous Cell Carcinoma, and Pigmented Benign Keratosis.
## Introduction

Skin lesions can arise from abnormal growth in the epithelium layer of the skin and are often indicative of skin cancer. Early diagnosis is crucial for effective treatment. 
Skin cancers like Basal Cell Carcinoma (BCC), Squamous Cell Carcinoma (SCC), and Melanoma (MEL) are particularly significant and can lead to severe complications if left untreated. 
This project primarily targets these serious skin cancers.The use of dermoscopic images, which visualize the skin's epidermis, enhances diagnostic accuracy. Deep learning models are 
employed to classify skin lesions effectively. The project utilizes a dermoscopic image dataset from Kaggle, containing over 25,000 images of various skin conditions. 
The ResNet-50 CNN model is chosen for its ability to address the vanishing gradient problem and is well-suited for classification tasks.

## Methodology

The project follows these steps:
1. Data collection: Dermoscopic images are collected and preprocessed, including adjustments for aspect ratio and resolution.
2. Dataset creation: A refined dataset is constructed.
3. Model development: A ResNet-50 CNN model is built and trained.
4. Testing and validation: The model's accuracy and performance are evaluated.
  
## Results and Discussion

The ResNet-50 model achieved an impressive accuracy rate of 93% in classifying skin lesions. This deep learning technique offers enhanced precision in skin disease diagnosis, reducing the risk of human error. 
The project uses Python programming and Jupyter Notebook for code execution and visualization.

### Skin Lesion Types
- Actinic Keratosis: Rough, scaly patches caused by sun exposure.
- Basal Cell Carcinoma: Commonly found on the head and neck, caused by UV radiation.
- Dermatofibroma: A benign fibrous histiocytoma.
- Melanoma: The most dangerous type, begins in melanin-producing cells.
- Melanocytic Nevi: Small, circular, and caused by abnormal skin pigmentation.
- Seborrheic Keratosis: Brown, oval growths on the face, chest, and back.
- Vascular Lesions: Reddish growths, often known as birthmarks.
- Squamous Cell Carcinoma: Grows large and can spread across the body, originating in squamous cells.

