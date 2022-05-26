# deluge_helm
Deluge torrent client helm chart.

**deluge_helm**

## installing an deluge_helm

Install deluge service with the following commands:

```
git clone https://github.com/AlexVinet/deluge_helm.git
cd deluge_helm/deluge/
Modify the pv and pvc
helm install deluge -f values.yaml .
```

>\*\*Note: You need to modify the pv.yaml and pvc.yaml with your own config.\*\*