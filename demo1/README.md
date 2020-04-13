# Demo 1

- create `demo` namespace: `kubectl apply -f ./namespace.yaml`
- check if the namespace is created: `kubectl get ns`
- create alipne pod: `kubectl apply -f ./alpine.yaml`
- check if the pod is running: `kubectl get po -n demo`
- clean up: `kubectl delete -f pod.yaml; kubectl delete -f namespace.yaml`
