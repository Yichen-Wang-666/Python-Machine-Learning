## CODE DESCRIPTION
#### Autoencoders to build

Stacked 784 - 392 - 196 - 392 - 784 (tied weights or not)

Convolutional Encoder (conv, maxpool, conv, maxpool, conv, maxpool).

Decoder (conv, upsample2d, conv, upsample2d, conv, upsample2d, conv)
