### 调试tomcat源码 添加注释
1.添加调试参数
> -Dcatalina.home=C:/Users/missb/IdeaProjects/tomcat_src/home
  -Dcatalina.base=C:/Users/missb/IdeaProjects/tomcat_src/home
  -Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
  -Djava.util.logging.config.file=C:/Users/missb/IdeaProjects/tomcat_src/home/conf/logging.properties
>
2. MainClass入口
> org.apache.catalina.startup.Bootstrap