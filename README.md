# observability is no longer actively maintained by VMware, Inc.

# Steeltoe App Observability

This is a collection of different ways to monitor a running app using Steeltoe Cloud Management and Distributed Tracing. Each folder is named after the platform used for observability. Within, you will find the needed configurations and docker assets. While the examples are docker driven and aimed at running locally, you should be able to also use platforms like Kubernetes with ease.

## Observability Platforms

### Tanzu Application Service

Something about TAS. [Learn more](https://tanzu.vmware.com/application-service) about the VMware Tanzu Application Service.

### Wavefront

Something about wavefront. [Learn more](https://wavefront.com) about Wavefront by VMware.

### Grafana

Something about grafana. [Learn more](https://grafana.com) about Grafana.

<!-- ## Security

The endpoints each have a specific configuration where their information can only be retrieved from within the prviate network. Don't be alarmed if you try one of the endpoints only to be greeted with a 404. The idea is to access the data from the dashboard, which servse as the only entry point to the private network. -->

## Scaling

The configuration(s) are very friendly to a cloud environment where app instances come & go. Feel free to experiment with scaling the application `docker-compose scale steeltoe-app=3`.