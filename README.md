# 准备&&说明
## 自定义配置文件的路径
Sublime安装完第一次运行的时候，会默认在`%appdata%`目录下生成一个Sublime Text的文件夹，用于存放配置文件及以后安装的各种插件。

我们要做的是不让他在默认的位置生成配置文件，而是要改到我们自定义的软件安装目录中，此时有两种情况：

**第一种情况**

 Sublime还没安装或者安装之后还没运行过：安装好之后**不要启动**软件，然后在进入安装目录，新建一个`Data文件夹`，注意文件夹名称大小写。例如我电脑上新建好Data文件夹之后的路径是这样的：`E:\ProgramFiles\Sublime Text 2/Data`。

**第二种情况**

Sublime已经运行过：关掉Sublime，在地址栏输入`%appdata%`，然后删除该目录下的Sublime Text文件夹。不要运行软件，按照上面情况1的步骤操作。

经过以上操作再运行软件，所有的配置文件及以后安装的插件就会生成在Data文件夹中了。

## 使用说明
这个仓库存放的是Data目录下Packages文件夹的所有内容，所以如果你准备克隆使用我的插件及配置，先按照上面`自定义配置文件的路径`的步骤在安装目录创建好Data文件夹，然后进入Data文件夹，克隆这个Repository并命名为`Packages`即可（注意大小写）：

```
git clone <my repository address> Packages
```

执行完上面的步骤，再启动Sublime之后，它就会按照配置文件去自动下载相应的插件。Over。

> 你也可以按如上方式把自己`Packages`文件夹关联到Github上的仓库，这样即使换电脑只要克隆这个仓库到指定位置就可以快速完成配置了。

# 插件清单（持续更新...）

- HTML-CSS-JS Prettify

	右键格式化html、css、js三种文件类型的代码。
- SublimeTextTrans-master

	调整Sublime的透明度。方法：`视图》Windows Transparency`
- SublimeTmpl


- ZZZZZZZZ-Localization

	经典的Sublime汉化包。安装好之后也可以切换成英文或者别的语言，方法：`帮助》Language`。
- AutoFileName

	自动匹配引入的文件路径。
- Emmet

	不用多说，前端必备，代码自动补全。

	

# 自定义配置（持续更新...）