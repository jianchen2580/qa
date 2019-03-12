###软件测试的概念###

https://www.cnblogs.com/findyou/p/6480411.html

**注：不需要太关注黑盒白盒测试**

注意按阶段划分：

- 单元测试：开发阶段由develper写
- 集成测试：QA测试
- 系统测试：QA测试
- 验收测试：QA测试

**注：回归测试是指fix bug后要跑一遍测试，以防bug fix破坏其它功能模块或者引入新的bug**

软件开发流程
 
    开发->测试->fix bug ->alpha -> beta -> prod 

软件部署流程

    开发本地开发环境 -> QE环境-> stage 环境 -> production 环境

#### Tools

selenium: https://www.jianshu.com/p/d3ca1cb64e37

### CI/CD: 持续集成，持续开发 ###

主要工具有Jenkins, Jenkins pipeline 是Jenkins 的精华

相关blog：

Jekins： https://www.jianshu.com/p/d23628fd906a

Jenkins pipeline: https://www.jianshu.com/p/307e76803355

### Linux

### 脚本能力:  Python 和 Bash

### DevOPS

其实就是持续交付 + 配置管理

#### 持续交付

使用Jenkins实现持续交付
blog: https://www.jianshu.com/p/5b433bc5ddf6

#### 配置管理

** Tools **

下面三个tools都能实现配置管理，选用其中一个就可以

- Ansible
- Chef
- Puppet

### Docker + K8s

**Docker** 

- 写 Dockerfile
- docker build 出一个image
- 在docker daemon上run image 

** kubernetes **

在集群上run docker image 
blog： https://www.jianshu.com/p/4dcfcde779e1
