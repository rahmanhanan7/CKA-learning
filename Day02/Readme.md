### What is a Namespace in Kubernetes

- Provides isolation of resources
- Avoid accidental deletion/modification
- Separated by resource type or environment or domain and so on
- Resources can access each other in the same namespace with their first name by the DNS name for other namespaces
- IPs of pods are cluster-wide and the IPs can be called anywhere from the cluster
- To use domains, use FQDN
