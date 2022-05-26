# deluge_helm
Deluge torrent client helm chart.

**deluge_helm**

## installing an deluge_helm

Install deluge service with the following commands:

```
git clone https://github.com/AlexVinet/deluge_helm.git
cd deluge_helm/deluge/
helm install deluge -f values.yaml .
```

# You need to modify the pv.yaml and pvc.yaml with your own config.