Verify Docker Installation
docker version

Log in to Docker Hub
docker login

Pull Image from Docker Hub
docker pull jhaggar/dotnet-docker-working:latest

Run the docker image
docker run -d -p 8080:80 jhaggar/dotnet-docker-working