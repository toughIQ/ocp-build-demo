# ocp-build-demo

https://docs.openshift.com/container-platform/4.7/cicd/builds/creating-build-inputs.html#builds-creating-secrets_creating-build-inputs
```
oc create secret generic dockerhub-toughiq --from-file=.dockerconfigjson=<path/to/.docker/config.json> --type=kubernetes.io/dockerconfigjson
```

```
oc secrets link builder dockerhub-toughiq
```
