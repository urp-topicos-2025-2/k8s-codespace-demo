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
# instalar aplicacion en kubernetes
```
kubectl apply -f deploy/apps/deployment.yaml
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

# Docker - Generar imagen de contenedor
```
docker build -t myusuariodockerhub/backend-python:v1.0.0 .

docker build -t myusuariodockerhub/frontend-python:v1.0.0 .
```

# Docker Registry - Autenticar a registry
docker login -u myusuariodockerhub

# Docker - Tag de imagen existente
docker tag backend-python:v1.0.0 myusuariodockerhub/backend-python:v1.0.0

# Docker - Subir imagen a registry
docker push clasesurp2/backend-python:v1.0.0
docker push clasesurp2/frontend-python:v1.0.0
