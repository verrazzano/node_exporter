# Build Instructions

The base tag this release is branched from is `v1.0.0`

---
## Build

`docker image build -f ./Dockerfile_verrazzano -t <docker-image-repo>/node-exporter:1.0.0-1 .`

## Push to OCIR

`docker image push <docker-image-repo>/node-exporter:1.0.0-1`
