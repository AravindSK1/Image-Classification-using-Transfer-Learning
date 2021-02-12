# Image-Classification-using-Transfer-Learning

Identifying the type of skin cancer at an early stage is critical, so that treatment could be taken at the earliest. Our objective is to identify the type of skin cancer which will save a lot of time and efforts taken to review each and every report manually. Usually, training of neural networks for automated diagnosis of pigmented skin lesions is hampered by the small size and lack of diversity of available dataset of dermatoscopic images. We are going to tackle this problem by data augmentation. In the light of this objective, we seek to derive a general analysis and modeling approach to predict diagnostic category of skin lesions.

Questions to address:
o The goal of this project is to leverage deep neural nets to develop an automated diagnosis of skin cancer from dermoscopic images.
o Reducing the time and cost constraints required in diagnostic tests with just a picture from any device

Methodology:
Based on the images, the objective is to predict in which of the following seven categories the lesion images fall under Melanocytic nevi, Melanoma, Benign keratosis-like lesions, Basal cell carcinoma, Actinic keratoses, Vascular lesions, Dermatofibroma using various CNN architectures

Data: https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000
o Count - 10015
o Resolution – 600x450

Relevant Software:
o Programming Languages: Python
o Libraries: keras, Tensorflow, matplotlib, Scikit-Learn

Reference Paper:
1. Classification of Skin Lesion by Interference of Segmentation and Convolution Neural Network. Authors: Mobeen ur Rehman ; Sharzil Haris Khan ; S M Danish Rizvi ; Zeeshan Abbas ; Adil Zafar Published in: 2018 2nd International Conference on Engineering Innovation (ICEI)
2. Deep Ensemble Learning for Skin Lesion Classification from Dermoscopic Images Authors: Ahmed H. Shahin ; Ahmed Kamal ; Mustafa A. Elattar Published in: 2018 9th Cairo International Biomedical Engineering Conference (CIBEC)

References: 1. https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000 2. https://www.researchgate.net/profile/Li_Jia_Li/publication/221361415_ImageNet_a_Large-Scale_Hierarchical_Image_Database/links/00b495388120dbc339000000/ImageNet-a-Large-Scale-Hierarchical-Image-Database.pdf 3. https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53 4. https://ml-cheatsheet.readthedocs.io/en/latest/backpropagation.html
