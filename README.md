# deluge_helm
Deluge torrent client helm chart.

**deluge_helm**

## installing an deluge_helm

Install deluge service with the following commands:
>You need to install [nfs.csi.k8s.io](https://github.com/kubernetes-csi/csi-driver-nfs) driver to use NFS before proceeding with the deluge installation, or use your own nfs driver.
```
git clone https://github.com/AlexVinet/deluge_helm.git
cd deluge_helm/deluge/
Modify the pv.
helm install deluge -f values.yaml .
```

>\*\*Note: You need to modify the pv.yaml with your own config.\*\*