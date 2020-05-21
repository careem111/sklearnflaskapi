[![CircleCI](https://circleci.com/gh/careem111/sklearnflaskapi.svg?style=svg)](https://circleci.com/gh/careem111/sklearnflaskapi)

skleanflask

This sklearnflask is a Machine Learning Microservice API model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. for more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing).

How To Run The Python Scripts

run the kubernetes file
  - ./run_kubernetes.sh
  
run the prediction script
  - make_prediction.sh
 
 Description of Files
 
 Make file - To prepare the environmet (installing dependencies , linting docker file)
 requirements.txt - python packages to be installed
 Docker file - To build a docker image
 run_docker.sh - Instructions to built docker image and container
 upload_docker.sh - Upload the docker image to docker hub
 run_kubernetes.sh - create kuberenetes pods locally and run
 app.py - flask application
 make_prediction.sh - script to test the application
 
 

