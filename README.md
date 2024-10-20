## MathPredictor : End to End Machine Learning Project

This is a ML application using ci cd pipelines and github action using container registry and Azure web app

## Run from the terminal

docker build -t testdockerkrish.azurecr.io/mltest:latest .

docker login testdockerkrish.azurecr.io

docker push testdockerkrish.azurecr.io/mltest:latest

