## Abstract EN
### Cross Over: oAuth, openID and Kafka

"Apache Kafka ist the wild west without security." An Apache Kafka cluster is widely open by default. Anybody is allowed to create, write, consume or delete any topic.

Let's compare with HTTP-based distributed system: Authentication and authorization are uncovered there by default, as well.
To mitigate this, OAuth and OpenID Connect became a de-facto standard.

That's something we'd like to see in Kafka too.
This would be particularly important when Kafka is being integrated into an existing application landscape that already uses OpenID Connect. 
Instead of introducing a second security integration, we'd prefer to reuse a battle proofed OAuth server for authentication and authorization.

Wanted in the wild west: something to integrate a Kafka cluster with a central identity provider and access management solution.

Let's do some research :-)
We used a typical application as lab: monoliths & microservices in containers on Kubernetes forming an event driven distributed system.

We'll show different scenarios and results on a running application in this talk. 
Additionally, you'll see how HTTP communication based applications keep their security integration while using Apache Kafka as backbone.
