# Kubernetes MinIO
 Deploy MinIO to Kubernetes

## Install

We have MinIO and MinIO Client. Configure your options ( See [here](https://github.com/helm/charts/tree/master/stable/minio#configuration) for full list of option ) and run :

```shell
helm install minio -f helm-values.yml stable/minio
```

* Enable `Ingress` and access MinIO Browser from [http://minio.local](http://minio.local)
* Login using `accessKey` and `secretKey` that defined in `helm-values.yml`
