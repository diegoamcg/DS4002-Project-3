# DS4002-Project-3

## Section 1: Software and platform section
In this project, we used Python in Rivanna, UVA's High-Performance-Computer, allowing us to run with more memory and cpus to run our model faster. To complete exploratory data analysis, we used pandas, numpy, seaborn, and matplotlib. For our analysis, we used Pytorch, specifically EfficientnetB0, a pretrained Pytorch model that allows us to run our model with higher accuracy and faster response. 

## Section 2: Map of Documentation
- DATA
  - Data Appendix PDF
  - NOTE: To download data, go to this website and download the data manually: https://astronn.readthedocs.io/en/latest/galaxy10.html#download-galaxy10-decals
- OUTPUT
  - Confusion_Matrix.png
  - Galaxy_Classification_Images.png
  - grad_cam_1.png
  - grad_cam_2.png
  - grad_cam_8.png
- SCRIPTS
  - EDA.ipynb
  - MI3_Project3_Model.ipynb
- LICENSE.md
- README.md

## Section 3: Instructions for Reproducibility
1. Download data from website
2. Create an instance on Rivanna or personal computer with at least 8 GB of memory, GoogleColab will not be sufficient for this model
3. Add data to same directory MI3_Project3_Model.ipynb is in.
4. Run through notebook, making any modifications desired to number of epochs, fine tuning, etc.
5. Analyze accuracy, Grad-Cam, and Confusion Matrix.
