# adigsom-spring-boot
Imagen de Docker personalizada para aplicaciones de arranque apps

La aplicación debe llamarse spring-boot.jar

El contenedor se expone en el puerto 8080.

## How to use

### Main Environment variables

JAVA_OPTS

SPRINGBOOT_OPTS

DEBUG

you can use these and your own variables in your application.

### Build
```
docker build -t {root}/spring-boot-base:1.0.0-SNAPSHOT .
```

### Push
```
docker push {root}/spring-boot-base:1.0.0-SNAPSHOT
```

## Docker Image
```
docker pull adigsom/spring-boot-base:1.0.0
```