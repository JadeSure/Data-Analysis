This is a docker version for house price prediction.

relative blog about docker [link](https://jadesure.github.io/2020/12/30/Docker-Introduction/)
a easy way build environment in the Docker by Dockerfile with run code:
docker build -t lala:1.0 --build-arg path:'file saved path/.'
. is my working folder which contains the model code, training and test datasets, python dependent packages and Dockerfile. Path is the variable which will be used in the Dockerfile.

docker push/pull for put/download file from/to docker hub.
