# TelSystem

#### 介绍

- 通讯录系统，包含CRUD(含多重复杂查询)、Excel导入导出、图形量化分析，麻雀虽小五脏俱全！
- 技术栈：前端:Ext、后端SpringBoot，使用forestry模板。
- 是我在参与正式付费项目之前最后一个自制项目，虽然没有什么新技术，但能够稳固自己的基础。


![主界面](https://images.gitee.com/uploads/images/2020/0617/224707_dd8f8f9b_7525468.png "主界面.png")

#### 软件架构

- --src
- 	--core  模板
- 	--ypc--zwz--controller  控制层
- 	--ypc--zwz--service     业务逻辑层
- 	--ypc--zwz--dao         数据持久层
- 	--ypc--zwz--model       数据模型
- 	--ypc--zwz--core         相关工具类
- --resources
- 	--applicationContext.xml   配置文件
- 	--jdbc.properties          配置数据库信息
- --WebContent
- 	--static--download  Excel导出模板文件
- 	--static--ext--examples--portal  前台ExtJS文件
- 	--static--img   前台背景图片
- 	--WEB-INF--lib 所需要的Jar包
- 	--WEB-INF--page--back--main.jsp  主页
- 	--WEB-INF--page--loginExt.jsp  登入页面验证码输入错误后的登入页面
- 	--WEB-INF--page--loginFail.jsp  登入失败的页面(不包含验证码错误)
- 	--WEB-INF--web.xml  配置文件
- 	loginExt.jsp   登入页面


#### 安装教程

1.  使用IDE（我是用eclipse202003）导入项目
2.  修改Java build path中的 JDK 、Tomcat版本
3.  在jdbc.properties中，修改数据库配置
3.  运行项目


#### 个人博客

https://blog.csdn.net/qq_41464123

![我的博客](https://images.gitee.com/uploads/images/2020/0526/132246_599dbf21_7525468.jpeg "在这里输入图片标题")
