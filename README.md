# tomcat
tomcat 8.5源码，并且解决了控制台输出乱码的问题。加上VM参数就可以直接启动

-Dfile.encoding=UTF-8
-Dcatalina.home=/Users/haopangang/IdeaProjects/tomcat
-Dcatalina.base=/Users/haopangang/IdeaProjects/tomcat
-Djava.endorsed.dirs=/Users/haopangang/IdeaProjects/tomcat/endorsed
-Djava.io.tmpdir=/Users/haopangang/IdeaProjects/tomcat/temp
-Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
-Djava.util.logging.config.file=/Users/haopangang/IdeaProjects/tomcat/conf/logging.properties
