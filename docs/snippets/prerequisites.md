## Prerequisites

Before installing Knative, you must meet the following prerequisites:

- **For prototyping purposes**, Knative will work on most local deployments of Kubernetes. For example, you can use a local, one-node cluster that has 2 CPU and 4GB of memory.

    !!! tip
        You can install a local distribution of Knative for development use by following the [Getting started guide](../../../../getting-started/){_blank}.

- **For production purposes**, it is recommended that:
    - If you have only one node in your cluster, you will need at least 6 CPUs, 6 GB of memory, and 30 GB of disk storage.
    - If you have multiple nodes in your cluster, for each node you will need at least 2 CPUs, 4 GB of memory, and 20 GB of disk storage.
- You have a cluster that uses Kubernetes v1.18 or newer.
- You have installed the [`kubectl` CLI](https://kubernetes.io/docs/tasks/tools/install-kubectl/).
- Your Kubernetes cluster must have access to the internet, since Kubernetes needs to be able to fetch images. To pull from a private registry, see [Deploying images from a private container registry](../../../../serving/deploying-from-private-registry).

!!! caution
    The system requirements provided are recommendations only. The requirements for your installation may vary, depending on whether you use optional components, such as a networking layer.
