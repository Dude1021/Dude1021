# Welcome To Nacos wiki home

Nacos(official site: http://nacos.io) is committed to helping you discover, configure, and manage your microservices. It provides a set of simple and useful features enabling you to realize dynamic service discovery, service configuration management, and service and traffic management. 

Nacos makes it easier and faster for you to build, deliver and manage a microservices platform . It is the infrastructure that supports a service-centered modern application architecture which adopts a microservices or cloud-native approach.

## What is Nacos？

Service is a first-class citizen in Nacos. Nacos supports discovering, configuring, and managing almost all types of services:

[Kubernetes Service](https://kubernetes.io/docs/concepts/services-networking/service/)
[gRPC](https://grpc.io/docs/guides/concepts.html#service-definition)
[ | Dubbo RPC Service](https://dubbo.incubator.apache.org/#/?lang=en-us)
[Spring Cloud RESTful Service](https://spring.io/understanding/REST)

Key features of Nacos:

* **Service Discovery And Service Health Check**

    Nacos supports both DNS-based service discovery and RPC-based (Dubbo/gRPC) service discovery. After a producer registers a service with [native sdk TODO](xx), [OpenAPI TODO](xx), or [a dedicated agent TODO](xx), a consumer can discover the service with either [DNS TODO](xx) or [HTTP TODO](xx).
    
    Nacos provides real-time health check to prevent services from sending requests to unhealthy hosts or service instances. Nacos supports both transport layer (ping or tcp) health check and application layer (such as http, redis, MySQL, and user-define) health check. For the health check of complex clouds and network topologies(such as VPC, Edge Service etc), Nacos provides both agent mode and server mode. Nacos also provide a unity service health dashboard to help you manage the availability and traffic of services.    
    
* **Dynamic configuration management**

    Dynamic configuration service allows you to manage the configuration of all applications and services in a centralized, externalized and dynamic manner across all environments.

    Dynamic configuration eliminates the need to redeploy applications and services when configuring updates.

    Centralized management of configuration makes it more convenient for you to achieve stateless services and elastic expansion of service instances on-demand.

    Nacos provides an [easy-to-use UI TODO](xx) to help you manage all of your configurations. It provides some out-of-box features including  configuration version tracking, canary release, configuration rollback, and client configuration update status tracking to ensure the security and control the risk of configuration management. 

* **Dynamic DNS service**

    Dynamic DNS service which supports weighted routing makes it easier for you to implement mid-tier load balancing, flexible routing policies, traffic control, and simple DNS resolution services in your production environment within your data center. Dynamic DNS service makes it easier for you to implement DNS-based Service discovery. 

    Nacos provides some simple [DNS APIs TODO](xx) for you to manage your DNS domain names and IPs.

* **Service governance and metadata management**

    Nacos allows you to manage all of your services and metadata from the perspective of a microservices platform builder. This includes managing service description, life cycle, service static dependencies analysis, service health status, service traffic management，routing and security rules, service SLA, and first line metrics.

* [Check more features ...](xx)

## Nacos landscape

![nacos_landscape.png](https://cdn.yuque.com/lark/0/2018/png/15914/1530514380550-31251a79-02bb-4155-bc4f-5a9f436551a2.png) 