# Convolutional Neural Network (CNN) O



The CNN architecture is composed of:

- **Convolutional Layers (ConvLayers):** These layers apply convolution operations to capture spatial hierarchies of features in the input data, such as images. Each convolution operation involves sliding a small filter (kernel) over the input and computing dot products.

- **Pooling Layers:** Used for downsampling spatial dimensions and reducing computational complexity. Max pooling, a common technique, retains the maximum value in a region.

- **Padding:** Applied to input data to preserve information at the borders during convolution and pooling operations. It prevents the reduction of spatial dimensions too quickly.

- **Strides:** Represent the step size taken by filters during convolution or pooling. Larger strides reduce spatial dimensions, while smaller strides preserve more spatial information.

- **Flatten Operation:** Before fully connected layers, a flatten operation is applied to convert the multi-dimensional tensor into a one-dimensional vector. This operation is crucial for transitioning from convolutional or pooling layers to fully connected layers.


## Animations for CNN

https://deeplizard.com/resource/pavq7noze3

https://deeplizard.com/resources
