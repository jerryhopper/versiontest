# versiontest



## JAVA 

[me@lqyr9301 ~]$ java -version

<code>java version "1.8.0_202"
Java(TM) SE Runtime Environment (build 1.8.0_202-b08)
Java HotSpot(TM) 64-Bit Server VM (build 25.202-b08, mixed mode)</code>

[my@debian ~]$ java -version

<code>openJDK 19.0.2 2023-01-17
OpenJDK Runtime Environment (build 19.0.2+7-Ubuntu-0ubuntu322.04)
OpenJDK 64-Bit Server VM (Build 19.0.2+7-ubuntu-0ubuntu322.04, mixed mode, sharing)</code>


## OPENSSL


[me@lqyr9301 ~]$ openssl version

<code>OpenSSL 1.0.1e-fips 11 Feb 2013</code>

[my@debian ~]$ openssl version

<code>OpenSSL 3.0.2 15 Mar 2022 (Library: OpenSSL 3.0.2 15 Mar 2022)</code>


## FILEBEAT

[ua1t9q8@lqyr9301 ~]$ /usr/share/filebeat/bin/filebeat --version

<code>filebeat version 5.3.0 (amd64), libbeat 5.3.0</code>



## TOMCAT

--TOMCAT--
[me8@lqyr9301 ~]$ sudo java -cp /opt/tomee/lib/catalina.jar org.apache.catalina.util.ServerInfo


[me@lqyr9301 ~]$ sudo java -cp ~tomcat/lib/catalina.jar org.apache.catalina.util.ServerInfo

<code>Server version: Apache Tomcat/7.0.63
Server built:   Jun 30 2015 08:08:33 UTC
Server number:  7.0.63.0
OS Name:        Linux
OS Version:     2.6.32-754.35.1.el6.x86_64
Architecture:   amd64
JVM Version:    1.8.0_202-b08
JVM Vendor:     Oracle Corporation</code>

