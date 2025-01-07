# demo2_k8soperator_golang

Demo application containing Kubernetes (K8s) Operator solution in pure Golang. 

# Prerequisites

- [Go](https://golang.org/dl/)
- [Helm](https://helm.sh/docs/intro/install/)
- [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [Kind](https://kind.sigs.k8s.io/docs/user/quick-start/)
- [Docker](https://docs.docker.com/get-docker/)
- [Kustomize](https://kubectl.docs.kubernetes.io/installation/kustomize/)
- [Kubebuilder](https://book.kubebuilder.io/quick-start.html#installation)
- [taskfile](https://taskfile.dev/#/installation)

# Getting Started

1. Install the prerequisites
   
   On Windows platform, you can use [Chocolatey](https://chocolatey.org/install) to install the prerequisites.

    ```text
    choco install kubernetes-cli -y
    where kubectl
    kubectl version --client
    
    choco install kubectx -y
    where kubectx
    kubectx --version
    
    choco install kubens -y
    where kubens
    kubens --version
    
    choco install kubernetes-helm -y
    where helm
    helm version
    
    choco install kind -y
    where kind
    kind version
    
    choco install kustomize -y
    where kustomize
    kustomize version
   
    choco install make -y
    where make
    make --version
    ```

    If you ever need to upgrade the version of kubectl, you can use the following command:
   
    ```text
    choco upgrade kubernetes-cli kubectx kubernetes-helm kind kustomize make -y
    ```

   Under the WSL Linux platform, install `operator-sdk`.

   ```text
   curl -L -o kubebuilder https://github.com/kubernetes-sigs/kubebuilder/releases/download/v4.3.1/kubebuilder_linux_amd64
   chmod +x kubebuilder
   sudo mv kubebuilder /usr/local/bin/kubebuilder
   which kubebuilder
   kubebuilder version
   ```

1. Clone the repository

   ```bash
   git clone
   ```
