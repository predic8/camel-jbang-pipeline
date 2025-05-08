# camel-jbang-pipeline
Demo Pipeline to deploy Camel YAML

# run

docker run -it -p 8080:8080 ghcr.io/predic8/camel-jbang-pipeline

curl -v -X POST -d "foo" http://localhost:8080/a
