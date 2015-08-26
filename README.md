# unblibraries/jdk
Docker container : Serves as a base container for java services. Leverages phusion/baseimage.

## Usage
This container serves little purpose on it's own, rather as the base for other images - e.g. [unblibraries/elasticsearch](https://registry.hub.docker.com/u/unblibraries/elasticsearch/).

```
FROM unblibraries/jdk:oracle8
...
```

## License
- unblibraries/jdk is licensed under the MIT License:
  - http://opensource.org/licenses/mit-license.html
- Attribution is not required, but much appreciated:
  - `JDK Docker Container by UNB Libraries`
