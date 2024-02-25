# Image-Enhancer-using-CGAN

Designed a custom Conditional Generative Adversarial Network(CGAN) trained over 13k Human Face images.
<br><br>
The images were first blurred using multiple randomized Image Augmentation techniques such as Guassian Blur, Salt & Pepper noise, etc. I've used these images for training the model to predict the actual de-noised images.
<br><br>
This Conditional Generative Adversarial Network (CGAN) implementation in TensorFlow can be used to enhance a degraded image. The model takes around 6-8 hrs to train on a GPU when the dataset is around 9000 images and will take longer on a larger dataset.
<br><br>
Below is the sample, where Left image is the Blurred image and the Right one is the model predicted de-noised output.

![](https://github.com/DeathReaper0965/Image-Enhancer-using-CGAN/blob/master/data/image-enhancer-gan.png)

Made with ❤️ by Praneet Pabolu
