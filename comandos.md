# CLI Kubernetes
```
kubectl
```

# listar los nodos del cluster
```
kubectl get nodes
```

# listar todos los pods en todos los namespaces
```
kubectl get pod --all-namespaces
```

# listar todos los namespaces
```
kubectl get namespaces
```

# listar todos los pods en el namespace "apps"
```
kubectl get pod -n apps
```

# listar todos los deployments en el namespace "apps"
```
kubectl get deployments -n apps
```

# instalar k9s
```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    echo >> /home/vscode/.zshrc
    echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> /home/vscode/.zshrc
    source /home/vscode/.zshrc
```
# k9s
```
 brew install derailed/k9s/k9s
```
