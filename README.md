# EKS_terraform_istio
Setting up an EKS cluster using terraform and installing istio and deploying the simple app

# Istio:

![image](https://user-images.githubusercontent.com/126230874/222130346-1886cdd6-d657-4c3e-95e5-33e94ce50946.png)

A service mesh is a dedicated infrastructure layer that you can add to your applications. It allows you to transparently add capabilities like observability, traffic management, and security, without adding them to your own code

Istio is an open source service mesh that layers transparently onto existing distributed applications. Istio’s powerful features provide a uniform and more efficient way to secure, connect, and monitor services. Istio is the path to load balancing, service-to-service authentication, and monitoring – with few or no service code changes. Its powerful control plane brings vital features, including

* Secure service-to-service communication in a cluster with TLS encryption, strong identity-based authentication and authorization
* Automatic load balancing for HTTP, gRPC, WebSocket, and TCP traffic
* Fine-grained control of traffic behavior with rich routing rules, retries, failovers, and fault injection
* A pluggable policy layer and configuration API supporting access controls, rate limits and quotas
* Automatic metrics, logs, and traces for all traffic within a cluster, including cluster ingress and egress

# Objectives:
* Setub EKS Cluster
* Installing the Istio in the setup EKS cluster
* Deploying Addons
* Deploying the basic app
