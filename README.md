### sonar-java
---
https://github.com/SonarSource/sonar-java

```java
sonar.runtimeVersion=7.9
maven.localRepository=/home/myName/.m2/repository
```

```sh
mvn clean install
export ORCHESTRATOR_CONFIG_URL=file:///home/user/workspace/orchestrator.properties
mvn clean install -Pit-plugin
git submodule init
git submodule update
cd its/ruling
mvn clean install -DskipTests=false
cp its/ruling/target/actula/* its/ruling/src/test/resources/
```

```
```
