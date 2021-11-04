# zipkin-opentelemetry

Run `mvn liberty:run` in the root directory.

In another terminal, run `docker run --rm -d -p 9411:9411 --name zipkin openzipkin/zipkin`

Navigate to http://localhost:9080/dev/system/properties

Navigate to http://localhost:9411/zipkin to see the traces
