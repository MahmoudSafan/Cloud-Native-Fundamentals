# DOCKER COMMAND
### first Navigate to main folder where docker file and project stored
#### then run this commands
1. docker build -t node-helloworld .
2. docker tag node-helloworld mahmoudsafan2/node-helloworld:v1.0.0
3. docker login
4. docker push mahmoudsafan2/node-helloworld:v1.0.0

#### to run an local image use command
* docker run mahmoudsafan2/node-helloworld:v1.0.0

#### to run an web based image
* docker run -d -p portNumber:portNumber nameOfImage