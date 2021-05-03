# BELOW STEPS TO PERFORM IN ORDER TO RUN THIS APP USING DOCKER 


Clone the repo 

git clone https://github.com/mohit3wadhwa/docker-ready-python-flask-app.git

cd docker-ready-python-flask-app.


Start running below DOCKER commands


Build the image using the following command

$ docker build -t docker-ready-python-flask-app:latest .


Run the Docker container using the command shown below.

$ docker run -dp 5000:5000 docker-ready-python-flask-app


Once all above get completed, look for http://localhost:5000/ in any of your broswer. 
