Docker is a company
Mostly used for running your code in an isolated environment
Install docker gui via official docker website depending on your system requirement

Commands 
1) Docker run -> it runs the image by fetching it from docker repository  
docker run -p(port) (from) 27017: (to) 27012 mongo -> port mapping
docker run -d(detached mode) -p(port) (from) 27017: (to) 27012 mongo -> detached mode

2) Docker ps -> shows containers running in my system similar to ls -a
3) docker kill - kills the container
4) docker run -e password=password -p(port) (from) 27017: (to) 27012 mongo
