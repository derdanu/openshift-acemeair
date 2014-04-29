# OpenShift Acme Air Sample

This project contains both the application source and server config as expected by the [Liberty OpenShift cartridge][]. When creating an application, specify this repository as the initial URL and then add a PostgreSQL cartridge to the application.

To use a different type of relational database, update pom.xml and server.xml.

To load data into the database, go to http://appname-dev.openshift.local/rest/api/loader.

Try New York to Paris for a flight with a lot of options to pick from.


[Liberty OpenShift cartridge]: https://github.rtp.raleigh.ibm.com/mtpeters-us/liberty-cartridge