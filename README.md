# camel-jbang-pipeline
Demo Pipeline to deploy Camel YAML


camel run github:predic8:camel-jbang-pipeline:csv-json.camel.yaml

camel ps --watch

camel get
camel get route
camel top
camel log
camel trace
camel cmd
camel get services
camel get health
camel hawtio
camel catalog component
camel doc jackson
camel dependency list

camel version list

camel cmd send --body=file:payload.json --endpoint=mqtt mqtt

camel cmd send --poll --endpoint='activemq:cheese'