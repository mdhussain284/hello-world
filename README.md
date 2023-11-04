# hello-world
## to create secret uisng kubectl command
```
kubectl create secret docker-registry regcred \
  --docker-email=<your gmail address> \
  --docker-username=user1 \
  --docker-password=pass@1234 \
  --docker-server=my-registry.example:5000
```
