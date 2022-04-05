# ADWMF
The program is about the adaptive dynamically weighted median filter. It includes two stages: the noise detection and noise removal. It is mainly used to removal the impulsive noise in images.

The input should be pbm image.
The output will be the original grayscale image, the noise-adding image, the noise-removal image by ADWMF and original MF. These four images would be stored in a output dictionary.
PSNR is used to evaluate their performance.
