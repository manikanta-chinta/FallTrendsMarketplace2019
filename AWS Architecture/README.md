# Architecture

![flow-v2](https://media.github.umn.edu/user/15286/files/babac900-1c31-11ea-8442-672bcb279417)

sagemaker_s3 ipynb file shows the code required to link an s3 bucket to a sagemaker model for file downloading and uploading.

The intitial part of the code represents the training phase of the predictive model and the 2nd part represents the prediction on all 6 data sets (1 normal and 5 skewed) and the psi calculation function.

The final step is to upload the accuracy and the psi files to S3.
