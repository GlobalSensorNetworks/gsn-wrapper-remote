# gsn-wrapper-remote

Wrapper to connect to GSN 1.x from 2.x

## installation

* get the jar file from the release (or build it yourself with "mvn package")
* copy the jar file to /usr/share/gsn-core/lib
* edit the file /etc/gsn-core/wrappers.properties and add "remote-rest=gsn.http.rest.RestRemoteWrapper" at the bottom.
* restart gsn-core

