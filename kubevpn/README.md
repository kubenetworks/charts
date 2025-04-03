# Helm charts for KubeVPN server

## Install
```shell
helm install kubevpn kubevpn/kubevpn --set image.repository=ccr.ccs.tencentyun.com/kubevpn/kubevpn --set netstack=gvisor -n kubevpn --create-namespace
```
