
# 

Usage:

```vget (application) (property)```

Example: 

```vget java version```

The above fetches the java version.

Other possible applications:

* java
* openssl
* tomcat
* filebeat



### Openssl
The available application/properties are:

* version 
* name*
* banner
* date
* path

Example: ```vget openssl path```

### Tomcat

* version
* banner
* jvmversion
* jvmvendor
* osname
* osversion
* arch

### Java

* banner
* version
* runtime
* path

### Filebeat

* version
* path
