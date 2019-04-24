[//]: # (SPDX-License-Identifier: CC-BY-4.0)

## Nodejs Rest Server Hlem Kubernates

Step 1. Create namespace 

```
kubectl create namespace orgmtbcnodejs

```

Step 2. Run command on master node  



```
 helm install  nodeJsRestHelm/hl-fabric/ --name noderest --namespace orgmtbcnodejs -f  nodeJsRestHelm/hl-fabric/myvalues.yaml
```
