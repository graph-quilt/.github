# Graph Quilt 

Graph Quilt is an open architecture from Intuit Inc. for creating a unified graph that aggregates and combines multiple 
GraphQL APIs. 

Please take a look at the [GraphQL Conference presentation](https://graphql.org/conf/schedule/17f150667d13a57f28bae524443f4c60/?name=The%20evolution%20of%20the%20GraphQL%20Orchestrator%20powering%20Intuit%20Consumer%20Apps) or watch the video below.

Graph Quilt Gateway is a unified API aggregation layer that exposes data from multiple sources through a single
GraphQL endpoint. It aggregates and combines schemas from dynamically registered sources at runtime 
into a single GraphQL schema. It will split all incoming queries into multiple sub-queries, 
orchestrate these sub-queries to appropriate data providers and aggregate providers’ responses into a 
single response before returning it to the client.

[Get started](https://graph-quilt.github.io)

![](https://github.com/graph-quilt/.github/blob/main/profile/images/arch/graph-quilt-gateway.png)

Watch the video 

[![Watch the video](https://img.youtube.com/vi/pDkvA5KKFw4/maxresdefault.jpg)](https://youtu.be/pDkvA5KKFw4)
