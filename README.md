## IMAGE COLORISATION USING DEEP LEARNING

A deep learning convolution approach to color grayscale images.

The entire model consists of two networks **colorization network** and the **classification network.**

## Classification Network
It uses **a pre trained VGG16** network to obatin an embedding or the classification of what is present in the image.
It helps to give realistic colors to the images.

## Colorisation Network
It uses an **Encoder Decoder** type of convolution network to colorise the images by downsampling it and then upsampling it.

