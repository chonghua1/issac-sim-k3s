# issac-sim-k3s
This project provide the detailed step of deploy issac-sim in k3s cluster.

## Prerequisites
Install the NVIDIA Container Toolkit

For instructions on installing and getting started with the NVIDIA Container Toolkit, refer to the [Installtion guide](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html).

Install the k3s cluster, refer to [k3s Installtion](https://docs.k3s.io/quick-start)

## Enabling GPU Support in Kubernetes

Once you have configured the options above on all the GPU nodes in your cluster, you can enable GPU support by deploying the Daemonset nvidia-deivce-plugin.yml

## Deploy the k3s pod


