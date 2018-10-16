# Azure Machine Learning

## Story

Cars R Us have invested in a new machine learning model to help them with pricing vehicles.

They have a simple web front end and a poorly trained Linear Regression pricing algorithm which has learnt its information from some sample car data they have.

The dealership could really use your help to get their web app into a Dev-Ops CI/CD pipeline, deploy their machine learning model and have the web app package itself up with the latest version of the model as currently it is cumbersome and fraught with difficulties when trying to do a release.

They have also realised that their model is not quite as accurate as it could be and they are certain they are losing money hand over fist.

It has also been requested a new model is trained up and deployed without adversely affecting their business.


## Tasks for participants

The initial task will be to get the Python Flask application (front end) into a Dev-Ops style pipeline.

This pipeline will need to connect to an Azure blob storage account to retrieve the latest version of the machine learning model and package it up with the application.

The model will then need to be enhanced so it is more accurate and then deployed back into blob storage.

Upon checking in any new code our pipeline should repackage the front end application along with the latest model in blob storage and deploy.

A follow up call should be performed to make sure the new model is in operation.
