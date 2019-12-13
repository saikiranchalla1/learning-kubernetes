# Part - 1: Introduction to Docker
1. Running your first docker container
2. Deploying a static website to the container
3. Building container images
4. Dockerizing a node.js application
5. Optimizing Docker Builds with OnBuild
6. Ignoring Files During Docker build
7. Creating Data Containers
8. Container Networking with Links and Networks
9. Persistent Data Volumes
10. Container Logging
11. Adding Metadata and Labels
12. Load balancing Containers
13. Monitoring containers with Prometheus
14. Using Grafana with Prometheus for Alerting and Monitoring

# Part - 2: Spinning Up a K8s Cluster
## Getting Started
1. Architecture of Kubernetes Cluster
2. Client Tools

## Provisioning Certificates
1. Why do we need CA and TLS Certs?
2. Provisioning the Certificate Authority
3. Generating Client Certificates
4. Generating the Kubernetes API server Certificate
5. Generating the Service Account key pair
6. Distributing the Certificate files
7. Lab: Creating a Certificate Authority and TLS Certificates for K8s

## Generating Kubernetes Configuration files for Authentication
1. Kubeconfigs
2. Generating Kubeconfigs for the cluster
3. Distributing the Kubeconfig files
4. Lab: Generating Kubeconfigs for a new K8s Cluster

## Generating the Data encryption config and key
1. What is Data encryption config in Kubernetes?
2. Generating the Data encryption config
3. Lab: Generating a data encryption config for Kubernetes
   
## Bootstrapping the etcd Cluster
1. What is etcd
2. Creating the etcd cluster
3. Lab: Bootstrapping an etcd Cluster for K8s

## Bootstrapping the Kubernetes Control Plane
1. Kubernetes Control plane
2. Control plane architecture
3. Installing Control plane Binaries
4. Setting up the Kubernetes API server
5. Setting up the Kubernetes COntroller Manager
6. Setting up the Kubernetes Scheduler
7. Enable HTTP Health Checks
8. Set up RBAC for Kubelet Authorization
9. Setting up a Kube API frontend load balancer
10. Lab: Bootstrapping a K8s control plane
11. Lab: Setting up a frontend load balancer for K8s API

## Bootstrapping the Kubernetes Worker nodes
1. Kubernetes worker nodes
2. Worker node architecture
3. Installing workder node binaries
4. Configuring Containerd
5. Configuring Kubelet
6. COnfiguring Kube-Proxy
7. Lab: Bootstrapping Kubernetes Worker Nodes

## Configuring kubectl for remote access
1. Kubernetes remote access and Kubectl
2. COnfiguring Kubectl for remote access
3. Lab: Configuring Kubectl to access a remote cluster

## Networking
1. The kubernetes networking model
2. cluster network architecture
3. installing Weave net
4. Cleanup
5. Lab: Setting up K8s networking with WeaveNet

## Deploying the DNS cluster Add-on
1. DNS in a Kubernetes Pod network
2. Deploying Kube-dns to the Cluster
3. Lab: Deploying kube-dns in a Kubernetes CLuster

## Smoke Test
1. Smoke testing the cluster
2. Smoke testing Data encryption
3. Smote testing deployments
4. Smoke testing port forwarding
5. Smoke testing Logs
6. Smoke testing Exec
7. Smoke testing Services
8. Smoke testing Cleanup
9. Lab: SMoke testing a kubernetes Cluster

# Part - 3: Certified Kubernetes Application Developer (CKAD)
## Core Concepts
1. Architecture
2. PODs and PODs with YAML
3. Replicasets
4. Deployments
5. Namespaces

## Configuration
1. Commands and Arguments in Docker
2. Environment variables
3. ConfigMaps
4. Secrets
5. Docker Security
6. Security Contexts
7. Service Account
8. Resource Requirements
9. Taints and Tolerations
10. Node Selectors
11. Node affinity
12. Taints & Tolerations Vs NodeAffinity

## MultiContainer PODs
1. Creating and Deploying Multi-Container PODS

## Observability
1. Readiness and Liveness Probes
2. Liveness Probes
3. Container Logging
4. Monitor and Debug applications

## POD Design
1. Labels, selectors and Annotations
2. Rolling updates and rollbacks
3. Jobs
4. Cronjobs

## Services and Networking
1. Services
2. Services - Cluster IP
3. Ingress Networking
4. Network Policies

## State Persistence
1. Volumes
2. Persistent Volumes
3. Persistent Volume Claims

## Certification Tips

# Part - 4: Monitoring K8s with Prometheus and Grafana
## Prometheus Architecture
1. Client Libraries
2. Exporters
3. Service Discovery
4. Scraping

## Run Prometheus on K8s
1. Setting up Prometheus
2. Configuring Prometheus
3. Setting up Grafana
4. NodeExporter
5. Adding a Grafana Dashboard

## Application Monitoring
1. Instrumenting Applications
2. Collecting Metrics from Applications

## PromQL
1. PromQL basics
2. PromQL Operations and Functions
3. Recording rules

## Alerting
1. Alertmanager
2. Alerting rules

# Part - 5: Helm, KNative, OPA, Vault
## Helm
1. What is Helm
2. Package Management in K8s
3. High level overview of Helm and Tiller
4. Installing Helm and Tiller
5. Chart in Helm

## KNative
1. Install knative
2. Deploy and App with Knative

## Vault
1. Installing Vault
2. Viewing the Vault UI
3. Using Vault for K8s Secrets

## OPA
1. Setting up OPA on K8s
2. Admission controller in K8s using OPA
