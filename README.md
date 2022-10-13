# UNET_from_scratch
This project is the implementation of the UNET architecture from scratch using PyTorch.

UNET is an architecture used for image segmentation and uses only the convolution operation and no fully connected layers. We can have as many masks for as many classes in the output layer of the UNET architecture. The original project seems to have been inspired from the RESNET paper as it also uses residual connections in between the layers where the sizes are same. The upsampling and the downsampling portion as almost symmetric and so forms a "U" like structure and so the name UNET.
