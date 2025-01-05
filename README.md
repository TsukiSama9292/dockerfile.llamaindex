```bash
docker build --pull --no-cache -f dockerfile.llamaindex -t tsukisama9292/server:llamaindex-rolling .
```
```bash
docker-compose up -d --pull always
```