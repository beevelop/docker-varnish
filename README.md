![GitHub Workflow Status](https://img.shields.io/github/workflow/status/beevelop/docker-varnish/Docker%20Image?style=for-the-badge)
![Docker Pulls](https://img.shields.io/docker/pulls/beevelop/varnish.svg?style=for-the-badge)
![Docker Stars](https://img.shields.io/docker/stars/beevelop/varnish?style=for-the-badge)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/beevelop/varnish/latest?style=for-the-badge)
![License](https://img.shields.io/github/license/beevelop/docker-varnish?style=for-the-badge)
[![GitHub release](https://img.shields.io/github/release/beevelop/docker-varnish.svg?style=for-the-badge)](https://github.com/beevelop/docker-varnish/releases)
![GitHub Release Date](https://img.shields.io/github/release-date/beevelop/docker-varnish?style=for-the-badge)
![CalVer](https://img.shields.io/badge/CalVer-YYYY.MM.MICRO-22bfda.svg?style=for-the-badge)
[![Beevelop](https://img.shields.io/badge/-%20Made%20with%20%F0%9F%8D%AF%20by%20%F0%9F%90%9Dvelop-blue.svg?style=for-the-badge)](https://beevelop.com)

# Varnish for Docker :whale:

```bash
# Launch any web container
docker run -d --name webapp tutum/hello-world

# Link "webapp" as "backend" to varnish and expose Port 80
docker run -d -p 80:80 --name varnish --link webapp:backend beevelop/varnish
```

## Configuration

- `VARNISH_CACHE_SIZE` (default: 128m)
- `BACKEND_PORT` (default: 80)
