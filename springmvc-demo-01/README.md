## 创建项目
1. 在IDEA欢迎页面 选择create new project 或者在打开的工程上方工具栏选择File → NEW → Project 

2. 左侧栏位选择Maven

3. 右侧栏位上方选择JDK版本，这里使用的是JDK1.7

4. 右侧栏位下方勾选 create from archetype （从maven的原型模版生成项目）

5. 选择org.apache.maven.archetypes:maven-archetype-webapp 选择后 点NEXT按钮 下一步

6. 在groupid 中填入所属组织唯一标识 对应包路径，artifactId 填入项目唯一标识 对应项目名称 填好后 点NEXT按钮 下一步

7. 选择Maven的配置Maven的目录 配置文件位置 以及 本地仓库的位置。  
    IDEA 虽然自带Maven3推荐使用自己下载Maven的最新版本 然后配置文件里改成aliyun的Maven仓库 有时使用IDEA自带的maven不但慢而且会卡。  
    配置完成后 点NEXT按钮 下一步

8. 填写项目名称，设置项目的根目录 这里项目名称和目录名可以不同 后方...可以选择本地目录 配置完毕后 Finish 创建完成

9. 在main下新建一个目录java

10. 在工程下与src平级建立一个目录 test

11. 工具栏 File → Project structure 选择左侧的 Modules 在右侧设置新建的java目录为Source test 目录为Tests 选中目录点击带颜色的按钮即可

12. 配置Tomcat 点选上方运行按钮左侧的配置按钮进行配置，图片配置说明比较容易理解，建议搜索一下看看。

至此 一个可运行的项目搭建完成了 运行debug 可以看到浏览器弹出的hello world！页面。

创建完项目 在project 视图里可能看到不到自动生成的项目结构，需要等待一下Maven构建项目需要一点时间。

如果你使用了git作为项目的版本控制工具 需要在项目中添加 .gitignore 文件 来忽略掉本地的项目工程文件和编译输出的文件。
IDEA中可以安装插件 ignore ，安装完成后可以在项目名上点击右键菜单→ NEW → ignore file 选择 .gitignore

等等 还少了sprin和 springmvc

