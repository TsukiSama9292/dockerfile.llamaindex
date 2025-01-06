## 清理
```bash
docker builder prune -f
docker image prune -f
docker system prune -f
```
## nginx
```bash
docker build --no-cache -f dockerfile.nginx -t tsukisama9292/server:llamaindex-nginx-rolling .
docker push tsukisama9292/server:llamaindex-nginx-rolling
```
## redis
```bash
docker build --no-cache -f dockerfile.redis -t tsukisama9292/server:llamaindex-redis-rolling .
docker push tsukisama9292/server:llamaindex-redis-rolling
```