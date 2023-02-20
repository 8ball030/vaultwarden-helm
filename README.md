# vaultwarden
Helm chart for deploying [dani-garcia/bitwarden_rs](https://github.com/dani-garcia/vaultwarden) in Kubernetes.


```bash
helm repo add bitwarden https://raw.githubusercontent.com/8ball030/vaultwarden-helm/master/
helm install bitwarden bitwarden/vaultwarden
```

OR

```console
$ git clone https://github.com/8ball030/vaultwarden-helm
$ cd vaultwarden
$ helm install bitwarden ./chart/vaultwarden-helm
```


## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm install my-release bitwarden/vaultwarden
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
$ helm delete my-release
```



