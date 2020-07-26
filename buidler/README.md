## Dockerfile.buidler

### build image

```powershell
docker build `
  --file /_share/dockerfiles/Dockerfile.buidler `
  --force-rm `
  --tag image--buidler `
  .
```

### run container

```powershell
docker run `
  --name buidler `
  --rm `
  -it `
  -v /_share/buidler:/root/workspace `
  image--buidler /bin/bash
```
