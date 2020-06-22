# Medical-Imaging-Computer-Vision-Project

Our team pursued the development of high-accuracy classifiers with reduced recall rate using deep learning algorithms, as well as boundary box annotation of mammography x-rays.

We use a clean version of the dataset found in Kaggle which utilizes data from the Digital Database for Screening Mammography (DDSM) and CBIS-DDSM datasets. The data has been preprocessed and downsized from 598x598 to 299x299 image resolution, focusing on the region of interest. The dataset contains over 55k training images where ~86% are negative samples and ~14% are positive samples. The data was stored as tfrecords files for TensorFlow.

We pursued four different models to improve recall: 

1. VGG16/VGG19
2. ResNet
3. UNet
4. Transfer learning (using VGG)

The repository contains the results presentation and notebook used to create our results. Data files are excluded for size purposes.

This project was completed in Spring 2019 with collaborators Yajaira Gonzalez, Christoph Muus, Matthew Stewart, and Claire Stolz.
