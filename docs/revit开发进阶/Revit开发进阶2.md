# [Revit 开发学习大纲](https://binbinstrong.github.io/RevitDp_Learn/)



## markdown语法

用途：文档编写，



## VS创建项目

1. VS简介
2. 创建项目类型
   - .netframework 控制台应用
   - 共享项目
   - .netframework 类库

3. 应用.netFramework框架版本
4. vs项目管理

   - 解决方案

   - 项目

   - 命名空间（文件夹）
     - 引用
       - 本地程序集
       - 系统程序集
       - 共享项目

   - 项目属性设置
5. vs软件设置

   - 字体

   - 组件安装

   - 插件安装

   - nuget库
   - jetbrain 插件介绍 resharper
6. 常用快捷键 及快速输入
   - 代码补全
   - 代码片段管理 snippet

7. 调试运行
   - exe项目需要运行，并调试。按F5
   - 类库项目生成即可，并在目标程序内运行调试。在项目上点右键生成。



## C#基础

1. 程序集 Assembly  ,文件扩展名  .dll  .exe
2. 命名空间
3. 类/接口
   - 类的创建

   - 销毁
4. 字段/变量

   - 变量类型

   - 变量访问属性 public private 
5. 方法/函数
6. 程序基本结构

   - 顺序

   - 分支

   - 循环





## Revit调试准备



### Revit开发各版本对应.net

Revit 2017: .NET Framework 4.5.2

Revit 2018: .NET Framework 4.6

Revit 2019: .NET Framework 4.7

Revit 2020: .NET Framework 4.7.2

Revit 2021: .NET Framework 4.8

Revit 2022: .NET Framework 4.8



### 安装AddinManager和Lookup



### 使用Lookup和 AddinManager



## Revit帮助文档 RevitApi.chm使用方法

- 帮助文档

  <left>
      <a href="Revit Api帮助文档\20\RevitAPI.chm">revitApi2020.chm</a>
  </left>

- 使用

1. 获取

   通常帮助文档都在Revit SDK开发包里面

2. 查询

   在搜索框内输入关键字，回车即可显示素有相关类和字段

   <left>
       <img src="assets/image-20231031155656994.png">
   </left>





## 第一个Revit程序  HelloWorld!



1. 创建类库项目

2. 引用revit 相关程序集 RevitApi.dll ，RevitApiUI.dll等

3. 继承接口 IExternalCommand

4. 实现接口

5. 编写主程序

6. 调试

   1. 使用Addinmanager调试
   
   2. 通过addin文件添加来
   
   3. 
   





