sudo docker build -t exercise .
docker run -v $(pwd)/output:/output exercise

