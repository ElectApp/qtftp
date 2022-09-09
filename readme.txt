This repository contains deprecated APIs which have been removed from Qt

Applications are recommended to port to the supported APIs.
However as some features are lost, these APIs are provided as standalone
source code for applications that require removed features.

Note: If you downloaded the source package from a hosting service
such as Gitorious, the package does not contain the generated headers
under the ./include directory. Before building, you'll need to generate
them manually by running the syncqt Perl script. For example:

cd qtftp
<QTDIR>/bin/syncqt.pl -version 5.1.0

Another method follow: https://blog.birost.com/a?ID=00350-e93b803f-47d7-43c2-9595-4468663170d0
