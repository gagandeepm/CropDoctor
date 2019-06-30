# CropDoctor
A Spectral Data Processing Pipeline for Agriculture

I worked for a stealth mode agricultural startup using aerial Imaging to help farmers make data-driven decisions on how to manage their crops. I developed a data pipeline using AWS Lambda that creates a training dataset for their ML algorithms. The company flys planes and collects huge amount of spectral data over the farms that is analyzed to predict crop health. Every hour of imaging generates around 500 GB of spectral intensity data files which is available in binary format on AWS S3. The farmer also collects some ground truth data about the crops at certain locations. To create the training dataset the spectral data at the ground truth locations have to be retrived and used to calculate a quatity called reflectance that can use used to correlate to the ground truth measurements for the ML Algos. 


Project Summary slides
http://bit.ly/2X2c7Ow
