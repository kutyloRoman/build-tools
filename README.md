# build-tools
1. Maven
mvn package - to compile and build jar and war for all modules
mvn test - to run tests for all modules

2. Gradle
gradle build - to build project
gradle test - to run test

3. ANT+Ivy
cd ant-build
ant --buildfile <buildfile> dist - to build jar for specified module
ant --buildfile <buildfile> junit - to run test
