                                                                                             ^
                                                                                              \
                                                                                               | 
                                                                                               |Raw
Copy these Codes below and then Paste to gradle.properties File.                              
_______________________________________________________________________

# Enable daemon 
org.gradle.daemon=true

# Try and findout the best heap size for your project build.
org.gradle.jvmargs=-Xmx3096m -XX:MaxPermSize=512m -XX:+HeapDumpOnOutOfMemoryError -Dfile.encoding=UTF-8

# Modularise your project and enable parallel build
org.gradle.parallel=true

# Enable configure on demand.
org.gradle.configureondemand=true



