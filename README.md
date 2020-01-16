# 关于ASP.NET MVC模式

1. 001MVCDEMO

* 1.1 初识MVC--TestController.cs
* 1.2 简单的增删改查--PersonController.cs
* 1.3 关于layout--LayoutTestController.cs

2. 002CheckData

* 1.1 判断请求是否来自Ajax--IsAjaxRequestController.cs
* 1.2 数据检验--使用Attribute
* 1.3 输出数据错误信息--ModelState
* 1.3 自定义特性进行数据验证--在Common文件夹中添加自定义的特性类


3. 003DropDownList

* 1.1 自己实现DropDownList选中--DropDownlist1Controller.cs
* 1.2 使用Html辅助类：@Html.DropDownList--DropDown2Controller.cs


4. 004FilterTest1

* 1.1 检验是否登录--CheckAuthorFilter.cs
* 1.2 日志：记录访问信息--LogActionFilter.cs
* 1.3 记录异常信息--ExceptionFilter.cs


5. 005Html辅助类

   不建议使用，但是Html.DropDownList()还是挺方便的

* 1.1 Html.BeginForm()等
* 1.2 Html.validationMessage()和Html.validationSummary()

6. 006特性路由

* 在RoutesConfig.cs中RegisterRoutes（）中routes.MapMVCAttributeRoutes()

7. 007传统路由

* 路由规则，默认路由，路由顺序，路由约束
* 选择传统路由还是特性路由

8. 008Log4Net

* NuGet:`Install-Package log4net -Version 2.0.8`(注意项目是基于.net 4.6.1)
* Log4Net在Web.config中的配置
* 使用过滤器配置将不同级别的日志记录在不同而文件中