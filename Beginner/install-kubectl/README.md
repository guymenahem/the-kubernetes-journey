# Install kubectl

```mermaid
    flowchart TD;
    install-kubectl(<b> MUST - Install kubectl </b>)
    install-kubectl --> install-nice-to-have

    install-nice-to-have(Install nice to have tools)
    install-nice-to-have --> kubectl-autocompletion
    install-nice-to-have --> kubectl-kubectx-kubens
    install-nice-to-have --> k9s
    install-nice-to-have --> kubectl-aliases

    kubectl-autocompletion(NICE TO HAVE - Install kubectl autocompletion) --> next-create-a-cluster

    kubectl-kubectx-kubens(NICE TO HAVE - Install kubectx and kubens) --> next-create-a-cluster

    k9s(NICE TO HAVE - Install k9s) --> next-create-a-cluster

    kubectl-aliases(NICE TO HAVE - Install kubectl aliases) --> next-create-a-cluster

    next-create-a-cluster(NEXT - Create a cluster)
```

## Install kubectl
- [install kubectl - Kubernetes official documentation](https://kubernetes.io/docs/tasks/tools/#kubectl)


## Recommended Tools
- [kubectl auto completion setpup](https://kubernetes.io/docs/tasks/tools/included/optional-kubectl-configs-bash-linux/)
- [kubectx + kubens - Switch between contexts and namespace easily](https://github.com/ahmetb/kubectx)
- [k9s - terminal UI to interact with your Kubernetes clusters](https://github.com/derailed/k9s)
- [kubectl-aliases - premade kubectl aliases](https://github.com/ahmetb/kubectl-aliases)
