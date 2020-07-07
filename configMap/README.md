# configMap commands
$ kubectl create configmap nginx-config --from-file=nginx-proxy.conf

$ kubectl get configmap

$ kubectl get  configmap nginx-config -o yaml

$ kubectl exec -it nginx-deployment-c64948fdd-bgzz6 -c nginx -- bash

$ kubectl exec -it nginx-deployment-c64948fdd-bgzz6 -c nodejs -- bash

URL: http://localhost:31002
