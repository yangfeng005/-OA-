# 帆航OA系统

##  项目介绍

​     帆航OA系统基于开源流程引擎camunda开发的办公自动化系统。采用前后端分离架构，基于可视化的表单建模、流程建模工具，零代码快速构建业务OA应用。

## 项目演示

地址：http://119.29.209.39:8000/  账号密码：admin/123456

## 技术栈

后端：SpringBoot+JWT+Shiro+mybatis-plus

流程引擎：camunda

前端：Vue3， ant-design-vue

中间件：redis缓存，minio文件管理

数据库：mysql或postgresql

## 产品功能

### 1.表单设计

   在线可视化表单设计器可快速构建业务表单，表单设计器包含表单组件、辅助组件、布局组件、系统组件等多种组件，可构建复杂页面功能，支持表单预览，所见即所得。

![image-20230601225921985](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601225921985.png)

   基于设计的表单动态生成业务实体表，页面设计完成后，发布即可完成对应表单的数据库表结构设计。操作简单，业务人员能够快速上手。

![image-20230601225855323](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601225855323.png)

### 2.流程设计

​    BPMN2.0规范，基于开源camunda流程引擎开发，支持浏览器在线设计流程；支持驳回、拒绝、撤销等多种中国特色流程操作。

![image-20230601230835507](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601230835507.png)

![image-20230601230637109](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601230637109.png)

支持流程节点和设计的表单绑定。

![image-20230601232829791](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232829791.png)

流程设计完成，发布部署流程。

### 3.流程执行监听

​     系统内置了表达式和Java类两种监听类型，支持开发人员扩展，方便业务人员在设计流程时参照，配置节点审批人的获取方式。

![image-20230601231157309](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601231157309.png)

### 4.流程发起

​      申请人发起流程。

![image-20230601231554282](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601231554282.png)

![image-20230601231942662](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601231942662.png)

### 5.我的发起

![image-20230601232138450](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232138450.png)

![image-20230601232214638](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232214638.png)

![image-20230601232238432](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232238432.png)

### 6.我的待办

![image-20230601232400477](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232400477.png)

![image-20230601232435638](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232435638.png)

![image-20230601232451083](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232451083.png)

### 7.我的已办

![image-20230601232544893](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232544893.png)

 ![image-20230601232613715](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232613715.png)

![image-20230601232633418](https://gitee.com/yangfeng005/oa/blob/master/images/image-20230601232633418.png)

## 咨询

杨先生：

邮箱：[1041114134@qq.com](mailto:835487894@qq.com)

手机：15287192249

微信号：FinelyYang