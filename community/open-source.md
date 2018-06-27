If you have created (or know of) an open source library or product that
uses CloudEvents, please include in the list below.

* [CloudEvents.NET](https://github.com/aliencube/CloudEvents.NET): is a .NET
  implementation of the CloudEvents [spec](../spec.md) and
  [HTTP transport binding](../http-transport-binding.md). It has been released to
  [nuget.org](https://www.nuget.org/packages?q=Aliencube.CloudEventsNet).
  It also contains some app
  [samples](https://github.com/aliencube/CloudEvents.NET/tree/master/sample)
  of 1) console app to Web API, and 2) Web API to Azure Event Grid, which
  demonstrates how CloudEvent messages are generated and sent to Web API and
  Azure Event Grid over HTTP.
* [microBean CloudEvents](https://microbean.github.io/microbean-cloudevents/):
  CloudEvents represented as plain Java objects. Satellite projects add
  [Jackson and CDI event integration](https://microbean.github.io/microbean-cloudevents-jackson-cdi).
* [jCloudEvents](https://github.com/project-streamzi/jcloudevents):
  Java POJO implementation of the CloudEvents specification and some CDI bindings.
* [Strombrau Gateway](https://github.com/project-streamzi/event-gateway):
  Vert.x based gateway routing CloudEvent metadata to internal Apache Kafka topic
* [Event Gateway](https://github.com/serverless/event-gateway):
  It's dataflow for event-driven, serverless architectures. The Event Gateway combines both API Gateway and Pub/Sub functionality into a single event-driven experience.
* [CloudEvents Extend API](https://github.com/goextend/cloudevents-extend-api) is a JavaScript programming model for [Extend](https://goextend.io) which allows handling Cloud Events.
* [CloudEvents Verify](https://github.com/btbd/CEVerify):
  is a tool to help verify CloudEvents according to the proper specifications. It is currently being hosted publicly [here](http://soaphub.org/ceverify).