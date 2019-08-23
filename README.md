# Simple Angular app with Maven build

A simple Angular 7 application builded with eirslett/frontend-maven-plugin, in this example I have used a base configuration but for additional details we can visit the official plugin repository [front-end-maven-plugin](eirslett/frontend-maven-plugin).

## Proxy Setting

If we are behind a proxy, we can activate proxy configuration for do this is very easy, all that you need is set attribute:
```
<configuration>
    <npmInheritsProxyConfigFromMaven>true</npmInheritsProxyConfigFromMaven>
</configuration>
```

## Build

```
mvn clean install
```

### Artifact

The directory **dist** contains the angular app builded, ready to deploy.
