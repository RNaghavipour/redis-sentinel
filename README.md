# Redis-Sentinel
Deploy a HA Redis on your k8s cluster.

**Note**: These manifests deployed in a cluster created by Kind, so before installing change some sections;
i.e. volumeClaimTemplate in Redis StatefulSet manifest according to your storage provisioner.

## Installation
In the cloned directory run:
``` kubectl apply -f . ```
