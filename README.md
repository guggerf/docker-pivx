# PIVX wallet for docker

Docker image that runs the pivx daemon which can be turned into a staking wallet with the correct configuration.

All credits go to guggero! If you like this image, buy him a coffee ;) DGuggerovpXAZcsUT2sMtcGNSwrjTudFEE

## Quick Start (daemon/staking)

```text
docker run \
  -d \
  -v /home/username/crypto/pivx:/pivx \
  -p 51472:51472 \
  --name=pivx \
  guggerf/pivx
```
