# Spatio-Temporal SAR-Optical Data Fusion for Cloud Removal via a Deep Hierarchical Model

Authors: Alessandro Sebastianelli, Erika Puglisi, Maria Pia Del Rosso, Jamila Mifdal, Artur Nowakowki, Fiora Pirri, Pierre Philippe Mathieu and Silvia Liberata Ullo

## Dataset:
The dataset collects roughly 8000 S1 and 8000 S2 images or 2000 S1 and 2000 S2 time-series of 4 images. Each image has a shape of 256 X 256 pixels; for the S1 images only the VV polarisation has been considered, resulting in a matrix with a shape of 256 X 256 X 1 ; for the S2 the red, green and blue bands have been considered, resulting in a matrix with a shape of 256 X 256 X 3, and an extra matrix with a shape of 256 X 256 X 1 for the cloud mask (QA60 band).

The dataset has been created using our tool proposed in: Sebastianelli, A., Del Rosso, M. P., & Ullo, S. L. (2021). Automatic dataset builder for Machine Learning applications to satellite imagery. SoftwareX, 15, 100739.


Part 1:

- https://drive.google.com/drive/folders/1Y8647SFRBS4l5-YK75yz4WyzAx8K4Kou?usp=sharing
- https://drive.google.com/drive/folders/16cF49ZMUn1ROTIxdaH9u74xSs6oqHE2o?usp=sharing

Part 2:

https://drive.google.com/drive/folders/1Af_V8uY-OAtW4O_L_doSlPsmpueZdd11?usp=sharing

## Note
### The code is splitted in multiple Jupyter Notebooks, we are currently refining it to make the code cleaner and more readable.

## Papers
- Sebastianelli, A., Nowakowski, A., Puglisi, E., Del Rosso, M. P., Mifdal, J., Pirri, F., ... & Ullo, S. L. (2021). Sentinel-1 and Sentinel-2 Spatio-Temporal Data Fusion for Clouds Removal. arXiv preprint arXiv:2106.12226. https://arxiv.org/abs/2106.12226 
