# VisualStudio 使用介绍

 


1. VlisualStudio简介

2. 创建项目类型

   - .netframework 控制台应用

   - 共享项目

   - .netframework 类库
   
   ```c#
   using Autodesk.Revit.DB;
   using Autodesk.Revit.UI;
   using System;
   using System.Collections.Generic;
   using System.Linq;
   using System.Text;
   using System.Threading.Tasks;
   //using Autodesk.Revit
   
   namespace RevitFirstApp
   {
       public class RevitPopupWin : IExternalCommand
       {
           public Result Execute(ExternalCommandData commandData, ref string message, ElementSet elements)
           {
               var result = default(Result);
   
               var num = 22222;
   
   
               if (true)
               {
   
               }
   
               
    
   
   
               return result;
           }
   
   
       }
   
   }
   
   ```
   
   
   
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
   
6. 常用快捷键 及 代码快速输入

   - 代码补全

   - 代码片段管理 snippet
   
     <left>
         <img src="revit开发入门/assets/image-20231105152132743.png"
     </left>
     
     
   
7. 调试运行

   - exe项目、控制台项目 运行 并调试。按F5
   
   - 类库项目生成即可，并在目标程序内运行调试。在项目上点右键生成。

## 快捷键

### 注释   

ctrl + k   ctrl+ c  
