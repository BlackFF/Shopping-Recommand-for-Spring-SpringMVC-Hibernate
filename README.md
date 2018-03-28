# Shopping-Recommand-for-Spring-SpringMVC-Hibernate
在线购物商城个性化商品推荐（Spring+SpringMVC+Hibernate）

# 项目功能介绍

   本项目是一个在线购物商城，但是请注意，此网站是单商家，也就说这里一个商家可以添加多种商品，而不是像淘宝一样可以有多个商家。而且本项目也仅供学习交流，禁止用作任何商业用途。


# 主要功能

普通用户：

    1.登录、注册功能 
    
    2.浏览商品功能 
    
    3.搜索商品功能 
    
    4.查看商品详情 
    
    5.添加购物车 
    
    6.购买功能（在商品详情页单独购买或在购物车批量购买） 
    
    7.查看订单状态 
    
    9.确认收货功能 
    
    10.评价已购买商品功能

系统功能：

    1.通过模糊匹配算法，实现数据的匹配与解析。
    
    2.	基于内容的推荐，根据类型和商品的详细信息进行解析、录入，进行匹配推荐。
    
    3.	基于时间的推荐，根据时间的算法，匹配季节的信息，进行推荐。
    
    4.	基于地理位置的推荐，根据所处的地理位置进行算法匹配。
    
    5.	基于热度的推荐，进行推荐。
    
管理员：

    1.拥有普通用户所有功能 
    

2.查看、删除所有用户功能 
    
    3.查看、删除所有商品功能 
    
    4.添加新的商品功能 
    
    5.处理订单功能 
    
    6发货功能

# 项目主要技术与工具

开发工具及环境

    IDE是Intellij IDEA，clone或者下载之后可以直接用IJ打开项目
    
    运行环境是Tomcat 9.0可以根据自己情况配置，7.0以上应该都行 
    
    项目版本管理使用了Maven工具，类型也为Maven项目 
    
    数据库使用了MySQL
    

开发技术

    后端框架为Spring+SpringMVC+Hibernate，注解形式 
    
   
    前端框架为Bootstrap，使用插件有Layer.js等 
    
    前后端交互方式为ajax，使用json格式传递数据
    
    
# 安装环境
Jdk 1.8 或者以上

Tomcat 7.0或者以上

Idea 2017

MySQL 57或者以上

Maven 工具 （最好换源）

其他 框架 和 jar 采用 maven 管理，打开项目，会自动下载。第一次	导入项目，务必 确保电脑 连接网咯。


# 注意

项目配置了Hibernate的自动数据库创建，项目对应MySQL数据库不需要专门用SQL创建，只需要在数据库新建一个shopping数据库即可，对应的表会在项目第一次运行时自动创建。
     

     
