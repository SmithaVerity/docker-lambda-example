# docker-lambda-example

sudo docker build -t lambda-example .


sudo docker run -d -p 9000:8080 lambda-example


curl -XPOST "http://localhost:9000/2015-03-31/functions/function/invocations" -d {}
