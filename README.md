# tensorflow-flask
## Mount ML model to the docker
* sudo docker run -p 8501:8501 --name:pets -v "/home/rhyme/Desktop/app/pets/:/models/pets/1" -e MODEL_NAME=pets tensorflow/serving
