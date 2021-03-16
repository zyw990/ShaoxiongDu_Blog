# <center>SpringBoot个人博客</center>

## 效果预览 &nbsp;&nbsp;&nbsp;<a href='http://blog.shaoxiongdu.top' target ='_blank'>blog.ShaoxiongDu.top</a>

## 一.项目技术

#### * 后端采用SpringBoot框架 前端采用Semantic UI 全段模板引擎Thymeleaf

#### * 后端分为控制层 业务层 数据持久层 严格按照SpringMVC架构模式开发.

#### * 后端持久层框架采用SpringBootJPA，数据库为MySQL

## 二.部署教程

#### 1.  Fork本项目,用IDEA新建项目，选从版本工具导入，复制项目github地址 粘贴到IDEA中　点击clone　等待项目下载即可

#### 2. 下载完成之后，部分版本需要在项目结构中指定JDK，之后修改开发环境(-dev)的配置文件中的数据库信息,确保连接的是自己的数据库  修改datasource下的jpa的ddl为create

#### 3. 运行springboot项目 即可自动在数据库中创建表结构  

#### 4. 手动在user表中插入一条数据  注意密码存储采用MD5加密, 可以使用java/lrm/utils/MD5工具类中的主方法转换.

#### 5. 博客首页访问地址: localhost:80  博客后台登陆页面访问地址 localhost:80/admin

#### 6. 后台依次添加分类，标签，博客内容  博客主页刷新即可更新.

##### *注: 端口号可在主配置文件中修改

## 常见问题.

#### 如果您在学习或者部署本项目的时候遇到了任何问题，非常欢迎提出issues或者联系我。

#### 我的关注号【CodeKey】，日常分享一些编程中的面试题目，程序人生，理论知识等编程干货。

<img src="http://blog.shaoxiongdu.top/images/CodeKey.jpg" width='300px' />

## 四.赞赏

#### 如果觉得这个项目有趣,欢迎请作者喝一杯茶!

<img src="https://github.com/ShaoxiongDu/ShaoxiongDu/blob/main/wechatPay.jpg" width='300px' />
