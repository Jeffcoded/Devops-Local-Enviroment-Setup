# Tools Setup Verification Report

## Overview
The report below shows the DevOps tools installed and tested in my Ubuntu 26.04.1 LTS environment

## Verification Results

| Tool       | Versions | working Status|
| ---------- | ------: | --------- |
| Git        |  2.53.0 | ✅ Working |
| Docker     |  29.7.2 | ✅ Working |
| kubectl    |  1.37.0 | ✅ Working |
| Minikube   |  1.38.1 | ✅ Working |
| Kubernetes |  1.35.1 | ✅ Working |
| Terraform  |  1.16.0 | ✅ Working |
| Ansible    |  2.20.1 | ✅ Working |
| AWS CLI    | 2.31.35 | ✅ Working |
| Azure CLI  |  2.90.0 | ✅ Working |
| Helm       |  4.2.4 | ✅ Working |

## Docker Verification

Docker was tested with:

```bash
docker run hello-world
A successful setup message was received, confirming Docker was working correctly


## Docker Verification
Minikube was successfully started using Docker.

```bash
minikube status

Result:

```text
host: Running
kubelet: Running
apiserver: Running
kubeconfig: Configured

The Kubernetes node was also verified:

```bash
kubectl get nodes
```

Result:

```text
NAME       STATUS   ROLES           VERSION
minikube   Ready    control-plane   v1.35.1

##Final Remark
All required tools were successfully set up and verified in the Ubuntu 26.04.1 LTS environment
