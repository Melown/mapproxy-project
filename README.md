# Initial project configuration for VTS-Mapproxy

[VTS-MapProxy](https://github.com/melown/vts-mapproxy) 
is a HTTP server that converts non-VTS resources (raster or vector) to VTS
resources (surface, boundlayer, freelayer) on the fly.

In this project, you will get configuration files, which do define the server
itself: `mapproxy.conf` and also resources file, with configuration of surface
resources and overlay (bound) layers.

You can run the server and browse the resources using the command

```
mapproxy mapproxy.conf
```

For more information about how to install and configure VTS-Mapproxy, please
referer to [official documentation](http://melown.readthedocs.io/en/latest/).
