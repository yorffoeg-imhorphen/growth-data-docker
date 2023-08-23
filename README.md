# growth-data-docker
Program allowing the processing of data from image acquisition during the monitoring of plant development. This program is available as a Docker via the following link: https://hub.docker.com/r/yorffoeg/growth_data_images.
You can find help on installing the program in the description on the Docker Hub page and in the readme file named ReadmeDockerHub.

This program allows the user to select the regions of interest, extract measurements from the depth images, calculate different features from the curves obtained, and finally make predictions on the development stages of the plants. Predictions are made using convolutional neural networks, in the form of labels ranging from 0 to 3 inclusive and meaning:
- 0 : Soil
- 1 : Germination
- 2 : Opening of the cotyledons
- 3 : Appearance of the first leaf

This program was designed by the Imhorphen team working at INRAE in Angers (France). Four people participated in its development:

- Programming : Couasnet Geoffroy
- Testing / modification: Mercier Félix
- Deep Learning algorithm: Garbouge Hadhami
- Management: David Rousseau
