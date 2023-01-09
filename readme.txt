

http://localhost:8088
docker build . -t composetest

docker run -p 0.0.0.0:3000:3000 -d composetest
