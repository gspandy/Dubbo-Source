apache-maven-3.6.3



dubbo-2.7.5-release



在maven仓库中一定要配置阿里镜像

```xml
 <mirror>
	<id>nexus-aliyun</id>
	<mirrorOf>*</mirrorOf>
	<name>Nexus aliyun</name>
	<url>http://maven.aliyun.com/nexus/content/groups/public</url>
</mirror>
```




接着会报循环依赖的错误，fix忽略即可。





使用  clean package  不要用install



