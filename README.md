# Canola-min
Project folder for Metapolator with minimal set of the Canola font (for UI development purpose)


# create canola.mp from scratch

The source UFO used for import is located in the repository [metapolator/Canola-full](https://github.com/metapolator/Canola-full/)

Follow the steps described in [metapolator/Canola-full/README.md](https://github.com/metapolator/Canola-full/blob/master/README.md) but change the path to `canolaSource.ufo` accordingly.


```bash
$ mom import -g `cat subset.txt` ../Canola-full/canolaSource.ufo canola.mp/base-regular
```
