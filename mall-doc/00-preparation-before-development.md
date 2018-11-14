0、开发环境
	JDK 1.8
	Spring Boot 2.0.6.RELEASE
	Spring Cloud Finchley.RELEASE
1、将maven的settings.xml中的mirror配置为阿里镜像
<mirror>
    <id>nexus-aliyun</id>
    <mirrorOf>*</mirrorOf>
    <name>Nexus aliyun</name>
    <url>http://maven.aliyun.com/nexus/content/groups/public</url>
</mirror>
2、idea配置template,将Preferences | Editor | File and Code Templates 配置下的,Class、Interface、Enum模版中加入
/**
* @date   : ${YEAR}-${MONTH}-${DAY} ${TIME}
* @author : congleiw@gmail.com
*/
3、安装alibaba-java-coding-guidelines插件