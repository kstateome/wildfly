```
 jdk8
 /Users/kaz/install/apache-maven-3.3.3/bin/mvn clean deploy -DskipTests -Denforcer.skip=true
 
 cd dist/target
 tar -cf wildfly-9.0.1.1.Final.tar wildfly-9.0.1.1.Final/
 gzip wildfly-9.0.1.1.Final.tar
 scp wildfly-9.0.1.1.Final.tar.gz kaz0358@ome-tools1.campus.ksu.edu:/as/data/www/tools.ome.ksu.edu.ssl/htdocs/artifacts/devvm
```
