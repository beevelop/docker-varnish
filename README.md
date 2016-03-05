[![Travis](https://shields.beevelop.com/travis/beevelop/docker-varnish.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-varnish)
[![Docker Pulls](https://shields.beevelop.com/docker/pulls/beevelop/varnish.svg?style=flat-square)](https://links.beevelop.com/d-varnish)
[![ImageLayers Layers](https://shields.beevelop.com/imagelayers/layers/beevelop/varnish/latest.svg?style=flat-square)](https://links.beevelop.com/d-varnish)
[![ImageLayers Size](https://shields.beevelop.com/imagelayers/image-size/beevelop/varnish/latest.svg?style=flat-square)](https://links.beevelop.com/d-varnish)
[![GitHub release](https://shields.beevelop.com/github/release/beevelop/docker-varnish.svg?style=flat-square)](https://github.com/beevelop/docker-varnish/releases)
![Badges](https://shields.beevelop.com/badge/badges-7-brightgreen.svg?style=flat-square)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# Varnish for Docker :whale:

```bash
# Launch any web container
docker run -d --name webapp tutum/hello-world

# Link "webapp" as "backend" to varnish and expose Port 80
docker run -d -p 80:80 --name varnish --link webapp:backend beevelop/varnish
```

## Configuration
`VARNISH_CACHE_SIZE` (default: 128m)
`BACKEND_PORT` (default: 80)
