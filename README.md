# Helm charts for KubeVPN server

## Install with default mode
```shell
helm install kubevpn kubevpn/kubevpn -n kubevpn --create-namespace
```
in China you can use tencent image registry

```shell
helm install kubevpn kubevpn/kubevpn --set image.repository=ccr.ccs.tencentyun.com/kubevpn/kubevpn -n kubevpn --create-namespace
```

## AWS Fargate cluster
```shell
helm install kubevpn kubevpn/kubevpn --set netstack=gvisor -n kubevpn --create-namespace
```
