# Hysteria

## Desc

1. 通过 cert-manager.io 创建证书
2. 通过 LoadBalancer 端口转发

## Use

```bash
helm upgrade --install hysteria2-jp ./hysteria2 --namespace v2b -f values.jp.yaml
```
