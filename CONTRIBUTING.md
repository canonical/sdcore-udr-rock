# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-udr_1.4.0_amd64.rock docker-daemon:sdcore-udr:1.4.0
docker run sdcore-udr:1.4.0
```