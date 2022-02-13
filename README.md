![](https://github.com/Lylio/image-repo/blob/master/logos/quarkus.png?raw=true)
![](https://github.com/Lylio/image-repo/blob/master/logos/franky-03.png?raw=true)
# Quarkenstein
## A Quarkus Test Microservice

### Description
Quarkenstein is a creaky test Quarkus app for screwing in and bolting on random experimental components.

#### Maven Launch
1. `mvn quarkus:dev`
2. Open browser at http://localhost:8080/

#### Docker Launch
1. `docker build -t quarkenstein .`
2. `docker run -p 8080:8080 quarkenstein:latest`
3. Navigate to http://localhost:8080/