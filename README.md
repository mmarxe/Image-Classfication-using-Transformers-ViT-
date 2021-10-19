# Image Visual Transformers

![image](https://user-images.githubusercontent.com/47692036/137953299-40c1507a-f55b-46d3-a864-e4943c4ade61.png)
All changes and reviews go to this repository.

Training the model can take days with the Colab GPUs. Thus constant updates will be made to the repository to the improving accuracy and metric.

The PCA Implementation is used for dimensionality reduction. A single image consists of about 3072 pixels however after reeduction it is compressed to only 202 pixels.

![image](https://user-images.githubusercontent.com/47692036/137953383-e118a7cc-9964-457a-8736-33715b07bec0.png)

However a clearer view of the image shows its texture has not changed as much. The goal of this is to improve the training of the transformer by reducing training time. It will also go a long way to reducing computational resources.

Most of the heavy work had already been done by the Keras team implementing the 16 by 16 paper. Little change in preliquisite variables has been done and most of the heavy work was incorporating the PCA into the model. 

However the colab is to improve the accuracy achieved by their model by dimensionality reduction.
