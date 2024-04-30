Compile:
```bash
JAVA_HOME=/usr/lib/jvm/java-17-openjdk
make OS_NAME=Linux OS_ARCH=x86_64 CCFLAGS="-fpic -I${JAVA_HOME}/include/linux -I${JAVA_HOME}/include/" native native
```
