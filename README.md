# h2gis-geoserver

Is an extension to use H2GIS with Geoserver at least the 2.8.X series.

Note that h2gis-geoserver uses the H2GIS Geotools driver available at https://github.com/orbisgis/h2gis-geotools

 
### Install

In a terminal, run

```bash
$ mvn clean install
```

* Go to your target folder, select the h2gis-gs-XX.jar and copy-paste it to the WEB-INF/lib directory of your GeoServer installation.
* In your target folder, go to plugin-dep that contains all dependencies. Select all jars and copy-paste it to the WEB-INF/lib directory of your GeoServer installation.
* Restart GeoServer

### Use

Read the step by step tutorial available on the [WIKI page] (https://github.com/orbisgis/h2gis-gs/wiki)




