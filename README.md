# docker-isc-kea
Docker image of ISC Kea DHCP server built on [Alpine Linux](https://alpinelinux.org/). This a fork of [tcely/docker-isc-kea](https://github.com/tcely/docker-isc-kea)'s efforts, with the following modifications:

* Optional support for [Kea Premium Hook Library](https://www.isc.org/product/kea-premium-hook-library-kea-1-3-package/) _(add licensed tarball to build directory prior to building)_
* Remove Cassandra library _(not needed in my environment)_
* Define EXPOSE ports
* socat added for testing Kea API
