# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-udr_1.3_amd64.rock docker-daemon:sdcore-udr:1.3
docker run sdcore-udr:1.3
```