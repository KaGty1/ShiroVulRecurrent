### Welcome to `ShiroVulRecurrent`

`ShiroVulRecurrent`为一个简易的`Shiro`本地项目，采用`SpringBoot`+`maven`搭建，致力于供安全研究者更方便地复现`Shiro`漏洞

`JDK`版本：`JDK_8`



#### 快速更换`Shiro`版本

在`pom.xml`文件中更改`<shiro.version>`标签中的版本即可

```xml
<properties>
        <java.version>8</java.version>
        <shiro.version>1.7.1</shiro.version>
 </properties>
```



#### `ShiroFilterFactoryBean`快速配置权限

在`ShiroConfig`类的`shiroFilterFactoryBean`方法中快速配置访问权限

![image-20250306114629024](https://img-1325537595.cos.ap-beijing.myqcloud.com/undefinedimage-20250306114629024.png)



#### 修改访问跟路径与端口信息

在`appilcation.properties`中快速修改跟路径与端口信息

![image-20250306114842737](https://img-1325537595.cos.ap-beijing.myqcloud.com/undefinedimage-20250306114842737.png)
