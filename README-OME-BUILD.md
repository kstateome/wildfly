mvn clean deploy -DskipTests -Denforcer.skip=true

cd build/target
tar -cf wildfly-8.2.0.1.Final.tar wildfly-8.2.0.1.Final/
gzip wildfly-8.2.0.1.Final.tar
scp wildfly-8.2.0.1.Final.tar.gz kaz0358@ome-tools1.campus.ksu.edu:/as/data/www/tools.ome.ksu.edu.ssl/htdocs/artifacts/devvm
