# Docker Nodejs App


## Getting Started
### To run the project:  

1. Clone the project:  
`$ sudo git clone https://github.com/deepak41/docker-nodejs-app.git`  

2. Go to root folder of project & build the docker image:   
`$ sudo docker build . -t deepak661/nodejs-web-app`  

3. Run a container from the image:   
`$ sudo docker run -p 45045:8080 -d deepak661/nodejs-web-app`  

3. Test the app:   
`$ curl -i localhost:45045`  

The app should be up and running. 


### To upload the image to docker hub:  

1. Login into docker hub from terminal:  
`$ sudo docker login -u "username" -p "password" docker.io`  

2. Upload the image to docker hub:   
`$ sudo docker push deepak661/nodejs-web-app`  
