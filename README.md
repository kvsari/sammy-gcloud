Sammy gCloud
===

[Kubernetes](https://kubernetes.io/) deployment for [sammy](https://gitlab.com/kvsari/sammy) project on [google cloud](https://cloud.google.com/).


# Components

# Useful commands

To apply a .yaml file.
```console
kubectl apply -f <filename>
```

To connect to a pod running a single container.
```console
kubectl exec -ti <pod-name> bash
```

Inside the command line of the `postgres` pod. To connect to psql;
```console
psql -U postgres -W sammy_trade_history
```
