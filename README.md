# Denoising-of-Synthetically-Noised-Images
 

This includes the code for Denoising of Synthetically Noised Images
Collected and prepared natural photos, and inserted various noises utilising Gaussian and Uniform distributions
• Implemented Convolutional Autoencoder, using 2 Convolutional Layers each in both encdoing and decoding stages
• Used Maxpooling2D to form encoded image and Upsampling2D to form the final decoded image of same size as input
• Achieved accuracy of 81% using optimizers such as Adadelta and Adam with loss function as Binary Cross Entropy
