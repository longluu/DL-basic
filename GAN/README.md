# DL-GAN-basic
 Some basic GAN models. Most are from Tensorflow tutorial with some modifications.
 
- DCGAN: GAN with convoluational layers. Also make a GIF of how image generation from the same seeds progresses over time. Use cifar-10 (original is MNIST).
 
- GAN_pix2pix: conditional GAN that takes in an image of house outline and output an image of the house. Preprocessing pipeline that resize, crop and jitter the images. Use TensorBoard.
 
 - Cyclegan-Unet: similar to conditional GAN but does not require pair samples, only 2 sets of samples. New: introduce cycle consistency loss and identity loss. Note that the implementation is different from original paper (Unet for generator).
 
 
 
