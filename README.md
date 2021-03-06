## YbGoCloundFramework
----
## 基于Golang，Beego框架的SAAS云平台开发框架，根据多年开发经验创新性地进行架构设计，模块重用高、用户体验佳、性能卓越、数据分级隔离、也非常有利于减少项目后期管理和维护的工作量。 
本框架开发过众多项目，目前仅开源基础权限框架部分及部分公共模块功能。 

## 框架特性
### 本框架可在一套源码中同时开发、管理和维护多个项目，做到多个项目模块复用的最大化的同时，还可大大减少后期的开发维护工作量
### 集成权限模块，实现了简单的单点登录功能，权限资源通过XML文件进行配置，部署和维护比数据库中配置更方便，一个模块可多个项目重用，仅需配置下基础权限即可，非常的方便和灵活
### SAAS云平台架构，分为系统->应用->租户->用户四级，可控制每个级别的功能权限和数据权限。 
### RBAC的权限控制方式，集成组织机构管理、角色管理、用户管理、权限资源管理，不同应用间数据完全隔离。
### 集成了灵活、强大的配置设置管理功能，同样分为系统->应用->租户->用户四级，每级具有权限的管理人员可自行管理的设置项，配置好各级设置后，不同应用、租户、用户间的设置值完全独立。 
### 本框架开源部分涵盖了区域、流水号生成、基础代码管理等常用模块，可大大减少后期开发的工作量。
### 性能优越、用户体验佳、集成Cache功能

### 安装方法    
----
1、go get https://gitee.com/yellbuy/YbGoCloundFramework    
2、创建mysql数据库，并将YbGoCloundFramework.sql导入    
3、修改config 配置数据库    
4、运行 go build    
5、运行 ./run.sh start|stop    
6、文件夹assets下分别为各个项目的权限资源和配置设置相关的XML文件    

访问地址：http://your_host:8081
用户名：admin 密码：123456

### 许可证协议：
----
https://github.com/yellbuy/go-cloud-framework/edit/master/LICENSE.txt?raw=true

### 联系我
----
QQ：19892257

效果展示
----
### 基础框架：本次开源部分截图<br/>
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/1.1.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/1.2.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/1.3.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/1.4.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/1.5.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/1.6.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/1.7.png?raw=true)
<br/>
### 自定义表单，自定义流程<br/>
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/5.1.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/5.2.png?raw=true)
### 某电商Demo<br/>
1）小程序二维码
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.0.jpg?raw=true)
<br/>
2）电商后端
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.1.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.2.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.3.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.4.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.5.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.6.png?raw=true)
3）电商前端
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.7.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.8.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.9.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.10.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.11.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.12.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.13.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.14.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/3.15.png?raw=true)
<br/>
### CMS部分Demo<br/>
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/2.1.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/2.2.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/2.3.png?raw=true)
### 某金融项目<br/>
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/4.1.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/4.2.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/4.3.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/4.4.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/4.5.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/4.6.png?raw=true)
### 某快递物流项目<br/>
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/6.1.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/6.2.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/6.3.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/6.4.png?raw=true)
![image](https://github.com/yellbuy/go-cloud-framework/blob/master/demo/6.5.png?raw=true)
<br/>
### 其他项目略去
......
