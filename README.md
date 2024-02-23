# py-aws-layers
Python packages in a file to s3 bucket that can be used by lambda layers.

Simply list the python packages you want installed in AWS in the requirments.txt file

The main.yaml Upload Python Packages to S3 Github Action pipeline will build the python module, and store it in an S3 bucket. 

The problem this solves is that Lambda functions require you to upload python modules to use them, this is very time consuming. By using this Continous Delivery pipeline, you can list multiple modules in the requirments.txt file and rest assured that they will be available to your Lambda function!

NOTE - you must set some env variables for it to run!
