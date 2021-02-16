# Interpolation-of-Images
The two notebooks cover interpolation for upscaled and a radomly sampled image.
The first notebook covers reconstruction of a randomly sampled image using scipy.interpolate.griddata with varying number of available samples to observe the the quality of reconstructed images.
The second notebook covers Bi-Linear interpolation algorithm and interpolation using various filter windows such as hamming, hanning, rectangular and blackmann harris window. Also the quality of upscaled images using different interpolation types provided by cv2.imresize() has also been compared in terms of PSNR and SSIM
