# node-docker-html-starter
Basic docker set up with node html and express

# Build Docker Image
# docker build -t node-docker-html-starter .

if the build is successful
Check image
# docker images

Image will be availbale on the docker image list

# docker run node-docker-html-starter, 
will start the app but server wont respond to local:8080
instead run
# docker run -d -P --name demo1 node-docker-html-starter 
   --demo1 is the name
# docker ps -a


