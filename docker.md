- Remove dangling docker images ([Source](https://github.com/moby/moby/issues/32811#issuecomment-372386752))
```
docker rmi $(docker images -q --filter "dangling=true")
```
