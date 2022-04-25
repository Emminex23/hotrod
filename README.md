# Hot R.O.D. - Rides on Demand

This demo is based on the Jaeger Hotrod demo [hotrod-tutorial]

![image](https://user-images.githubusercontent.com/906471/151587572-56d39bc2-c20f-4d87-85b8-7bc7859ac52f.png)


## Running

### Run everything in Kubernetes

Decide on a namespace in which things are to run and then run

```sh
kubectl -n "${NAMESPACE}" apply -f k8s/pieces
```

To uninstall:

```sh
kubectl -n "${NAMESPACE}" delete -f k8s/pieces
```
