<h1 align="center">
    <img src="Gloo-01.png" alt="Gloo Events SDK" width="200" height="242">
  <br>
</h1>


<h3 align="center">Gloo Events SDK</h3>
<BR>

Gloo is a function gateway built on top of the [Envoy Proxy](https://www.Envoyproxy.io). Gloo provides a unified entry point
for access to all services and serverless functions, translating from any interface spoken by a client to any interface
spoken by a backend. Gloo aggregates REST APIs and events calls from clients, "glueing" together services in-cluster, 
out of cluster, across clusters, along with any provider of serverless functions.

This Repo 
----

This repository contains the SDK library for Gloo integrations. Currently the only integration supported is a library for
emitting [CloudEvents](TODO). For writing Gloo clients, see [gloo-storage](https://www.github.com/solo-io/gloo-storage), the 
Gloo API Client in Go. 

For information about emitting events to the Gloo Gateway, see our [documentation](https://gloo.solo.io). 

Documentation
-----

Get started by reading our docs here: [https://gloo.solo.io/](https://gloo.solo.io/)

Community
-----
Join us on our slack channel: [https://slack.solo.io/](https://slack.solo.io/)

