## Jellyfin with rFFmpeg
This images extend the official [Jellyfin](https://jellyfin.org) [docker images](https://hub.docker.com/r/jellyfin/jellyfin) with [rFFmpeg](https://github.com/joshuaboniface/rffmpeg) support.

The rFFmpeg binary is located at `/usr/local/bin/rffmpeg`.

You need to mount your rFFmpeg configuration to `/etc/rfmpeg/rffmpeg.yml`.

For more information on rFFmpeg and configuration instructions take a look at the [project's repository](https://github.com/joshuaboniface/rffmpeg)!