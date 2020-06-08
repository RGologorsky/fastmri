# Checkpoints

This folder stores working versions of notebooks for easy reference.

- 02_kspace_classifier_real : 
	- classifies real images (28x28 MNIST, 10 categories, digits 0-9)
	- trains in image space and kspace
	- includes plots of digits in kspace 
	- No data augs.

- 03_kspace_classifier_real_imagenette :
	- classifies real images (128x128 Imagenette, 10 categories, church, parachute, etc)
	- trains in image space and kspace 
	- includes plots of images in kspace
	- No data augs apart from the RandomCrop presize to 128x128.