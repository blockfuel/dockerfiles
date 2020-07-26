## Dockerfile.rsv-v2

### build image

```powershell
docker build `
  --file /_share/dockerfiles/Dockerfile.rsv-v2 `
  --force-rm `
  --tag image--rsv-v2 `
  .
```

### run container

```powershell
docker run `
  --name rsv-v2 `
  --rm `
  -it `
  -v /_share/rsv-v2:/root/com.github/reserve-protocol/rsv-v2 `
  image--rsv-v2 /bin/bash
```
