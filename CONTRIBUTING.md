# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-udr_1.6.2_amd64.rock docker-daemon:sdcore-udr:1.6.2
docker run sdcore-udr:1.6.2
```