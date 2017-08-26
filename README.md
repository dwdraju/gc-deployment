# Playing with Google Cloud Deployment Manager

### Create Deployment
```
gcloud deployment-manager deployments create my-first-deployment --config vm.yaml
```

### Describe Deployment
```
gcloud deployment-manager deployments describe my-first-deployment
```

### Check Deployment's Manifest
```
gcloud deployment-manager manifests describe manifest-[ID] --deployment my-first-deployment
```

### Delete Deployment
```
gcloud deployment-manager deployments delete my-first-deployment
```