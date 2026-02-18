
#run app 
node app.js

#build docker image
docker build -t nodejs-helloworld .
docker build -t nodejs-helloworld:latest .

kubectl get nodes

kubectl describe node docker-desktop

