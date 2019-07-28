# Activiti 流程引擎

## 工作流入门

### 部署环境介绍

- 体验Activiti官网 https://www.activiti.org
- 物料准备：
  - Activiti软件包 activiti-6.0.0.zip
  - Java环境1.8.0_161
  - Servlet容器 apache-tomcat-8.0.50.zip



### 准备环境并部署Activiti6.0

![1564307637046](D:\workspace-idea-work\xiYiJiaoYu\project4\doc\img\1564307637046.png)

![1564307722659](D:\workspace-idea-work\xiYiJiaoYu\project4\doc\img\1564307722659.png)

将activiti-app.war、activiti-app.war复制到tomcat\wabapps文件夹下,并启动，

浏览器输入：<http://localhost:8080/activiti-app  

默认用户名：adim  密码： test

![1564308775366](D:\workspace-idea-work\xiYiJiaoYu\project4\doc\img\1564308775366.png)

### Activiti6.0快流体验

#### 流程如下：

``````mermaid
graph LR
 id1((StartEvent<br>开始)) --> id(UserTask<br>TL审批)
 id --> id2(UserTask<br>HR审批)
 id2 --> id3((EndEvent <br> 结束))



``````

流程参与者，创建三个用户：

|ID|password|



![1564311325623](D:\workspace-idea-work\xiYiJiaoYu\project4\doc\img\1564311325623.png)





## 源码初探

### 概览与获取

### engine

### 模块介绍

### activiti-app运行

