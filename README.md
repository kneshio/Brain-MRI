**Alzheimer MRI Classification**

Alzheimer MRI Classification: 6400 MRI belong to 4 different classes: Non Demented (3200), Very Mild Demented (2240), Mild Demented (896), Moderate Demented (64) 

The pretrained EfficientNet-V2 B3 model was used. Although the dataset is imbalanced, without data augmentation, 100% train accuracy, 98.8% validation accuracy and 98.1% test accuracy were achieved.  

** Kaggle Brian Tumor MRI Images 44 Classes **

The dataset includes 4479 T1, contrast-enhanced T1, and T2 magnetic resonance images labeled as astrocytoma (580), carcinoma (251), ependymoma (150), ganglioglioma (61), germinoma (78), glioblastoma (204), granuloma (78), medulloblastoma (131), meningioma (874), neurocytoma (457), oligodendroglioma (224), papilloma (237), schwannoma (465), and tuberculoma (145).

Class Activation Maps (CAM) is used to highlight the critical image regions influencing classification and identify the tumor locations. When the pretrained EfficientNet-V2 B3 model was used, the test accuracy 93.3% can be achieved with samplewise normalization and AdamW optimization and 97.0% can be achieved with featurewise normalization and Adam optimization. 

