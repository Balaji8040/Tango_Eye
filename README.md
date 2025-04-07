# Tango_Eye
Person Clustering from Images using Deep Learning

This project implements an unsupervised pipeline to automatically group (cluster) images of the **same individual** using feature embeddings from a pretrained deep learning model (ResNet50) and **DBSCAN** clustering.


## 📁 Dataset

- Input: A folder of images of people captured "in the wild".
- Each image may depict a different person, or the same person in different conditions (angle, lighting, occlusion, etc.).
- Dataset is assumed to be extracted and stored in a single folder.



## 🚀 Features

- ✅ Feature extraction using `ResNet50` (pretrained on ImageNet).
- ✅ Clustering using `DBSCAN` (density-based clustering).
- ✅ Visualization of embeddings using PCA.
- ✅ Display of sample images from each detected cluster.


