# Project List
- [Transfomer From Scratch](#transformer-from-scratch)
- [Image Inpainting](#image-inpainting)
- [Text Style Transfer](#text-style-transfer)
- [3D reconstruction from single RGB image](#3d-reconstruction-from-single-rgb-image)

## Transformer From Scratch

**Description** : This is a learning oriented project. Tranformers are the state of the art text processing models (Used as a base in all major Large Language Models (LLMs) such as GP T(ransformer) 1,2,3,4, Bard, Llama, Claude, etc). This project is an attempt to understand the transformer architecture and its working. The project is divided into 3 parts 
- Start by learning the very basics of Standard neural networks, backpropagation, tuning and optimizations, etc.
- Then move to the basics of Processing sequential/text data using RNNs,LSTMs, understand their usecases, drawbacks and the need of transformers.
- Finally we understand the working of transformers and implement a `text-completion model` using it from scratch.

The final model we train will not be close to the current SoTA models (due to limited data and compute) but you'll gain a thorough understanding of the transformer architecture and its working so you can contribute to the real-world Transformer research.

**Pre-Requisites** : Strong Python and C++ programming.

**Resources** : [Sequence Models-Andrew NG](https://www.coursera.org/learn/nlp-sequence-models/),      [Original Transformer Paper-Attenion is All you need](https://arxiv.org/abs/1706.03762),      [Neural Networks-Andrej Karpathy](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)

**Difficulty** : Medium

**Mentor** : Labib Asari


## Image Inpainting

**Description** : The Image Inpainting project offers a unique opportunity to dive deep into the realm of image processing and deep learning. Inpainting is the process of filling in missing or corrupted parts of an image, restoring its visual integrity. This project is divided into two exciting stages, where you’ll not only learn the fundamentals but also gain hands-on experience with both traditional and cutting-edge inpainting techniques.

Stage 1: Hands-on Implementation of OpenCV Inpainting Algorithm
FIrst things first since this is a computer vision project, knowledge of basics of computer vision is a must. Here you will be allowed to explore different computer vision techniques and are expected to complete tasks related to them. In this stage, you will explore the OpenCV library and implement traditional inpainting algorithms. You will grasp the underlying concepts and techniques, and apply them to restore images with missing portions. This stage serves as a strong foundation for understanding the core principles of inpainting.

Stage 2: Deep Learning Implementation of Image Inpainting
Building upon your knowledge from the first stage, you will dive into the exciting world of deep learning. You will design and implement a neural network for image inpainting using state-of-the-art techniques. This stage empowers you to leverage the power of artificial intelligence to produce visually appealing and contextually accurate inpainted images.

**Pre-requisite** : Computer Vision, Deep learning, Python

**Resources** : [Image-Inpainting Paper](https://arxiv.org/pdf/2104.01431.pdf), [Edge-Connect](https://github.com/knazeri/edge-connect), [OpenCV-Inpainting tutorial](https://docs.opencv.org/3.4/df/d3d/tutorial_py_inpainting.html).

**Difficulty** : Medium

**Mentor** : Dhruvanshu, Om




## Text Style Transfer

**Description** : Text Style Transfer is a task of transferring the style of one text to another. For example, if we have a text in an informal style, we can transfer it to a formal style while preserving the context. These tasks is very useful in many applications such as machine translation, text summarization, etc. 
In this project, we will be implementing a text style transfer model using the Transformer architecture. The exact style-combinations will be decided as we go along the project.
Example : https://quillbot.com/

**Pre-Requisites** : Strong Python programming, experience in NLP/Deep Learning is preferable.

**Resources** : [awesome-list for Text-Style-Transfer](https://github.com/jiangqn/Text-Style-Transfer), [StyleFormer](https://github.com/PrithivirajDamodaran/Styleformer) 

**Difficulty** : Hard

**Mentor** : Labib Asari




## 3D reconstruction from single RGB image

**Description** : The "Three-Dimensional Reconstruction from a Single RGB Image" project focuses on the field of computer vision and 3D reconstruction. The goal of this project is to develop algorithms and techniques that can take a single RGB image as input and generate a plausible 3D representation of the scene depicted in the image. This involves extracting depth information, estimating the shape of objects, and creating a 3D model that closely resembles the original scene. Through the project, you will embark on an enriching learning journey. You will develop a strong grasp of fundamental deep learning principles, encompassing neural networks, loss functions, and optimization. The project will immerse you in diverse computer vision techniques, from image processing to depth estimation methods. Domains explored in the project would be Computer Vision, Machine Learning, Geometry and 3D Modeling, Image-to-Depth Conversion.

**Pre-Requisites** : Strong Python programming, experience in Deep Learning is preferable.

**Resources** : [Three-Dimensional Reconstruction from a Single RGB Image
Using Deep Learning](https://www.mdpi.com/2313-433X/8/9/225), [Pixel2Mesh](https://github.com/nywang16/Pixel2Mesh/tree/master) 

**Difficulty** : Hard

**Mentor** : Soham Mulye
