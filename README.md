```
docker build --no-cache -f dockerfile.nginx -t tsukisama9292/llamaindex:nginx-rolling .
docker run -t -d tsukisama9292/llamaindex:nginx-rolling
```
```
docker build --no-cache -f dockerfile.redis -t tsukisama9292/llamaindex:redis-rolling .
docker run -t -d tsukisama9292/llamaindex:redis-rolling
```