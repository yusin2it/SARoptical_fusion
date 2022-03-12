# SARoptical Applications
## SAR-Optical Feature Fusion
The effective combination of the complementary information provided by huge amount of unlabeled multi-sensor data (e.g., Synthetic Aperture Radar (SAR) and optical images) is a critical issue in remote sensing. Recently, contrastive learning methods have reached remarkable success in obtaining meaningful feature representations from multi-view data. However, these methods only focus on image-level features, which may not satisfy the requirement for dense prediction tasks such as land-cover mapping. In this work, we propose a self-supervised framework for SAR-optical data fusion and land-cover mapping tasks. SAR and optical images are fused by using a multi-view contrastive loss at image-level and super-pixel level according to one of those possible strategies: in the early, intermediate and late strategies. For the land-cover mapping task, we assign each pixel a land-cover class by the joint use of pre-trained features and spectral information of the image itself. Experimental results show that the proposed approach not only achieves a comparable accuracy but also reduces the dimension of features with respect to the image-level contrastive learning method. Among three fusion strategies, the intermediate fusion strategy achieves the best performance.
## Methods
![Image text](https://github.com/yusin2it/SARoptical_fusion/blob/main/img_sources/Method.jpg)
## Results
![Image text](https://github.com/yusin2it/SARoptical_fusion/blob/main/img_sources/comparison_of_methods.jpg)
## Training
python train_XX.py

## Unsupervised SAR-Optical Segmentation

