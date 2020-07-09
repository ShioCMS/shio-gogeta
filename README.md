![gogeta-banner.png](https://shiocms.github.io/shio-gogeta/gogeta-banner.png) 
------

**Shio Gogeta CMS** - Shio CMS concepts ported to Apache Sling.

Shio (pronounced [strong/ʃiː/ weak/ʃɪ/ o])

**If you'd like to contribute to Viglet Shio, be sure to review the [contribution
guidelines](CONTRIBUTING.md).**

**We use [GitHub issues](https://github.com/ShioCMS/shio-gogeta/issues) for tracking requests and bugs.**

# Installation

## Download

```shell
$ git clone https://github.com/ShioCMS/shio-gogeta.git
$ cd shio-gogeta
```

## Deploy 

### 1. Compile

Use Maven to compile Shio CMS Gogeta.

```shell
$ mvn clean install
```
### 2. Run

To run execute.

```shell
$ cd builder/target
$ java -jar org.apache.sling.cms.builder-0.16.3-SNAPSHOT.jar 
```

## Shio CMS Goget
* Administration Console: [http://localhost:8080/system/sling/form/login](http://localhost:8080/system/sling/form/login).

> login/password: admin/admin
