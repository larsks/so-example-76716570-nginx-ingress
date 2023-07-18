This is part of <https://stackoverflow.com/a/76717119/147356>.

## To deploy this example

Create your target namespace:

```
kubectl create namespace mynamespace
```

Deploy the resource into your namespace:

```
kubectl -n mynamespace apply -k .
```
