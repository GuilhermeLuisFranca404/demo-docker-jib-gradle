### Testing
```
$ gradle test
```
### Build (with tests)
```
$ gradle build
```
### Build (no tests)
```
$ gradle assemble
```
### Run image Docker
```
docker run --rm -p 8080:8080 -t demoapp-example-jib:latest
```
<br><br>



### Running in Docker and dockerRun
```
$ gradle assemble docker dockerRun --info
```
<br><br>


### Build Docker with jib and run with dockerRun:
```
gradle jibDockerBuild dockerRun
```
### Stopping Docker container
```
$ gradle dockerStop
```
<br>

## JIB?
Jib is a tool to work with fat jar, generated:
``` $ java -Djarmode=layertools -jar demoAPP-0.0.1-SNAPSHOT.jar extract ```
