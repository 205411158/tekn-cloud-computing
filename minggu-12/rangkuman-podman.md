# Docker Depricated in Kubernetes, What about Podman?

In Shot , what it mmeans here is that Docker does not support Kubernetes Runtime API alled CRI (Container Runtime Interface).

Kubernetes people have been using a bridge service called "dockershim".

It converts Docker API and CRI, but it will no longer be provided from Kubernetes side within a few minor releases.

In short : Design of Docker is not well-perfect use when running at Kubernetes.

![Gambar 1](./podman01.png)

## Podman: A tool for managing OCI containers and pods

Podman (the POD MANager) is a tool for managing containers and images, volumes mounted into those containers, and pods made from groups of containers.
Podman is based on libpod, a library for container lifecycle management that is also contained in this repository. The libpod library provides APIs for managing containers, pods, container images, and volumes.
