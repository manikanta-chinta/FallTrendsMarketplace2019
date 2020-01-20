# Project Infrastructure Setup on AWS

## Step 1:
Create S3 bucket and folders for training and testing datasets - https://docs.aws.amazon.com/AmazonS3/latest/user-guide/create-bucket.html

## Step 2:
Create lambda function to be auto triggered when ever new file comes to S3 test folder and perform data cleaning and wrangling before passing it to sagemaker for predictions - https://docs.aws.amazon.com/lambda/latest/dg/getting-started-create-function.html

## Step 3:
Creat sagemaker notebook instance for running the model and link it to the s3 bucket created above to save the model in and also to upload and download the training and testing datasets and accuracy and psi values - https://docs.aws.amazon.com/sagemaker/latest/dg/gs-setup-working-env.html

## Step 4:
Create a quicksight dashboard and link to the s3 bucket created above to display the data distributions, psi and accuracy values - https://docs.aws.amazon.com/quicksight/latest/user/example-create-a-dashboard.html

