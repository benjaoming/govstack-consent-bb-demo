# GovStack Consent BB - demo
A stand-alone Docker and Kubernetes configuration simulating the Consent BB specification.

## Running the demo

The demo can be run on a local Docker environment using the following command:

```
docker-compose up
```

## Components of the demo

* An HTTP server (Caddy)
* The Consent BB OpenAPI spec
* A Caddy module for validating OpenAPI specs (caddy-openapi)
* Mocked static responses for static endpoints
* A demo application written in Django for dynamic endpoints
