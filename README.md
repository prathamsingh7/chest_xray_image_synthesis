# Leveraging GANS for Chest X-Ray image synthesis

## Keywords: 
Chest X-ray image, Synthetic data generation, Generative Adversarial Networks (GANs), Auxiliary Classifier GAN (ACGAN), Imbalanced dataset, Auxiliary Classifier Wasserstein GAN (ACWGAN)

## Abstract: 
In the last few years, Deep learning has emerged as a transformative tool in medical diagnostics offering advanced and reliable findings. Medical imaging plays a pivotal role in diagnostic tasks, yet the scarcity of labeled data and privacy concerns pose significant challenges for leveraging deep learning techniques in this domain. This research addresses the data scarcity issue in medical image analysis by encouraging class-conditioned image synthesis. Synthetic images, generated using Generative Adversarial Networks (GANs), enhance the development of deep-learning models for medical imaging tasks, benefiting patients and healthcare providers. For this purpose, we employ the Auxiliary Classifier GAN(ACGAN)frameworkwhichfacilitates the generation of labeled images. Despite the promising capabilities of ACGAN, challenges persist, particularly in scenarios with imbalanced datasets. To solve this issue and improve overall image quality, we utilize the Auxiliary Classifier Wasserstein GAN (ACWGAN) approach. ACWGAN enhances the image quality while also ensuring that the generated images adequately represent minority classes, crucial for accurate diagnostic tasks. Through extensive experimentation and evaluation, we demonstrate the effectiveness of the ACWGAN approach in synthesizing high-quality, labeled chest X-ray images. Furthermore, we train a ResNet-based CNN model to showcase the importance of auxiliary classifiers in both ACGAN and ACWGAN frameworks for ensuring accurate classification of synthesized images. 

This research compares its result with the following paper: https://ieeexplore.ieee.org/document/10032429

## Objectives: 
1. Explore GANs for generating realistic chest X-ray images to overcome data scarcity in medical imaging.
2. Assess the effectiveness of ACGANs for producing labeled chest X-ray images crucial for classification tasks.

## Project Workflow
https://github.com/prathamsingh7/chest_xray_image_synthesis/blob/main/images/Project_workflow.png