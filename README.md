# miriconf-helm-chart

This repo stores and publishes the miriconf server helm chart. To add this helm repo run 

```
helm repo add miriconf https://miriconf.github.io/miriconf-helm-chart/
```

you can install the miriconf server for example by running 

```
helm install -n miriconf miriconf-server miriconf/miriconf-server
```
