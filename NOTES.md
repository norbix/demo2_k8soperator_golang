# Info

```text
# Create a `kind` cluster
kind create cluster --name dev
kubectl cluster-info --context kind-dev
kubectl get nodes

# Delete the `kind` cluster
kind delete cluster --name dev



# Create a new project
kubebuilder init --domain norbix.io --repo github.com/norbix/demo2-k8soperator-golang --project-name demo2-k8soperator-golang


```