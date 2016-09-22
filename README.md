# Resilio sync(Bittorrent sync) on Docker

## Usage

Edit your
  * `rslsync.conf`
  * `ports` and `volumes` in `docker-compose.yml`

```shell
docker-compose up -d
```

## Notice

* ID and password of WUI are confirmed at the initial access
* Be careful of configuration consistency(e.g. port, path)
