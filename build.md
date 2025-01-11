## Build image to arm64 and amd64

```
docker buildx build --platform linux/amd64,linux/arm64 -t cgalvisleon/postgis:12.3.5 -f ./12-3.5/Dockerfile --push .
docker buildx build --platform linux/amd64,linux/arm64 -t cgalvisleon/postgis:13.3.5 -f ./13-3.5/Dockerfile --push .
docker buildx build --platform linux/amd64,linux/arm64 -t cgalvisleon/postgis:13.3.5 -f ./14-3.5/Dockerfile --push .
```
