# Docker Nodejs App


## Getting Started
### To run the project:  

1. Clone the project

2. Build the docker image:   
`$ sudo docker build . -t deepak661/nodejs-web-app`  

3. Run a container from the image:   
`$ sudo docker run -p 45045:8080 -d deepak661/nodejs-web-app`  

3. Test the app:   
`$ curl -i localhost:45045`  

The app should be up and running. 
