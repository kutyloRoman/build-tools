# build-tools
## 1. Maven
 mvn package - to compile and build jar and war for all modules
mvn test - to run tests for all modules

## 2. Gradle
#### to build project
```bash
gradle build
```
#### to run test
```bash
gradle test
```
## 3. ANT+Ivy
#### Cd to folder with scripts
```bash
cd ant-build
```
#### to build jar for specified module
```bash
ant --buildfile <buildfile> dist 
```
#### to run test
```bash
ant --buildfile <buildfile> junit
```
