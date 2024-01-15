# OVARIAN CANCER CLASSIFICATION
 
We are presenting a CNN approach using two convolutional networks to classify histology images in a patchwise fashion. The first network, receives overlapping patches (35 patches) of the whole-slide image and learns to generate spatially smaller outputs. The second network is trained on the downsampled patches of the whole image using the output of the first network. The number of channels in the input to the second network is equal to the total number of patches extracted from the microscopy image in a non-overlapping fashion (12 patches) times the depth of the feature maps generted by the first network (C): 

