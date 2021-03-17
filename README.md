# <center>SpringBoot个人博客</center>

## 效果预览 &nbsp;&nbsp;&nbsp;

<a href='http://blog.shaoxiongdu.top' target ='_blank' >http://blog.ShaoxiongDu.top </a>

## 一.项目技术

 * 后端SpringBoot框架 分为控制层(Controller) 业务层(Service) 数据持久层(Dao) 按照SpringMVC架构模式规范进行开发.
   
 * 前端Semantic UI 前端模板引擎Thymeleaf
   
 * 数据持久层采用SpringBootJPA，数据库为MySQL8.0

## 二.部署教程

#### 1.导入项目

    Fork本项目,用IDEA新建项目，点击 Create Project For Version Control，复制项目github地址 粘贴到IDEA中的Git地址 选择　点击clone　等待项目下载即可
 
#### 2.配置项目依赖

    部分版本需要在项目结构中指定JDK
 
#### 3.配置数据库

    之后修改开发环境(-dev)的配置文件中的数据库信息,确保连接的是自己的数据库,修改属性 ddl-auto 为 create

#### 4.生成表结构

    运行springboot项目 即可自动在数据库中创建表结构
 
#### 5.插入管理员数据

    用数据库管理工具手动在user表中插入一条数据  注意密码存储采用MD5加密, 可以使用java/lrm/utils/MD5工具类中的主方法转换. 其余属性见名知意
 
#### 6.访问博客

    博客首页访问地址: localhost:80  博客后台登陆页面访问地址 localhost:80/admin
 
#### 7.添加数据

    后台依次添加分类，标签，博客内容  博客主页刷新即可更新.
 
#### 8.自定义博客IP

    页面顶端以及底部的个人IP在 src/main/resources/templates/_fragments.html 中 修改此文件中的指定内容即可同步至项目全部页面
    管理员的顶部底部模板文件在admin文件下 _fragemnts.html

#### 9.注意事项

    *注: 项目端口号可在主配置文件中修改 默认为 80 端口


## 10.项目反馈及改进

  > 如果您在学习或者部署本项目的时候遇到了任何问题，或者项目有任何可以改进的地方，欢迎提出issues或者联系我<shaoxiong.dev@aliyun.com>。
> 我会将您添加到项目贡献者中。


## 三.编程干货 

  > 我的关注号【CodeKey】，日常分享一些中的干货 【面试宝典,程序人生，数据结构，LeetCode题解】等......

<img src="http://blog.shaoxiongdu.top/images/CodeKey.jpg" width='300px' />
