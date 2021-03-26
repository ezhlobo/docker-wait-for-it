# docker-wait-for-it

It's based on Alpine image that simply copies `master` of https://github.com/vishnubob/wait-for-it.

How to use:

```bash
docker run --rm ezhlobo/wait-for-it <...>

# e.g.
docker run --rm ezhlobo/wait-for-it google.com:80

# await service from docker-compose
docker run --rm --network compose_app_default ezhlobo/wait-for-it db:80
```
