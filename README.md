# Velocity Groovy Example Project

### Example Velocity Template Engine Groovy application generated with Gradle and shadow plugin.

1. To build shadow jar execute:

       ./gradlew build shadowJar

2. To run with Java execute:

        java -jar ./app/build/libs/app-all.jar $PWD testtemplate.vm

> **_NOTE:_**  In order to run gradle make sure to enable SDKMAN:

    source "$HOME/.sdkman/bin/sdkman-init.sh"

**See also**:

- https://sdkman.io/install
- https://velocity.apache.org/engine/2.3/developer-guide.html
- https://imperceptiblethoughts.com/shadow/getting-started/#default-java-groovy-tasks
